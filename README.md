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
<img width="890" height="768" alt="arp" src="https://github.com/user-attachments/assets/153d9828-edf5-4a5d-930b-57d443aaeac0" />



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

<img width="489" height="92" alt="Screenshot 2025-09-24 203041" src="https://github.com/user-attachments/assets/eb935178-8c00-4cda-91dd-01c3cb10bc15" />

<img width="959" height="836" alt="dnsiff" src="https://github.com/user-attachments/assets/06ca0e93-20f0-45c1-950e-51b33acde820" />




Invoke the wireshark and examine the various menus  and controls of the tool:

<img width="961" height="914" alt="wrieshark" src="https://github.com/user-attachments/assets/4159a8a1-97f3-445e-b24e-4254cbc4d4fb" />



## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
