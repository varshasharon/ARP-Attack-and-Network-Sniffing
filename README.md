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
![image](https://github.com/user-attachments/assets/08044125-dfc5-4c23-bc48-6aa9a17d1027)


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:

 dsniff:

![image](https://github.com/user-attachments/assets/a4521a43-5aa9-48a4-a9c1-a199222a2813)


In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
![image](https://github.com/user-attachments/assets/f3ea0076-fc03-41be-ab90-2a1ee5aa112f)



In Kali issue the following commands:
sudo dsnifff


## OUTPUT:
![image](https://github.com/user-attachments/assets/ef419e9c-04eb-4969-a137-41306f8d09d4)

Invoke the wireshark and examine the various menus  and controls of the tool:


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
