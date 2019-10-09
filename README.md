# FreeRADIUS on Alpine

Generic FreeRADIUS on Alpine image, with EAP, LDAP, MySQL, and Kerberos included

A FreeRADIUS configuration directory should be mounted on `/etc/raddb`, and a Kerberos keytab on `/etc/keytab`.

A systemd unit definition is included in `radius.service`.
