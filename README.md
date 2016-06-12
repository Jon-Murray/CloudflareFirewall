
@echo off
REM remember to disable the default rules allowing anyone access from 80/443
REM list taken from https://www.cloudflare.com/ips-v4 and https://www.cloudflare.com/ips-v6

netsh advfirewall firewall add rule name="Allow HTTP from cloudflare" dir=in action=allow protocol=tcp localport=80 remoteip=103.21.244.0/22
netsh advfirewall firewall add rule name="Allow HTTPS from cloudflare" dir=in action=allow protocol=tcp localport=443 remoteip=103.21.244.0/22

netsh advfirewall firewall add rule name="Allow HTTP from cloudflare" dir=in action=allow protocol=tcp localport=80 remoteip=103.22.200.0/22
netsh advfirewall firewall add rule name="Allow HTTPS from cloudflare" dir=in action=allow protocol=tcp localport=443 remoteip=103.22.200.0/22

netsh advfirewall firewall add rule name="Allow HTTP from cloudflare" dir=in action=allow protocol=tcp localport=80 remoteip=103.31.4.0/22
netsh advfirewall firewall add rule name="Allow HTTPS from cloudflare" dir=in action=allow protocol=tcp localport=443 remoteip=103.31.4.0/22

netsh advfirewall firewall add rule name="Allow HTTP from cloudflare" dir=in action=allow protocol=tcp localport=80 remoteip=104.16.0.0/12
netsh advfirewall firewall add rule name="Allow HTTPS from cloudflare" dir=in action=allow protocol=tcp localport=443 remoteip=104.16.0.0/12

netsh advfirewall firewall add rule name="Allow HTTP from cloudflare" dir=in action=allow protocol=tcp localport=80 remoteip=108.162.192.0/18
netsh advfirewall firewall add rule name="Allow HTTPS from cloudflare" dir=in action=allow protocol=tcp localport=443 remoteip=108.162.192.0/18

netsh advfirewall firewall add rule name="Allow HTTP from cloudflare" dir=in action=allow protocol=tcp localport=80 remoteip=131.0.72.0/22
netsh advfirewall firewall add rule name="Allow HTTPS from cloudflare" dir=in action=allow protocol=tcp localport=443 remoteip=131.0.72.0/22

netsh advfirewall firewall add rule name="Allow HTTP from cloudflare" dir=in action=allow protocol=tcp localport=80 remoteip=141.101.64.0/18
netsh advfirewall firewall add rule name="Allow HTTPS from cloudflare" dir=in action=allow protocol=tcp localport=443 remoteip=141.101.64.0/18

netsh advfirewall firewall add rule name="Allow HTTP from cloudflare" dir=in action=allow protocol=tcp localport=80 remoteip=162.158.0.0/15
netsh advfirewall firewall add rule name="Allow HTTPS from cloudflare" dir=in action=allow protocol=tcp localport=443 remoteip=162.158.0.0/15

netsh advfirewall firewall add rule name="Allow HTTP from cloudflare" dir=in action=allow protocol=tcp localport=80 remoteip=172.64.0.0/13
netsh advfirewall firewall add rule name="Allow HTTPS from cloudflare" dir=in action=allow protocol=tcp localport=443 remoteip=172.64.0.0/13

netsh advfirewall firewall add rule name="Allow HTTP from cloudflare" dir=in action=allow protocol=tcp localport=80 remoteip=173.245.48.0/20
netsh advfirewall firewall add rule name="Allow HTTPS from cloudflare" dir=in action=allow protocol=tcp localport=443 remoteip=173.245.48.0/20

netsh advfirewall firewall add rule name="Allow HTTP from cloudflare" dir=in action=allow protocol=tcp localport=80 remoteip=188.114.96.0/20
netsh advfirewall firewall add rule name="Allow HTTPS from cloudflare" dir=in action=allow protocol=tcp localport=443 remoteip=188.114.96.0/20

netsh advfirewall firewall add rule name="Allow HTTP from cloudflare" dir=in action=allow protocol=tcp localport=80 remoteip=190.93.240.0/20
netsh advfirewall firewall add rule name="Allow HTTPS from cloudflare" dir=in action=allow protocol=tcp localport=443 remoteip=190.93.240.0/20

netsh advfirewall firewall add rule name="Allow HTTP from cloudflare" dir=in action=allow protocol=tcp localport=80 remoteip=197.234.240.0/22
netsh advfirewall firewall add rule name="Allow HTTPS from cloudflare" dir=in action=allow protocol=tcp localport=443 remoteip=197.234.240.0/22

netsh advfirewall firewall add rule name="Allow HTTP from cloudflare" dir=in action=allow protocol=tcp localport=80 remoteip=198.41.128.0/17
netsh advfirewall firewall add rule name="Allow HTTPS from cloudflare" dir=in action=allow protocol=tcp localport=443 remoteip=198.41.128.0/17

netsh advfirewall firewall add rule name="Allow HTTP from cloudflare" dir=in action=allow protocol=tcp localport=80 remoteip=199.27.128.0/21
netsh advfirewall firewall add rule name="Allow HTTPS from cloudflare" dir=in action=allow protocol=tcp localport=443 remoteip=199.27.128.0/21

netsh advfirewall firewall add rule name="Allow HTTP from cloudflare" dir=in action=allow protocol=tcp localport=80 remoteip=2400:cb00::/32
netsh advfirewall firewall add rule name="Allow HTTPS from cloudflare" dir=in action=allow protocol=tcp localport=443 remoteip=2400:cb00::/32

netsh advfirewall firewall add rule name="Allow HTTP from cloudflare" dir=in action=allow protocol=tcp localport=80 remoteip=2405:8100::/32
netsh advfirewall firewall add rule name="Allow HTTPS from cloudflare" dir=in action=allow protocol=tcp localport=443 remoteip=2405:8100::/32

netsh advfirewall firewall add rule name="Allow HTTP from cloudflare" dir=in action=allow protocol=tcp localport=80 remoteip=2405:b500::/32
netsh advfirewall firewall add rule name="Allow HTTPS from cloudflare" dir=in action=allow protocol=tcp localport=443 remoteip=2405:b500::/32

netsh advfirewall firewall add rule name="Allow HTTP from cloudflare" dir=in action=allow protocol=tcp localport=80 remoteip=2606:4700::/32
netsh advfirewall firewall add rule name="Allow HTTPS from cloudflare" dir=in action=allow protocol=tcp localport=443 remoteip=2606:4700::/32

netsh advfirewall firewall add rule name="Allow HTTP from cloudflare" dir=in action=allow protocol=tcp localport=80 remoteip=2803:f800::/32
netsh advfirewall firewall add rule name="Allow HTTPS from cloudflare" dir=in action=allow protocol=tcp localport=443 remoteip=2803:f800::/32








