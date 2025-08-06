***Nmap Live Host Discovery***
This room was a detailed explanation on how NMAP (network mapper) finds online systems/hosts on a network before starting the port scanning, since doing the port scanning on offline system is time wastage. To discover live hosts nmap can take these approaches:
ARP scan, ICMP scan, TCP/ UDP
TASK 1: i was given two subnets joined through 1 router and was asked to broadcast an ARP requestion of finding the computer 6. I learnt alot about subnetting here and how ARP requests are managed in subnetting.
TASK 2: It was enumerating targets using nmap, how we can tell nmap to scan what targets. Using the attack machine, i explored few nmap commands and answered the task questions.
TASK 3: I tackled with ARP request and respons ealong with ICMP ping packets between two subnets. 
TASK 4: nmap host discovery using ARP, this was an interesting room since i learnt further about ARP scanning using nmap and arp-scan both. and how ARP queries work.
TASK 5: this task was about nmap host discovery using ICMP. i came across three different ways we can check for live hosts on a network. ICMP echo packets, ICMP timestamps, ICMP address mask. its better to use all three to get proper results as ICMP ping packets are often blocked by the firewalls by default.
TASK 6: This task for alot to learn from. We strted with TCP SYN PING which is 3 way handshake AND TCP ACK PING which requires root user. We also git to learn about UDP ping which kind of goes opposite of TCP ping and masscan. 
<img width="500" height="300" alt="image" src="https://github.com/user-attachments/assets/d8e86f23-e880-49e2-80ea-1bae41408323" />
