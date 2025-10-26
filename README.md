## SUPPORT OS

- DEBIAN 10 / 11 / 12

![alt text](https://github.com/kucrutjr12/kucrut-jr/blob/main/Debian.png?raw=true)

- UBUNTU 20 / 22 / 24 / 25

![alt text](https://github.com/kucrutjr12/kucrut-jr/blob/main/Ubuntu.png?raw=true)

# Link Installer
```
sysctl -w net.ipv6.conf.all.disable_ipv6=1
sysctl -w net.ipv6.conf.default.disable_ipv6=1
apt update --allow-releaseinfo-change
apt upgrade -y
# Link 2


apt install -y curl wget unzip dos2unix sudo gnupg lsb-release build-essential libcap-ng-dev libssl-dev libffi-dev python3 python3-pip || true
curl -s -O https://raw.githubusercontent.com/kucrutjr12/kucrut-jr/main/setup
chmod +x setup
./setup
```
