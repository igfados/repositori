termux install xfce debian proot

```bash
pkg update
pkg install x11-repo
pkg install termux-x11-nightly
pkg install proot-distro
proot-distro install debian
```

```
proot-distro login debian
apt update -y
apt install nano adduser
apt install sudo
```
```
adduser root
nano /etc/sudoers
su ~ root
whoami
sudo whoami
```

```bash
sudo apt install xfce4 -y
```

```
wget https://raw.githubusercontent.com/LinuxDroidMaster/Termux-Desktops/main/scripts/proot_debian/startxfce4_debian.sh
chmod +x startxfce4_debian.sh
./startxfce4_debian.sh
```
