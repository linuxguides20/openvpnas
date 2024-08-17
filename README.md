# How to installing OpenVPN Access Server (OpenVPN-AS) version 2.14 on Ubuntu 22.04 with unlimit connections

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
