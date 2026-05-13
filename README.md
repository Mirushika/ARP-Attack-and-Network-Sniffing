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

<img width="1036" height="696" alt="Screenshot 2026-05-13 113803" src="https://github.com/user-attachments/assets/a8007389-bb69-4b8b-b470-a8ff0a25b9a9" />


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:


<img width="1291" height="521" alt="VirtualBox_kali_ ex 4 -1" src="https://github.com/user-attachments/assets/aa1ae70d-d59b-47af-9e79-70861cf1e6e8" />


 dsniff:


<img width="1009" height="367" alt="VirtualBox_kali_ ex 4" src="https://github.com/user-attachments/assets/8a12c6d4-b233-4ad3-a9a1-7d0343b453ce" />




In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:

<img width="1045" height="184" alt="VirtualBox_kali_sniff" src="https://github.com/user-attachments/assets/1eb41954-5433-4f0c-8f28-8810ccf685c6" />



In Kali issue the following commands:
sudo dsnifff
## OUTPUT:


<img width="1920" height="944" alt="VirtualBox_kali_Host list 1" src="https://github.com/user-attachments/assets/b7caf2ed-9178-40d4-9241-f879a3301b52" />


<img width="1920" height="944" alt="VirtualBox_kali_ arp poision" src="https://github.com/user-attachments/assets/2e5c4e0e-4340-4cbe-b997-1d74dbbda44a" />


Invoke the wireshark and examine the various menus  and controls of the tool:


<img width="1920" height="944" alt="VirtualBox_kali_ duplicate" src="https://github.com/user-attachments/assets/58f46a1f-c6ae-404f-a175-acd760b6069d" />

## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
