# froxlorbsdpatch
Änderungsvorschläge für Froxlor aus FreeBSD

zum Installieren von pure-ftpd:

cd /usr/ports/ftp/pure-ftpd
make config
[x] LARGEFILE
[X] MYSQL
[x] PAM
[x] PRIVSEP
[x] SENDFILE
[x] THROTTLING
[x] TLS
[x] UTF8
[x] virtualchroot

make install clean
