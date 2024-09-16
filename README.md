# Simplest LINUX hardening and benchmark

You can always use ITARIAN, AZURE ARC services.

Don't use asterisk in DEBIAN packaging installations. You may try that on RED HAT.

ORACLE LINUX is most recommended. Yet CENTOS Is more compatible with packages.`

UBUNTU is the best. With PLASMA desktop environment, because it does not need GNOME shell or GDM, XORG, but it is best to keep default to be generic for overall system configuration firmly, firmly except for being generic.

"It's coming from within hardware - no, it's coming from within operating systems".

Use PCI-DSS, CIS or DISA policies if you want, but this is pretty much it. 

If you cannot install UNIX through kind of VENTOY set of UEFI boot loading then do not install it at all since intranet.

Use encrypted containers or encrypted virtual hard drives instead of disk encryptions for any work since internet. 

There's no application to encrypt existing folders currently 2024.

Install OPENSNITCH, FIREJAIL, RKHUNTER, CLAMAV, PRELOAD, SURICATA, SNORT on default over UFW.

Ask BING AI or CHAT GPT to configure FIREJAIL and RKHUNTER as service.

For SURICATA and SNORT the configuration files must have the right device, interface, adapter name like wlp2s1, wlo1, eth0 and the home network range must be correct.

Do not install FIREWALLD.

Create another user and just sudo chown that user whole system file permission from recovery console except /root/ folder which should be over allocated with root permissions.

It is chown user:user **/**/**/**/**/** or chown user:user **/**/**/**/**/** going forward and keep going back until chown user:user / on the length without chmod command.

This user has chroot and cpu in limits.conf /etc/security at 0. Thus your main user that you will use can be exclusive.

You get error like WARNING: cannot start document portal: Can't mount path /run/user/1000/doc. Fix it yourself for applications coming with DEBIAN.

All after /etc/sudoers is that user except that /etc/sudoers folder. /etc/sudoers.d is that user and /etc/sudoers/README is that user and if you have ZFS then /etc/sudoers.d/zfs is that user from recovery console and finally for logged on user /usr/bin/sudo is root and it needs the chmod which is chmod 4755 /usr/bin/sudo.

So. You will have to enable services over and over again of applications.

Or.
..
..
...

Finally delete sudo service file format alter connection pre-emptive looper and all services in etc/systemd/system must be rooted.

Mostly this is an overhead BIOS.

Meaning that when you enter any operating system, lower chances to go online with this security.

That sudo service can appear and disappear depending on firewall.

By then unless more software happens it was done.

"Android sorcerers and deny more air is not".

From the operating system start directory execute these commands. Best to use recovery console without sudo.

sudo systemd-run --scope -p MemoryLimit=1000M -p CPUQuota=100% ionice -c3 -n7 /*/

sudo ionice -c3 -p $$

sudo ionice -c3 -p *

sudo ionice -c3 -p /*/*

sudo ionice -c3 -p */*

ulimit -f 100000 /*/*/*/*/*/*/*/*
#
#
sudo chown root:root /usr/bin/lwp-request/*

sudo chmod 0 /usr/bin/lwp-request/*

sudo chown root:root /usr/sbin/*cupsd*

sudo chmod 0 /usr/sbin/*cupsd*

sudo chown root:root
#
#
sudo apt install *-*gnome*

sudo apt update

sudo apt upgrade

#reboot

sudo apt install *gnome*-*

#reboot

sudo ubuntu-drivers install

#reboot

#All, after, things will be blue with.

No, virtualization.

No, ramdisk.

No, security feature from BIOS like TPM, etc...

Yes, secure boot.

These permissions listed below are old.
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
