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

<img width="721" height="253" alt="ftp" src="https://github.com/user-attachments/assets/bbcb273d-87b1-4e85-8e63-e00c9ebe883b" />


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:

<img width="947" height="640" alt="Screenshot 2025-09-24 194253" src="https://github.com/user-attachments/assets/54752174-4d8e-46f5-ad9e-d84a84fdc4c5" />


 dsniff:
In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:


<img width="721" height="253" alt="ftp" src="https://github.com/user-attachments/assets/2732f17c-52d2-45f8-b997-42e0c05daad9" />


In Kali issue the following commands:
sudo dsnifff
## OUTPUT:

![Uploading dnsiff.png…]()



Invoke the wireshark and examine the various menus  and controls of the tool:




## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
