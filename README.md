# ansible-mailserver-buster

ansible roles for a mail server on debian buster

The location of this repo is: https://gitea.multiname.org/ibu/ansible-mailserver-buster

## mail_system

ansible role for debian buster setting up a mailserver with
postfix, rspamd, dovecot and clamav and based on PostgreSQL

Attention: user and domain administration (in PostgreSQL) is not covered here

* mail_system
* mail_system.yml


## journal-postfix

ansible role for debian buster parsing postfix entries in
systemd journal and collecting delivery information

* journal-postfix
* journal-postfix.yml
* journal-postfix-doc

See [journal-postfix/files/srv/README.md](journal-postfix/files/srv/README.md)

