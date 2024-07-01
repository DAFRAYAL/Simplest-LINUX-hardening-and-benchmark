# Simplest LINUX hardening and benchmark

Will add other unix system groups allocations later. You can always use ITARIAN, SNORT services.

Don't use asterisk in DEBIAN packaging installations. You may try that on RED HAT.

ORACLE LINUX is most recommended. Yet CENTOS Is more compatible with packages.

UBUNTU is the best.

Use PCI-DSS, CIS or DISA policies if you want, but this is pretty much it. 

I think that you can use your user account as exclusive with automatic logon while having its chroot at zero.

If you cannot install UNIX through kind of VENTOY set of UEFI boot loading then do not install it at all since intranet.

Use encrypted containers or encrypted virtual hard drives instead of disk encryptions for any work since internet.
#
#
I am using these permissions listed below.
We grant ourselves with own user account name permission over folders.
#
#
sudo chown exzo:exzo /home/

sudo chmod 755 /home/


sudo chown exzo:exzo /boot/

sudo chmod 755 /boot/


sudo chown exzo:exzo /bin/

sudo chmod 755 /bin/


sudo chown exzo:exzo /dev/

sudo chmod 755 /dev/


sudo chown exzo:exzo /etc/

sudo chmod 755 /etc/


sudo chown exzo:exzo /lib/

sudo chmod 755 /lib/


sudo chown exzo:exzo /lib32/

sudo chmod 755 /lib32/


sudo chown exzo:exzo /lib64/

sudo chmod 755 /lib64/


sudo chown exzo:exzo /libx32/

sudo chmod 755 /libx32/


sudo chown exzo:exzo /opt/

sudo chmod 755 /opt/


sudo chown exzo:exzo /run/

sudo chmod 755 /run/


sudo chown exzo:exzo /sbin/

sudo chmod 755 /sbin/


sudo chown exzo:exzo /snap/

sudo chmod 755 /snap/


sudo chown exzo:exzo /sys/

sudo chmod 755 /sys/


sudo chown exzo:exzo /usr/

sudo chmod 755 /usr/

#
#
Nobody likes this extension?
#
#
sudo chown root:root /usr/share/gnome-shell/extensions/
#
#
sudo chmod 700 /usr/share/gnome-shell/extensions/
#
#
System folders
#
#
sudo chown root:root /dev/cpu/

sudo chmod 700 /dev/cpu/


sudo chown root:root /dev/dma_heap/

sudo chmod 700 /dev/dma_heap/


sudo chown root:root /dev/vfio/

sudo chmod 700 /dev/vfio/


sudo chown root:root /dev/net/

sudo chmod 700 /dev/net/


sudo chown root:root /dev/pts/

sudo chmod 700 /dev/pts/


sudo chown root:root /dev/disk/

sudo chmod 700 /dev/disk/


sudo chown root:root /dev/hugepages/

sudo chmod 700 /dev/hugepages/


sudo chown root:root /sys/kernel/

sudo chmod 700 /sys/kernel/


sudo chown root:root /sys/power/

sudo chmod 700 /sys/power/


sudo chown root:root /dev/devices/

sudo chmod 700 /dev/devices/


sudo chown root:root /lib/kernel/

sudo chmod 700 /lib/kernel/


sudo chown root:root /etc/kernel/

sudo chmod 700 /etc/kernel/


#
#
#Restart for /var/, /proc/, /tmp/, /srv/ to recover themselves from root only access on UBUNTU
#
#
sudo chown root:root /var/

sudo chmod 700 /var/


sudo chown root:root /proc/

sudo chmod 700 /proc/


sudo chown root:root /tmp/

sudo chmod 700 /tmp/


sudo chown root:root /srv/

sudo chmod 700 /srv/

#
#
#Restart for /var/, /proc/, /tmp/, /srv/ to recover themselves from root only access on UBUNTU
#
#

sudo chown root:root /cdrom/

sudo chmod 700 /cdrom/


sudo chown root:root /media/

sudo chmod 700 /media/


sudo chown root:root /mnt/

sudo chmod 700 /mnt/


sudo chown root:root /root/

sudo chmod 700 /root/

