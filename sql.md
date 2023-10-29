# SQL interpreters

## MySQL compatible

* [MySQL](https://www.mysql.com/) - the oroginal;
* [MariaDB](https://mariadb.org/) - fork of the original made by author of the original;
* [Percona Server for MySQL](https://www.percona.com/mysql/software) - fork of the original code base;
* [Go MySQL Server](https://github.com/dolthub/go-mysql-server) - completely new implementation written in Go; not threadsafe, without transaction support;
* [Dolt](https://github.com/dolthub/dolt) - based on Go MySQL Server; adds version control functionality.

# SQL dumpfile generators and interpreters

Generator | Interpreter | Compatiblity | Other
--- | --- | --- | ---
mysqldump | mysql | MySQL, ANSI and potentially other (see description for `--compatible` option) | limited to single thread; can also export to XML
mariadb-dump | mysql | MySQL, MariaDB and "ansi, mysql323, mysql40, postgresql, oracle, mssql, db2, maxdb" (see description for `--compatible` option) | can also export to XML; fork of mysqldump, so probably limited to single thread
[MySQL Shell Dump Utitlities](https://dev.mysql.com/doc/mysql-shell/8.0/en/mysql-shell-utilities-dump-instance-schema.html) | ? | ?
mysqlpump | mysql | MySQL | can utilize multiple threads (even up to 11x speedup vs singlethreaded mysqldump according to some tests)
[mydumper](https://github.com/mydumper/mydumper) | myloader | MySQL, Percona, MariaDB | can utilize multiple threads, supports Regex for specifying DB and table names; does not support Windows
Percona XtraBackup | ? | ? | ?
[Mariabackup](https://mariadb.com/kb/en/full-backup-and-restore-with-mariabackup/) | mariabackup | ? | fork of Percona XtraBackup; supports some specific MariaDB features like InnoDB Page Compression or Data-at-Rest Encryption; supports Windows; complicated partian backup
