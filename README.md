# Enumeration
Enumeration Techniques

# Explore Google hacking and enumeration 

# AIM:

To use Google for gathering information and perform enumeration of targets

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various Google hacking keywords and enumeration tools as follows:


### Step 3:
Open terminal and try execute some kali linux commands

## Pen Test Tools Categories:  

Following Categories of pen test tools are identified:
Information Gathering.

### Google Hacking:

Google hacking, also known as Google dorking, is a technique that involves using advanced operators to perform targeted searches on Google. These operators can be used to search for specific types of information, such as sensitive data that may have been inadvertently exposed on the web. Here are some advanced operators that can be used for Google hacking:

### site:
This operator allows you to search for pages that are within a specific website or domain. For example, "site:example.com" would search for pages that are on the example.com domain.
Following searches for all the sites that is in the domain yahoo.com

![image](https://github.com/Vanitha-SM/Enumeration/assets/119557985/63dc4188-e890-4aaf-83f0-189054dbb22c)


### filetype:
This operator allows you to search for files of a specific type. For example, "filetype:pdf" would search for all PDF files.
Following searches for pdf file in the domain yahoo.com

![image](https://github.com/Vanitha-SM/Enumeration/assets/119557985/1b3f4a33-ff59-4cdf-bad1-0faeb174ff5e)


### intext: 
This operator allows you to search for pages that contain specific text within the body of the page. For example, "intext:password" would search for pages that contain the word "password" within the body of the page.

![image](https://github.com/Vanitha-SM/Enumeration/assets/119557985/c7ce576f-ec52-4b91-a023-e9574249933a)


### inurl: 
This operator allows you to search for pages that contain specific text within the URL. For example, "inurl:admin" would search for pages that contain the word "admin" within the URL.

![image](https://github.com/Vanitha-SM/Enumeration/assets/119557985/4cbb5993-fed6-4b11-840c-0e09860f860f)

### intitle: 
This operator allows you to search for pages that contain specific text within the title tag. For example, "intitle:index of" would search for pages that contain "index of" within the title tag.

![image](https://github.com/Vanitha-SM/Enumeration/assets/119557985/acd14200-b395-47c4-acc6-043ca3932b70)

### link:
This operator allows you to search for pages that link to a specific URL. For example, "link:example.com" would search for pages that link to the example.com domain.

![image](https://github.com/Vanitha-SM/Enumeration/assets/119557985/c04a1135-281b-4da2-bd39-c1b3f07ca8f6)

### cache: 
This operator allows you to view the cached version of a page. For example, "cache:example.com" would show the cached version of the example.com website.

![image](https://github.com/Vanitha-SM/Enumeration/assets/119557985/a80f0d0f-136e-4908-b5f2-eefdf33e7e52)

 
## DNS Enumeration-




##  DNS Recon
provides the ability to perform:
Check all NS records for zone transfers
Enumerate general DNS records for a given domain (MX, SOA, NS, A, AAAA, SPF , TXT)
Perform common SRV Record Enumeration
Top level domain expansion


![e1](https://github.com/Vineesh-AI-DS/Enumeration/assets/93427254/1c0e832c-630d-4471-8e6b-b562bb0010c7)
![e2](https://github.com/Vineesh-AI-DS/Enumeration/assets/93427254/a47d1e11-174e-4e8f-821f-64668fcaa090)

## dnsenum
Dnsenum is a multithreaded perl script to enumerate DNS information of a domain and to discover non-contiguous ip blocks. The main purpose of Dnsenum is to gather as much information as possible about a domain. The program currently performs the following operations:

- Get the host’s addresses (A record).
- Get the namservers (threaded).
- Get the MX record (threaded).
- Perform axfr queries on nameservers and get BIND versions(threaded).
- Get extra names and subdomains via google scraping (google query = “allinurl: -www site:domain”).
- Brute force subdomains from file, can also perform recursion on subdomain that have NS records (all threaded).
- Calculate C class domain network ranges and perform whois queries on them (threaded).
- Perform reverse lookups on netranges (C class or/and whois netranges) (threaded).
- Write to domain_ips.txt file ip-blocks.
This program is useful for pentesters, ethical hackers and forensics experts. It also can be used for security tests.


![e3](https://github.com/Vineesh-AI-DS/Enumeration/assets/93427254/693c2c0c-00bd-4ed4-955e-2604fe11e24b)


## smtp-user-enum:
Username guessing tool primarily for use against the default Solaris SMTP service. Can use either EXPN, VRFY or RCPT TO.

![image](https://github.com/Vanitha-SM/Enumeration/assets/119557985/ef22300b-9b15-4d41-99a0-0df1dd5c274a)


In metasploit list all the usernames using head /etc/passwd or cat /etc/passwd:

![image](https://github.com/Vanitha-SM/Enumeration/assets/119557985/6640e8b0-f5c7-4fb2-ad53-5dcdac7c6df8)

select any username in the first column of the above file and check the same

![image](https://github.com/Vanitha-SM/Enumeration/assets/119557985/3ca2e9dd-6738-4349-b97a-e11332fe3ee3)

## Telnet for smtp enumeration
Telnet allows to connect to remote host based on the port no. For smtp port no is 25
telnet <host address> 25 to connect
and issue appropriate commands
  
 ![image](https://github.com/Vanitha-SM/Enumeration/assets/119557985/cc88d054-d852-443d-81e1-240061d68e7f)

  
## nmap –script smtp-enum-users.nse <hostname>

The smtp-enum-users.nse script attempts to enumerate the users on a SMTP server by issuing the VRFY, EXPN or RCPT TO commands. The goal of this script is to discover all the user accounts in the remote system.


![image](https://github.com/Vanitha-SM/Enumeration/assets/119557985/3c7db18b-d88f-45a3-b387-d1f60fc24465)



## RESULT:
The Google hacking keywords and enumeration tools were identified and executed successfully

