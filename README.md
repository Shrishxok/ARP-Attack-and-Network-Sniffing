# ARP-Attack-and-Network-Sniffing
# Explore Network Sniffing and ARP Attacks

# AIM:

To explore network sniffing and ARP Attacks

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:


### Step 3:
Open terminal and try execute some kali linux commands

## ARP Attacks:  
ARP spoofing: A hacker sends fake ARP packets that link an attacker's MAC address with an IP of a computer already on the LAN. 
Boot kali and Windows7 virtual machines.
In windows 7 give the command arp -a
## OUTPUT:
![1](https://github.com/Shrishxok/ARP-Attack-and-Network-Sniffing/assets/120294863/7a922794-c952-4b43-a849-621329bbe6ac)

From kali linux issue the command : sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
![2](https://github.com/Shrishxok/ARP-Attack-and-Network-Sniffing/assets/120294863/6b2cc62c-68c9-4775-8c49-51e3ba3265c9)

dsniff: In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
![3](https://github.com/Shrishxok/ARP-Attack-and-Network-Sniffing/assets/120294863/5b4eb589-cca7-45f8-9214-86a7092763ad)

In Kali issue the following commands: sudo dsnifff
## OUTPUT:
![4](https://github.com/Shrishxok/ARP-Attack-and-Network-Sniffing/assets/120294863/7fb4a5d1-ead1-4fcd-ab82-55ce187465f7)

Invoke the wireshark and examine the various menus and controls of the tool:
![5](https://github.com/Shrishxok/ARP-Attack-and-Network-Sniffing/assets/120294863/a3d9b54c-8a38-4388-b7ec-dfdbdb7f11a8)

### RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
