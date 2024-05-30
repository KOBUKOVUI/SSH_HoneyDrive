# SSH_HoneyDrive :honeybee:
How to use Kippo SSH honeypot to analyze a brute-fore attack.
## Description :page_with_curl:
This project help you have an overview how a honeypot works. We will use HoneyDrive 
which is a honeypot Linux Distro. It's a virtual appliance (OVA) with Xubuntu Desktop
installed. It has 10 pre-installed honeypot software packages. But in this project 
we will focus on using Kippo SSH honeypot to lure hackers and capture their signatures.

In this project, we will use Kali Linux as an Attacker :crossed_swords: and HoneyDrive 
as a victim :shield:. In Kali Linux, **_Nmap_** and **_Medusa_**(a brute-force tool) will 
be used.

## What are honeypots? :honey_pot:
Honeypots are designed as real parts of a network infrastructure such as 
a server or an end-host. But honeypots are modified to look like atractive targets for luring the hackers. Honeypots are used by the security teams to monitors the system's security resposes and redirect 
the attacker away from the real assets. 

## How do Honeypots work? :open_file_folder:
Honeypots are often designed to have vulnerabilites which often are decoy data. When the attackers break in
to the honeypots, the security team can observe how the hackers launched the attacks and take note their 
technique or signature. All these informations can be used to strengthen the security of real systems.  

## Installation :gear:

### 1, Install HoneyDrive: 
**Step 1**: Download the OVA file from [bruteforce.gr](https://sourceforge.net/projects/honeydrive/) 

**Step 2**: Use virtual machine application such as VMware or Virtual Box to create a new machine.

**Step 3**: Turn on the HoneyDrive.
![HoneyDriveDesktop](Pic/HoneyDriveDesktop.png)

**Step 4**: Start __kippo_ssh__. 
Open termianl end the command below: 
```
/honeydrive/kippo/start.sh
```
Wait for a moment and the kippo will be activated. :hourglass:
![KippoStart](Pic/StartKippo.png) 





