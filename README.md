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


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
![Screenshot 2024-04-21 092827](https://github.com/Hariprasath2023/ARP-Attack-and-Network-Sniffing/assets/145207783/ec9c17e7-b3d9-4714-9daf-1a3167e162b6)


From kali linux issue the command : sudo arpspoof -i eth0 -t

OUTPUT:
![Screenshot 2024-04-21 092834](https://github.com/Hariprasath2023/ARP-Attack-and-Network-Sniffing/assets/145207783/3ce4d16a-0893-4783-af4f-f5b9d97a7ebd)


 dsniff:
In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
![Screenshot 2024-04-21 092840](https://github.com/Hariprasath2023/ARP-Attack-and-Network-Sniffing/assets/145207783/fd80a560-76f4-4301-a5c9-5af6b19a91f7)


In Kali issue the following commands:
sudo dsnifff
## OUTPUT:

![Screenshot 2024-04-21 092854](https://github.com/Hariprasath2023/ARP-Attack-and-Network-Sniffing/assets/145207783/a6a07e23-ec8b-4b57-acb9-109a45cbf548)



## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
