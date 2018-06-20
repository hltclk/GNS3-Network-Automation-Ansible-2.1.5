# Network-Automation-Ansible-2.1.5
Make sure your hosts are in the Network Automation Container's hosts file

Use "nano /etc/hosts" command to add your switches or routers like below

  127.0.1.1       NetworkAutomation-1
  127.0.0.1       localhost
  ::1     localhost ip6-localhost ip6-loopback
  fe00::0 ip6-localnet
  ff00::0 ip6-mcastprefix
  ff02::1 ip6-allnodes
  ff02::2 ip6-allrouters

  192.168.122.71 S1
  192.168.122.72 S2
  192.168.122.73 S3
  192.168.122.74 S4
  192.168.122.75 S5

