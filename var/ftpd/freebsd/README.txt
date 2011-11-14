$ wget ftp://ftp.freebsd.org/pub/FreeBSD/releases/i386/ISO-IMAGES/8.2/FreeBSD-8.2-RELEASE-i386-disc1.iso
$ mkdir /mnt/freebsd
$ mount -o loop FreeBSD-8.2-RELEASE-i386-disc1.iso /mnt/freebsd
$ cp -r /mnt/freebsd/* /var/ftpd/freebsd/
