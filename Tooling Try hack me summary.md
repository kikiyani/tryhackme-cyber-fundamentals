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

***HYDRA***
In this room i learnt about hydra, which is an open source tool where you can do bruteforce attack since manually doing this could take you forever. This room had alot to learn. I learnt how to use hydra tool on different services, the practical task was ssh and web. I was given the username MOLLY and though the txt password file and using the commands i got the two flags. For the web form in hydra we also added the login path to be used and message if credentials are incorrect, which we got to know my trying a combination and using the web developers tools. For the ssh basic command was used of the ssh hydra. 


<img width="500" height="300" alt="image" src="https://github.com/user-attachments/assets/267eb4dc-7b23-4c42-9802-f2d5e12be292" />

<img width="500" height="300" alt="image" src="https://github.com/user-attachments/assets/18cd8b95-5ad2-4574-a9da-82a1afea6f6e" /> 

<img width="500" height="300" alt="image" src="https://github.com/user-attachments/assets/22f780f3-d756-4663-8489-772813ae48df" />



***LINUX PRIV ESCALATION***
This room is a walkthrough of different linux priviledge escalation techniques you can use. I was provided with a vulnerable VM and had to exploit the vulnerabilities in it. Starting with weak file permissions: readable and writeable /etc/shadow and /etc/passwd files. I also came across and learnt about sudo and cron jobs. Among which cron jobs, was entirely a new concept for me. I also played around with SUID/SGID, files that had the S bit and how they can be exploited. Then, comes my favourite one, password and keys. In which, we exploited vulnerabilities related to passwords in command, or config files, or keys hidden in root. lastly, also dealt with NFS, in which concept or root squashing was explored.   




<img width="800" height="300" alt="image" src="https://github.com/user-attachments/assets/be465f7e-762e-41f2-8259-bbf545af075c" />


