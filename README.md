# percona-toolkit-xtrabackup docker image ()

NOTE: fork fr3nd/docker-percona-toolkit and Percona xtrabackup added

## Percona toolkit

Percona Toolkit for MySQL® is a collection of advanced open source command-line
tools, developed and used by the Percona technical staff, that are engineered
to perform a variety of MySQL and system tasks that are too difficult or
complex to perform manually. Percona Toolkit supports Percona Server, MySQL®
and MariaDB® and works best with Percona Server and other Percona products.

* https://www.percona.com/software/mysql-tools/percona-toolkit

Included tools

* pt-align
* pt-archiver
* pt-config-diff
* pt-deadlock-logger
* pt-diskstats
* pt-duplicate-key-checker
* pt-fifo-split
* pt-find
* pt-fingerprint
* pt-fk-error-logger
* pt-heartbeat
* pt-index-usage
* pt-ioprofile
* pt-kill
* pt-mext
* pt-mysql-summary
* pt-online-schema-change
* pt-pmp
* pt-query-digest
* pt-show-grants
* pt-sift
* pt-slave-delay
* pt-slave-find
* pt-slave-restart
* pt-stalk
* pt-summary
* pt-table-checksum
* pt-table-sync
* pt-table-usage
* pt-upgrade
* pt-variable-advisor
* pt-visual-explain

## Percona xtrabackup

Percona XtraBackup is a free, open source, complete online backup solution for all versions of Percona Server, MySQL® and MariaDB®. With over 1,000,000 downloads, Percona XtraBackup performs online non-blocking, tightly compressed, highly secure backups on transactional systems so that applications remain fully available during planned maintenance windows.

* https://www.percona.com/software/mysql-database/percona-xtrabackup

Percona XtraBackup provides:

* Fast and reliable backups
* Uninterrupted transaction processing during backups
* Savings on disk space and network bandwidth with better compression
* Automatic backup verification
* Higher uptime due to faster restore time

## Docker hub

Docker hub URL:
https://hub.docker.com/r/joaquindlz/docker-percona-toolkit-xtrabackup

Docker image download:
docker pull joaquindlz/docker-percona-toolkit-xtrabackup
