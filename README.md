
# Metasploit-for-reconnaissance
# Metasploit
Metasploit for reconnaissance in pentesting

# Name: VIJAY R
# Reg no:212223240178
# AIM:

To get introduced to Metasploit Framework and to  perform reconnaissance  in pentesting .

## DESIGN STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:

Open terminal and try execute some kali linux commands

## EXECUTION STEPS AND ITS OUTPUT:


## OUTPUT:
![image](https://github.com/user-attachments/assets/7250905a-cca1-4e2a-aa8c-8314a11a39ca)

Invoke msfconsole:
## OUTPUT:
![image](https://github.com/user-attachments/assets/d8e7b5c2-53da-4ce9-be79-c22c6c0fedf4)

Type help or a question mark "?" to see the list of all available commands you can use inside msfconsole.
![image](https://github.com/user-attachments/assets/5cf57fe9-593a-4ebb-8410-ab109a426d82)

Port Scanning:
Following command is executed for scanning the systems on our local area network with a TCP scan (-sT) looking for open ports between 1 and 1000 (-p1-1000).
msf >  nmap -sT 192.168.1810/24 -p1-1000
## OUTPUT:
![image](https://github.com/user-attachments/assets/3767bef8-a376-41db-8da1-979fb229ef87)


step4:
use the db-nmap command to scan and save the results into Metasploit's postgresql attached database. In that way, you can use those results in the exploitation stage later.

scan the targets with the command db_nmap as follows.
msf > db_nmap 192.168.181.0/24
## OUTPUT:




## RESULT:
The Metasploit framework for reconnaissance is  examined successfully
