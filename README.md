# Helm-Charts
Issues Faced:

while running MYSQL client,
I have no name!@mysql-release-client:/$ mysql -h mysql-release.default.svc.cluster.local -u root -p "$MYSQL_ROOT_PASSWORD"
I came across 

## ERROR 2003 (HY000): Can't connect to MySQL server on 'mysql-release.default.svc.cluster.local:3306' (110)

### Solution:
Decode base64 password first.
Must change File Permission in /etc/mysql.
Resolved!
