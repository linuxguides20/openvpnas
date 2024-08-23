# How to installing OpenVPN-AS version 2.14 on Ubuntu 22.04 with unlimit connections
![image](https://github.com/user-attachments/assets/eaa99a5f-4eff-4790-9435-148239dacbe7)

OpenVPN Access Server (OpenVPN-AS) is a commercial product offering easy setup, a web interface, and professional support, ideal for businesses. OpenVPN Server, the open-source version, is more flexible and customizable but requires technical expertise, making it better suited for users seeking a free, hands-on solution.

![image](https://github.com/user-attachments/assets/1275e0cb-49b5-4320-a96b-c5312ec1fedf)
You might think about buying a subscription from OpenVPN for your business, but **no, no, no**—it costs way too much money.
We offer you a very affordable option with a subscription that has no limits and 24/7 support.
## Install Openvpn AS first
With OpenVPN-AS, the licensing fees can be relatively expensive for businesses per connection.
Here is how to install OpenVPN Access Server version 2.14 on Ubuntu 22.04
- Before starting, make sure your system is up to date:
```
sudo apt update
sudo apt upgrade -y
```
- Run this script on your Ubuntu Server, this script also available for Ubuntu, Debian, Redhat
```
bash <(curl -fsS https://as-repository.openvpn.net/as/install.sh)
```
![image](https://github.com/user-attachments/assets/10c005af-9d09-4b05-bb31-9ef667993f47)

Login to this credential after openvpnas install complete

![image](https://github.com/user-attachments/assets/e30fcee7-c46a-4d3c-8e61-9943f6b93daf)

With free license only 2 connection per time

![image](https://github.com/user-attachments/assets/fa8a1034-3e6e-4ebe-b189-7be5c2d339fe)

Now stop openvpnas service
```
root@vpnas183:~# systemctl stop openvpnas.service
```
Go to /usr/local/openvpn_as/lib/python/ directory
```
root@vpnas183:~# cd /usr/local/openvpn_as/lib/python/
```
Rename of file pyovpn-2.0-py3.10.egg
```
root@vpnas183:/usr/local/openvpn_as/lib/python# mv pyovpn-2.0-py3.10.egg pyovpn-2.0-py3.10.egg_bak
```
Download my file in same directory
```
root@vpnas183:/usr/local/openvpn_as/lib/python# wget https://github.com/linuxguides20/openvpnas/blob/f0419cfcc16b710768bc599ebbcd08fad4fb7244/pyovpn-2.0-py3.10.egg
```
Restart openvpnas service
![image](https://github.com/user-attachments/assets/64f916a0-e67d-4da4-aff7-0c4f66a40892)
## Upgrade license
I offer a free file with 4 connections. If your business needs more than 4 connections, contact me on Telegram for options like 10, 100, 500, or unlimited connections. Telegram: https://telegram.me/ttptt25

This is a demo of the number of connections available. There is no insert script, no ransomware—my company has over ten thousand people, and we've been using this for over ten years without any problems.

![image](https://github.com/user-attachments/assets/536d1ce7-eec1-430c-a9bf-ede02f048afd)
![image](https://github.com/user-attachments/assets/3f871e21-0b55-4022-b071-cd57246de9bd)
![image](https://github.com/user-attachments/assets/73cbec72-0f7e-40de-99ae-a880f2353e60)


