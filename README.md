The simple way to backup and restore MySQL databases.
===

Backup:
> mysqldump -u[user] -p[password] [database_name] > [backup_database_name].sql

Restore:
> mysql -u[user] -p[password] [database_name] < [backup_database_name].sql
