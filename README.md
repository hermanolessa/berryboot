# berryboot

cat /etc/apt/sources.list
deb http://http.kali.org/kali kali-rolling main non-free contrib

apt update && apt -y full-upgrade

root@kali:~# grep VERSION /etc/os-release
VERSION="2019.2"
VERSION_ID="2019.2"

root@kali:~# uname -a
Linux kali 4.19.0-kali4-amd64 #1 SMP Debian 4.19.28-2kali1 (2019-03-18) x86_64 GNU/Linux
