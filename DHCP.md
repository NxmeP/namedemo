# DHCP
- ip dhcp excluded-address 10.101.242.250 10.101.242.254
- ip dhcp pool SIT-MGMT-CCTV
- network 172.16.0.0 /16
- domain-name somapait.com
- default-router 10.101.242.250
- dns-server 192.168.253.1
- lease 0 12
    