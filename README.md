# network-config
 ## Set a Static IP Address
 ![network-1](network-1.PNG)
 
 ## used sudo systemctl restart systemd-networkd instead of sudo systemctl restart networking
 ![network-active](network-active.PNG)
 ![network-2](network-2.PNG)

 ## ping google.com
 ![network-3](network-3.PNG)

 ## capture network traffic on the eth0 interface 
 sudo tcpdump -i enX0 -w capture.pcap
 ![display](display.PNG)

 ## Analyze the captured traffic 
 ![capturing-r-traffic](capturing-r-traffic.PNG)

 ## Set Up a Firewal
sudo ufw allow ssh
sudo ufw allow http
sudo ufw enable
![setup](setup.PNG)
![firewall](firewall.PNG)

## Troubleshoot DNS
dig google.com
![troubleshoot](troubleshoot.PNG)
