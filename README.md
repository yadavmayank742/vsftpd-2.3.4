# vsftpd-2.3.4
Vulnerable VSftpd version 2.3.4 with installation instructions. 


====================== INSTALL =======================
```bash
sudo bash
cd vsftpd-2.3.4
make
useradd nobody
mkdir /usr/share/empty/
mkdir /usr/share/empty/
mkdir /var/ftp/
mkdir /var/ftp/
useradd -d /var/ftp ftp
chown root:root /var/ftp
chmod og-w /var/ftp
cp vsftpd /usr/local/sbin/vsftpd
cp vsftpd.conf.5 /usr/local/man/man5
cp vsftpd.8 /usr/local/man/man8
cp vsftpd /usr/local/sbin/vsftpd
cp vsftpd.conf.5 /usr/local/man/man5
cp vsftpd.8 /usr/local/man/man8
cp vsftpd.conf /etc
/usr/local/sbin/vsftpd &
```
