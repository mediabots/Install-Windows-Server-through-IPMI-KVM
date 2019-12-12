# [GUIDE] Install Windows Server through IPMI/KVM *(step by step)*
 How to Install Windows Server 2019 using IPMI or KVM

## What is IPMI/KVM?
The Intelligent Platform Management Interface (IPMI) is a set of computer interface specifications for an autonomous computer subsystem that provides management and monitoring capabilities independently of the host system's CPU, firmware (BIOS or UEFI) and operating system. IPMI defines a set of interfaces used by system administrators for out-of-band management of computer systems and monitoring of their operation. For example, IPMI provides a way to manage a computer that may be powered off or otherwise unresponsive by using a network connection to the hardware rather than to an operating system or login shell. Another use case may be installing a custom operating system remotely. Without IPMI, installing a custom operating system may require an administrator to be physically present near the computer, insert a DVD or a USB flash drive containing the OS installer and complete the installation process using a monitor and a keyboard. Using IPMI, an administrator can mount an ISO image, simulate an installer DVD, and perform the installation remotely.

More info: https://en.wikipedia.org/wiki/Intelligent_Platform_Management_Interface

----

## Requirements:

* A dedicated server with IPMI Access enabled

* Google Chrome Browser

* Java must be Installed on your machine

* Good Internet speed

----

## Guide to Install Windows Server 2019 using IPMI/KVM

You machine should have Java installed. Otherwise Download & install JAVA from here: https://www.java.com/en/download/

Through out this Tutorial, I am going to use https://oneprovider.com dedicated server [https://oneprovider.com/dedicated-servers] & Windows Server 2019 Essentials edition (free evaluation copy)

Oneprovider is a world leading company for web servers. And one of the cheapest DEDI/BOX provider in the industry(with 0 setup fee).

Also their support system is very helpful.

Their payment method includes Paypal with many other familiar payment methods.

In maximum cases, their servers comes with IPMI or iDRAC access

After receiving server information from Oneprovider, incase No Operating System is installed on your server, go to "Server manage" page and click on 'Install' tab. Otherise click on "IPMI Session" Tab

From there you can craete an IPMI session for your System IP.

After clicking on "Create Session" button, you should wait for 2 minutes, after that IPMI URL and its credential is visible to you.

Anyway, you are welcome to choose any other Dedicated provider, which could allow you to have an access of IPMI/iDRAC/KVM

<ins>For step-by-step guide, please watch the Youtube Video</ins>

----

## Video Tutorial

<a href="http://www.youtube.com/watch?feature=player_embedded&v=ETxqU1Pex-g" target="_blank"><img src="http://img.youtube.com/vi/ETxqU1Pex-g/0.jpg" 
alt='[Tutorial Video] How to Install Windows Server through IPMI/KVM ' width="480" height="360" border="10" /></a>

----

## Download the OS

you can have your own iso copies from Microsoft Official site here: https://www.microsoft.com/en-us/evalcenter/evaluate-windows-server

OR

Download from my Archive below:

### Widows Server 2019 (evaluation copy/180 days free trial)

https://archive.org/download/WS2019_trial/WS2019.iso

### Widows Server 2016 (evaluation copy/180 days free trial)
https://archive.org/download/windowsserver2016datacenterevaluationcopy/Windows_Server_2016_Datacenter%28EVALUATION-copy%29.ISO

### Widows Server 2012 R2 (evaluation copy/180 days free trial)
https://archive.org/download/WS2012R2/WS2012R2.ISO

### Widows Server 2008 R2 (evaluation copy/180 days free trial)
https://archive.org/download/windowsserver2008r2evaluationcopy/WS2008R2.iso

----

## Download extra dependent server software
https://archive.org/download/extradependentsoftwares/Extra-Dependent-Softwares.iso

----

## Server Speedtest
Tested on 1Gbps France(Paris) Server 
https://www.speedtest.net/result/8843990145

![alt text](https://i.imgur.com/s0gy1oG.png "speedtest of the Windows Server")

----

