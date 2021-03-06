# api-vesta



v-add-backup-ftp-host HOST USERNAME PASSWORD [PATH] [PORT]

v-add-cron-job USER MIN HOUR DAY MONTH WDAY COMMAND [JOB] [RESTART]

v-add-cron-report USER

v-add-cron-restart-job

v-add-cron-vesta-autoupdate

v-add-database USER DATABASE DBUSER DBPASS [TYPE] [HOST] [CHARSET]

v-add-database-host TYPE HOST DBUSER DBPASS [MAX_DB] [CHARSETS] [TEMPLATE]

v-add-dns-domain USER DOMAIN IP [NS1] [NS2] [NS3] [NS4] [RESTART]

v-add-dns-on-web-alias USER DOMAIN

v-add-dns-record USER DOMAIN RECORD TYPE VALUE [PRIORITY] [ID] [RESTART]

v-add-domain USER DOMAIN [IP] [RESTART]

v-add-mail-account USER DOMAIN ACCOUNT PASSWORD [QUOTA]

v-add-mail-account-alias USER DOMAIN ACCOUNT ALIAS

v-add-mail-account-autoreply USER DOMAIN ACCOUNT MESSAGE

v-add-mail-account-forward USER DOMAIN ACCOUNT FORWARD

v-add-mail-account-fwd-only USER DOMAIN ACCOUNT

v-add-mail-domain USER DOMAIN [ANTISPAM] [ANTIVIRUS] [DKIM] [DKIM_SIZE]

v-add-mail-domain-antispam USER DOMAIN

v-add-mail-domain-antivirus USER DOMAIN 

v-add-mail-domain-catchall USER DOMAIN EMAIL

v-add-mail-domain-dkim USER DOMAIN [DKIM_SIZE]

v-add-remote-dns-domain USER DOMAIN [FLUSH]

v-add-remote-dns-host HOST PORT USER PASSWORD [TYPE] [DNS_USER]

v-add-remote-dns-record USER DOMAIN ID



v-add-sys-ip

v-add-user

v-add-user-package

v-add-web-domain

v-add-web-domain-alias

v-add-web-domain-ftp

v-add-web-domain-proxy

v-add-web-domain-ssl

v-add-web-domain-stats

v-add-web-domain-stats-user

v-backup-user

v-backup-users

v-change-cron-job

v-change-database-owner

v-change-database-password

v-change-database-user

v-change-dns-domain-exp

v-change-dns-domain-ip

v-change-dns-domain-soa

v-change-dns-domain-tpl

v-change-dns-domain-ttl

v-change-dns-record

v-change-dns-record-id

v-change-domain-owner

v-change-mail-account-password

v-change-mail-account-quota

v-change-mail-domain-catchall

v-change-remote-dns-domain-exp

v-change-remote-dns-domain-soa

v-change-remote-dns-domain-ttl

v-change-sys-config-value

v-change-sys-ip-name

v-change-sys-ip-nat

v-change-sys-ip-owner

v-change-sys-ip-status

v-change-sys-language

v-change-user-contact

v-change-user-language

v-change-user-name

v-change-user-ns

v-change-user-package

v-change-user-password

v-change-user-shell

v-change-user-template

v-change-web-domain-ftp

v-change-web-domain-ip

v-change-web-domain-proxy-tpl

v-change-web-domain-sslcert

v-change-web-domain-sslhome

v-change-web-domain-stats

v-change-web-domain-tpl

v-check-user-password

v-delete-backup-ftp-host

v-delete-cron-job

v-delete-cron-reports

v-delete-cron-restart-job

v-delete-cron-vesta-autoupdate

v-delete-database

v-delete-database-host

v-delete-databases

v-delete-dns-domain

v-delete-dns-domains

v-delete-dns-domains-src

v-delete-dns-on-web-alias

v-delete-dns-record

v-delete-domain

v-delete-mail-account

v-delete-mail-account-alias

v-delete-mail-account-autoreply

v-delete-mail-account-forward

v-delete-mail-account-fwd-only

v-delete-mail-domain

v-delete-mail-domain-antispam

v-delete-mail-domain-antivirus

v-delete-mail-domain-catchall

v-delete-mail-domain-dkim

v-delete-mail-domains

v-delete-remote-dns-domain

v-delete-remote-dns-domains

v-delete-remote-dns-host

v-delete-remote-dns-record

v-delete-sys-ip

v-delete-user

v-delete-user-backup

v-delete-user-backup-exclusions

v-delete-user-ips

v-delete-user-package

v-delete-web-domain

v-delete-web-domain-alias

v-delete-web-domain-ftp

v-delete-web-domain-proxy

v-delete-web-domains

v-delete-web-domain-ssl

v-delete-web-domain-stats

v-delete-web-domain-stats-user

v-generate-ssl-cert

v-get-dns-domain-value

v-get-mail-account-value

v-get-mail-domain-value

v-get-user-value

v-get-web-domain-value

v-insert-dns-domain

v-insert-dns-record

v-insert-dns-records

v-list-backup-ftp-host

v-list-cron-job

v-list-cron-jobs

v-list-database

v-list-database-host

v-list-database-hosts

v-list-databases

v-list-database-types

v-list-dns-domain

v-list-dns-domains

v-list-dns-domains-src

v-list-dns-records

v-list-dns-template

v-list-dns-templates

v-list-mail-account

v-list-mail-account-autoreply

v-list-mail-accounts

v-list-mail-domain

v-list-mail-domain-dkim

v-list-mail-domain-dkim-dns

v-list-mail-domains

v-list-remote-dns-hosts

v-list-sys-config

v-list-sys-info

v-list-sys-interfaces

v-list-sys-ip

v-list-sys-ips

v-list-sys-languages

v-list-sys-rrd

v-list-sys-services

v-list-sys-shells

v-list-sys-users

v-list-sys-vesta-autoupdate

v-list-sys-vesta-updates

v-list-user

v-list-user-backup

v-list-user-backup-exclusions

v-list-user-backups

v-list-user-ips

v-list-user-log

v-list-user-ns

v-list-user-package

v-list-user-packages

v-list-users

v-list-users-stats

v-list-user-stats

v-list-web-domain

v-list-web-domain-accesslog

v-list-web-domain-errorlog

v-list-web-domains

v-list-web-domains-alias

v-list-web-domains-proxy

v-list-web-domain-ssl

v-list-web-domains-ssl

v-list-web-domains-stats

v-list-web-stats

v-list-web-templates

v-list-web-templates-proxy

v-rebuild-cron-jobs

v-rebuild-databases

v-rebuild-dns-domain

v-rebuild-dns-domains

v-rebuild-mail-domains

v-rebuild-user

v-rebuild-web-domains

v-restart-cron

v-restart-dns

v-restart-ftp

v-restart-mail

v-restart-proxy

v-restart-service

v-restart-system

v-restart-web

v-restore-user

v-schedule-user-backup

v-schedule-user-restore

v-search-domain-owner

v-search-object

v-search-user-object

v-start-service

v-stop-service

v-suspend-cron-job

v-suspend-cron-jobs

v-suspend-database

v-suspend-database-host

v-suspend-databases

v-suspend-dns-domain

v-suspend-dns-domains

v-suspend-dns-record

v-suspend-mail-account

v-suspend-mail-accounts

v-suspend-mail-domain

v-suspend-mail-domains

v-suspend-remote-dns-host

v-suspend-user

v-suspend-web-domain

v-suspend-web-domains

v-sync-dns-cluster

v-unsuspend-cron-job

v-unsuspend-cron-jobs

v-unsuspend-database

v-unsuspend-database-host

v-unsuspend-databases

v-unsuspend-dns-domain

v-unsuspend-dns-domains

v-unsuspend-dns-record

v-unsuspend-mail-account

v-unsuspend-mail-accounts

v-unsuspend-mail-domain

v-unsuspend-mail-domains

v-unsuspend-remote-dns-host

v-unsuspend-user

v-unsuspend-web-domain

v-unsuspend-web-domains

v-update-database-disk

v-update-databases-disk

v-update-dns-templates

v-update-mail-domain-disk

v-update-mail-domains-disk

v-update-sys-ip

v-update-sys-ip-counters

v-update-sys-queue

v-update-sys-rrd

v-update-sys-rrd-apache2

v-update-sys-rrd-ftp

v-update-sys-rrd-httpd

v-update-sys-rrd-la

v-update-sys-rrd-mem

v-update-sys-rrd-mysql

v-update-sys-rrd-net

v-update-sys-rrd-nginx

v-update-sys-rrd-pgsql

v-update-sys-rrd-ssh

v-update-sys-vesta

v-update-sys-vesta-all

v-update-user-backup-exclusions

v-update-user-backups

v-update-user-counters

v-update-user-disk

v-update-user-package

v-update-user-stats

v-update-web-domain-disk

v-update-web-domains-disk

v-update-web-domains-stat

v-update-web-domain-stat

v-update-web-domains-traff

v-update-web-domain-traff

v-update-web-templates
