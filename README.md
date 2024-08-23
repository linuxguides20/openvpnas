# How to installing OpenVPN-AS version 2.14 on Ubuntu 22.04 with unlimit connections

OpenVPN Access Server (OpenVPN-AS) is a commercial product offering easy setup, a web interface, and professional support, ideal for businesses. OpenVPN Server, the open-source version, is more flexible and customizable but requires technical expertise, making it better suited for users seeking a free, hands-on solution.

![image](https://github.com/user-attachments/assets/72a1e15a-4e73-4913-b995-233d7cdd9ef9)

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
Download my file
