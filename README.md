# Script LOBSTER (V1-WSS)
 Welcome Dear๐๐

<h2 align="center">AutoScript VPN By LOBSTER <img src="https://img.shields.io/badge/Version-1.0-blue.svg"></h2>


<h2 align="center"> Supported Linux Distribution</h2>
<p align="center"><img src="https://d33wubrfki0l68.cloudfront.net/5911c43be3b1da526ed609e9c55783d9d0f6b066/9858b/assets/img/debian-ubuntu-hover.png"></p>
<p align="center"><img src="https://img.shields.io/static/v1?style=for-the-badge&logo=debian&label=Debian%2010&message=Buster&color=blue"> <img src="https://img.shields.io/static/v1?style=for-the-badge&logo=debian&label=Debian%2011&message=Bullseye&color=blue"> <img src="https://img.shields.io/static/v1?style=for-the-badge&logo=ubuntu&label=Ubuntu%2018&message=18.04 LTS&color=blue"> <img src="https://img.shields.io/static/v1?style=for-the-badge&logo=ubuntu&label=Ubuntu%2020&message=20.04 LTS&color=blue"></p>

<p align="center"><img src="https://img.shields.io/badge/Service-OpenSSH-success.svg"> <img src="https://img.shields.io/badge/Service-Dropbear-success.svg">  <img src="https://img.shields.io/badge/Service-Websocket-success.svg"> <img src="https://img.shields.io/badge/Service-BadVPN-success.svg">  <img src="https://img.shields.io/badge/Service-Stunnel-success.svg">  <img src="https://img.shields.io/badge/Service-OpenVPN-success.svg">  <img src="https://img.shields.io/badge/Service-Squid3-success.svg">  <img   src="https://img.shields.io/badge/Service-Webmin-success.svg">  <img src="https://img.shields.io/badge/Service-OHP-success.svg">  <img
src="https://img.shields.io/badge/Service-Xray-success.svg">  <img src= "https://img.shields.io/badge/Service-SSR-success.svg">  <img src="https://img.shields.io/badge/Service-Trojan Go-success.svg"> <img src="https://img.shields.io/badge/Service-Trojan-success.svg"> <img src="https://img.shields.io/badge/Service-WireGuard-success.svg"> <img src="https://img.shields.io/badge/Service-Shadowsocks-success.svg">


## Commands : <img src="https://img.shields.io/static/v1?style=for-the-badge&logo=powershell&label=Shell&message=Bash%20Script&color=lightgray">

## Update & Upgrade First Your VPS for Debian 10 & 11

  ```html
  apt-get update && apt-get upgrade -y && update-grub &&  apt install figlet -y && apt install lolcat -y && gem install lolcat && sleep 2 && reboot

  ```

## Update & Upgrade First Your VPS for Ubuntu 18.04 & 20.04

  ```html
  apt-get update && apt-get upgrade -y && apt dist-upgrade -y && update-grub  && apt install figlet -y && apt install lolcat -y && gem install lolcat && sleep 2 && reboot

  ```
 
## INSTALLATION SCRIPT๐

  ```html
  sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update && apt install -y bzip2 gzip coreutils screen curl && wget https://raw.githubusercontent.com/aggvpn/ws/main/setup.sh && chmod +x setup.sh && sed -i -e 's/\r$//' setup.sh && screen -S setup ./setup.sh

  ```
 
 ## Copy & paste ๐๐ to your VPS if ERROR (WG ONLY)
 ## Wireguard

  ```html
  echo "deb http://deb.debian.org/debian/ unstable main" >/etc/apt/sources.list.d/unstable.list
printf 'Package: *\nPin: release a=unstable\nPin-Priority: 90\n' >/etc/apt/preferences.d/limit-unstable
apt update
apt install -y wireguard-tools iptables iptables-persistent
apt install -y linux-headers-$(uname -r)
 
  ```
 
   ```html
systemctl restart wg-quick@wg0

  ```
  ## โ๏ธ INSTALL SCRIPT WSBUG TELCO MYโ๏ธ
```
wget -q -O /usr/bin/bug "https://raw.githubusercontent.com/aggvpn/allow/main/vbug.sh" && chmod +x /usr/bin/bug && apt install make && apt install gcc && apt install shc
```
  ## โ๏ธ UPDATE SCRIPT WSBUG TELCO MY โ๏ธ
  ```
  rm -f /usr/bin/bug && wget -q -O /usr/bin/bug "https://raw.githubusercontent.com/aggvpn/allow/main/vbug.sh" && chmod +x /usr/bin/bug && apt install make && apt install gcc && apt install shc
  ```

## Info :

 ## Script for Sell Only. Contact owner on Telegram @Lobsterintel <a href="https://t.me/Lobsterintel" target=โ_blankโ><img src="https://img.shields.io/static/v1?style=for-the-badge&logo=Telegram&label=Telegram&message=Click%20Here&color=blue"></a>

 ## For Buy Script : Contact Telegram @Lobsterintel <a href="https://t.me/Lobsterintel" target=โ_blankโ><img src="https://img.shields.io/static/v1?style=for-the-badge&logo=Telegram&label=Telegram&message=Click%20Here&color=blue"></a>

 ## Main Menu





  ## Status Running
 


  ## Service & Port
 


## Description :

  Service & Port

  โ- OpenSSH                 : 22
  โ- OpenVPN                 : TCP 1194, UDP 2200, SSL 110
  โ- Stunnel4                : 222, 777
  โ- Dropbear                : 442, 109
  โ- OHP Dropbear            : 8585
  โ- OHP SSH                 : 8686
  โ- OHP OpenVPN             : 8787
  โ- Websocket SSH(HTTP)     : 2081
  โ- Websocket SSL(HTTPS)    : 222
  โ- Websocket OpenVPN       : 2084
  โ- Squid Proxy             : 3128, 8080, 8000
  โ- Badvpn                  : 7100, 7200, 7300
  โ- Nginx                   : 81
  โ- Wireguard               : 5820
  โ- Shadowsocks-R           : 1443-1543
  โ- SS-OBFS TLS             : 2443-2543
  โ- SS-OBFS HTTP            : 3443-3543
  โ- XRAY Vmess Ws Tls       : 443
  โ- XRAY Vless Ws Tls       : 443
  โ- XRAY Vless Tcp Xtls     : 443
  โ- XRAY Trojan Tcp Tls     : 443
  โ- XRAY Vmess Ws None Tls  : 80
  โ- XRAY Vless Ws None Tls  : 8080
  โ- Trojan Go               : 2083

 >>> Server Information & Other Features
   โ- Timezone                 : Asia/Kuala_Lumpur (GMT +8)๐ฒ๐พ
   โ- Fail2Ban                 : [ON]
   โ- DDOS Dflate              : [ON]
   โ- IPtables                 : [ON]
   โ- Auto-Reboot              : [ON]- 5.00AM
   โ- IPv6                     : [OFF]
   โ- Auto-Remove-Expired      : [ON]
   โ- Auto Delete Expired Account
   โ- Fully automatic script
   โ- VPS settings
   โ- Admin Control
   โ- Change port
   โ- Full Orders For Various Services

โโโโโโโโโโโโโโโโโโโโโโโโโโโโโโโ

## Telegram

[LOBSTER-INTEL](https://t.me/Lobsterintel)

[Group freemium VPN MY](https://t.me/FVPNMY)

[Channel VPN-TELCO](https://t.me/vpntelco2022)

[Channel VPN-FREEMIUM](https://t.me/FilevpnFree)

## Credit :

*   LOBSTER-INTEL

*   Project INTEL

*   V2ray

<p align="center">
  <a><img src="https://img.shields.io/badge/Copyright%20ยฉ-Lobster%20AutoScriptVPN%202022.%20All%20rights%20reserved...-blueviolet.svg" style="max-width:200%;">
    </p>
   </p>
