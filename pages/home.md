# Welcome
As a person aspiring to have a career in cyber security, you will without a doubt come across the term, "Linux". If you are not yet aware of how this applies to the field, have no fear, listed here is a variety of resources that will be useful in learning about Linux and it's various complementary skills.

# Step 1. Installing a Linux Virtual Machine
In order to work in Linux, it is important that you have a machine to work in. One way to accomplish this is to install a virtual machine (VM). In essence, virtual machines are special applications that give you the ability to run a different operating system on top of your existing computers operating system. To do this, you need a hypervisor, which is an application that gives your computer the ability to create virtual machines on your computer (since computers cannot do this on their own). The hypervisor we recommend you use is called Oracle VirtualBox, which is supported on Windows, Mac, and Linux.

The steps provided to install VirtualBox and a Linux Machine are provided below. Recommended for most users interested in cyber security is to create a Kali Linux VM. If the resources required for creating a Kali VM exceed those that may be provisioned from your laptop, you may also attempt to use Ubuntu. Both of the systems are ultimately Linux, but they are different by GUI and default applications, nevertheless, they will provide the basics needed to get started and then some. 
#### Resources
- *For information on installing VirtualBox, [Click Here](https://www.wikihow.com/Install-VirtualBox)*
- *For information on Installing Kali Linux Virtual Machine, [Click Here](https://www.kali.org/docs/virtualization/install-virtualbox-guest-vm/)*
- *For information on installing Ubuntu, [Click Here](https://ubuntu.com/tutorials/how-to-run-ubuntu-desktop-on-a-virtual-machine-using-virtualbox#1-overview)*

# Step 2. Understanding Linux
Part of learning is having great resources to engage with in an organized fashion. One great resource to learn Linux for free is to go through Linux Journey. The website is nicely organized and covers a majority of the topics needed to both get started and excel in learning Linux. Armed with a Linux VM through VirtualBox and the Linux Journey website, a person interested in Linux could learn a lot. Do keep in mind that you should understand how to open a ***terminal*** on your Linux VM. 

#### Opening a Terminal
Opening a terminal will create a window that is relatively void of any information at first. As you learn more about Linux, this otherwise ambiguous box will become your best friend. However, on most "desktop ready" Linux-based operating systems, the terminal isn't something you are just booted into but instead need to learn how to bring up. The following are keyboard shortcuts for both Kali and Ubuntu that can be used to bring up a terminal window.

**Ubuntu / Kali Linux Terminal Shortcut -** *Ctrl+Alt+T*

# Step 3. Diving Into the Linux System Configuration Files
One of the things you will learn about Linux is that it is extremely flexible in it's operation. You can customize and configure just about anything with a Linux operating system. It gives you great power, but with that, comes great responsibility. 

As mentioned Linux can be configured to your liking, but how do you know what to configure? How to configure it? What it is that you are configuring and what it does? Linux has a ton of standards put in place in order to help organize all of the potential chaos that may ensue with the freedom Linux provides. Once you've had some time with Linux by studying with Linux journey, you should take a dive into understanding the underlying systems and configurations governing your system from the time you turn your computer on, to the time you turn it off.

Additionally, it is a good idea to learn about jobs running locally on your system and how to log Linux operations being performed on your system.

#### Resources
- *For information of specific configuration files, [Click Here](https://phoenixnap.com/kb/linux-config-file)*
- *For information on the Boot Process of a Linux System, [Click Here](https://www.golinuxcloud.com/linux-boot-process-explained-step-detail/)*
- *For information on Linux job automation, [Click Here](https://www.howtogeek.com/101288/how-to-schedule-tasks-on-linux-an-introduction-to-crontab-files/)*
- *For information on Linux Logging, [Click Here](https://devconnected.com/linux-logging-complete-guide/)*
# Step 3.5 Diving into Networking
At one point or another, you will come across the need to understand networking eventually. Arguably, most of cyber security deals in networking, so having a fundamental understanding of how computers can communicate over a network is crucial. If you need help learning about networking, please check out NetworkAcademy.io. You may need to create a free account, but the platform has a networking learning pathway for the CCNA certification. You may not need all of the information provided in the CCNA course, however, you should have a firm understanding of the basics of networking, ideally.

Some concepts include but are not limited to: 
- Explain TCP/IP vs OSI
- What is an IPV4 Address?
- What is an IPV6 Address?
- What is Subnetting?
- What is a Subnet Mask?
- What does DNS do?
- What is a VLAN?
- What is SNMP?

# Step 4. Learning About Crucial Applications
Linux, in *most* cases, will provide the underlying subsystem required to run applications that perform functions on a network. This can mean that Linux runs the router handling your networking, or running the web server hosting your website, both of which would require additional applications to handle those functions as they are not supported by default in Linux (or at the very least, not supported without extensive and unnecessary configurations). 

The Following services are non-exhaustive but will be commonly run on Linux, and so understanding how they function and how to configure them is important.
- Secure Shell (SSH)
	- Telnet
	- OpenSSH
- DNS
	- Bind9
	- dnsmasq
- Web Server
	- Apache
	- Nginx
- File Transfer
	- FTPS
	- SFTP
- Remote Logging
	- SYSLOG

#### Resources
- *What is Telnet? [Click Here](https://www.geeksforgeeks.org/introduction-to-telnet/)*
- *What is OpenSSH? [Click Here](https://www.cloudflare.com/learning/access-management/what-is-ssh/)*
	- *How do I SSH? [Click Here](https://www.geeksforgeeks.org/ssh-command-in-linux-with-examples/)*
	- *How do I configure SSH? [Click Here](https://thelinuxcode.com/ssh-config-file/)*
	- *How do I configure SSHD? [Click Here](https://ioflood.com/blog/sshd-configuration-guide-linux-services-explained/)*

- **Questions about DNS?** [Click Here](https://www.cloudflare.com/learning/dns/what-is-dns/)
- *What is Bind9? [Click Here](https://www.cloudns.net/blog/bind-explained-a-powerful-tool-for-dns-management/)*
	- *How do I configure Bind9? [Click Here](https://linuxconfig.org/linux-dns-server-bind-configuration)*
- *What is dnsmasq? [Click Here](https://www.how2shout.com/what-is/dnsmasq.html)*
	- *How do I configure dnsmasq? [Click Here](https://ioflood.com/blog/install-dnsmasq-linux/)*
	
- **Questions about Web Servers?** [Click Here](https://www.techtarget.com/whatis/definition/Web-server)
- *What is Apache? [Click Here](https://kinsta.com/knowledgebase/what-is-apache/)*
	- *How do I configure Apache? [Click Here](https://docs.redhat.com/en/documentation/red_hat_enterprise_linux/8/html/deploying_different_types_of_servers/setting-apache-http-server_deploying-different-types-of-servers#apache-changes-to-rhel7_setting-apache-http-server)*
- *What is Nginx? [Click Here](https://kinsta.com/knowledgebase/what-is-nginx/)*
	- *How do I configure Nginx? [Click Here](https://medium.com/adrixus/beginners-guide-to-nginx-configuration-files-527fcd6d5efd)*

- **Questions About File Transfers (FTP)?** [Click Here](https://kinsta.com/knowledgebase/what-is-ftp/)
- *What is FTPS? [Click Here](https://technicalustad.com/what-is-ftps/)*
	- *How do I configure FTPS? [Click Here](https://www.opensourceforu.com/2015/03/set-up-an-ftps-server-in-linux/)*
- *What is SFTP? [Click Here](https://phoenixnap.com/kb/what-is-sftp)*
	- *How do I configure SFTP? [Click Here](https://linuxhandbook.com/sftp-server-setup/)* 

- *What is SYSLOG? [Click Here](https://www.auvik.com/franklyit/blog/what-is-syslog/)*
	- *How do I configure SYSLOG [Click Here](https://www.freecodecamp.org/news/what-is-syslog-handbook/)*

# Step 5. Locking it Down
So we have learned a lot about Linux, key services, and how to configure services so that they can perform the jobs we like them to do. However, not all applications are created equal, and many need some additional configurations in order to help them do their jobs in a secured way. A few topics to discover when learning about securing your network are the following.
- Local Policies and Administration
- Local Firewalls
	- UFW
	- IPTables
	- Firewalld
- Global Firewalls
	- PFSense
	- Palo Alto
	- Cisco
- Intrusion Detection Systems (IDS)
- Intrusion Prevention Systems (IPS)
- Security Information and Event Management Systems (SIEM)
	- Splunk

#### Resources
- *How do I configure Local Policies and Administer User Accounts? [Click Here](https://www.itprotoday.com/linux-os/linux-user-and-group-management-security-best-practices)*

- *What is a Firewall? [Click Here](https://www.cloudflare.com/learning/security/what-is-a-firewall/)*
	- *What is UFW? [Click Here](https://www.linux.com/training-tutorials/introduction-uncomplicated-firewall-ufw/)*
		- *How do I configure UFW? [Click Here](https://www.digitalocean.com/community/tutorials/ufw-essentials-common-firewall-rules-and-commands)*
	- *What is Firewalld? [Click Here](https://www.redhat.com/sysadmin/beginners-guide-firewalld)*
		- *How do I Configure Firewalld? [Click Here](https://www.computernetworkingnotes.com/linux-tutorials/firewalld-basic-concepts-explained-with-examples.html)*
	- *What is IPTables? [Click Here](https://medium.com/skilluped/what-is-iptables-and-how-to-use-it-781818422e52)*
		- *How do I Configure IPTables? [Click Here](https://phoenixnap.com/kb/iptables-linux)*
	- *What is PFSense? [Click Here](https://www.makeuseof.com/reasons-use-pfsense-firewall/)*
		- *How do I Configure PFSense? [Click Here](https://docs.netgate.com/pfsense/en/latest/config/index.html)*
	
- *What is an Intrusion Detection System (IDS)? [Click Here](https://www.ibm.com/topics/intrusion-detection-system)*

- *What is an Intrusion Prevention System (IPS)? [Click Here](https://www.ibm.com/topics/intrusion-prevention-system)*

- *What is a Security Information and Event Management System (SIEM)? [Click Here](https://www.ibm.com/topics/siem)*
	- *What is Splunk? [Click Here](https://www.splunk.com/en_us/blog/learn/what-splunk-does.html)*
		- *How do I Configure Splunk? [Click Here](https://www.tekstream.com/blog/a-beginners-guide-to-splunk-global-configuration-files/)*



# Step 6. Linux Scripting
When working in Linux environments, sometimes the tools you need to get the job done are not available or are too complex or heavy to justify using. Whenever this is the case, it may feel like you are out of luck. However, if you don't have the tool you need, you can always make it. 

To do this, you have a few options but all require the use of programming. You can program tools in python, or C, or whichever language you prefer for the most part, but generally, it is good to use a language called BASH.

Commonly referred to as BASH scripting, the code you write when making tools are the exact Linux commands you would run in sequence. For example, let's say I wanted to tell the user two things on separate lines and then calculate the sum of two numbers after another so the output looks like this?

```
Hello
World
21
```

I could just run the following:

```
echo -e "Hello\nWorld"
echo $((9+10))
```

However, remembering this series of commands is difficult and so, BASH was created to enable us to compact these commands into files. A BASH script would look something like this (don't worry about what the syntax means for now).

```
#!/bin/bash

echo -e "Hello\nWorld"
echo $((9+10))
```

We can then give this file a name, give it the ability to be executed, and now call the file every time we want to run those commands to form the aforementioned output above. Notice, how all we did was put the commands we wanted to run directly into the BASH file and it would end up running those exact commands. Cool huh? Additionally, the language is interpreted, meaning, the file is executed like a list of instructions going line by line to execute its instruction set. In this way, BASH is executed similarly to that of Python, another interpreted programming language. 

#### Resources
- *Want to learn BASH? [Click Here](https://linuxhandbook.com/bash/)*
