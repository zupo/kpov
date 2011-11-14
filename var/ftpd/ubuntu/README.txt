$ wget http://mirror.lihnidos.org/ubuntu/ubuntu-releases//lucid/ubuntu-10.04.3-desktop-i386.iso
$ mkdir /mnt/ubuntu
$ mount -o loop ubuntu-10.04.3-desktop-i386.iso /mnt/ubuntu
$ cp -r /mnt/ubuntu/* /var/ftpd/ubuntu/
$ cp -r /mnt/ubuntu/.* /var/ftpd/ubuntu/
