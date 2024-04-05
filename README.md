Networks
vulnerability(weakness)
hashcat,brute force-password cracking tool
Attacks-cracking (using) hardware without permission,
RAT-Remote Access Trojan
securing the data, resources
safe gurading
controls:
phsical control
administrative control
logical control
Port scanning
protocols(sets of rules)
ports(65,535-tcp,65,535-udp-1,73000 ports)entry gate
443 port-https(safe website)
80 port-http(unsafe website)
blockchain
exploit
SQL injection
session hijacking
phishing
DNS posioning
IP address
crptography
ARP posioning
hashing
spoofing
meta sploit-tool
back door
cross site 
Hacking - gaining unauthorized access
ethical hacking-gaining unauthorized access with written concern
web application peneration/security testing
web page-ideas in written format
web site-collection of webpages
web application-where user interaction is high
web server-
Offensive(red) and defensive(blue)-soc(security operation )reverse engineering,both(purple)
3 type of hackers:
white hat(architecture of web application),black hat,grey hat
hactivism - social purpose
CIA-Confidentiality,Integrity,Availability
authentication-verifying someones indentification
3 factors: something u know,something u have,someyhing u are(fingerprint)
integrity-orginality 
athourization/access control-permission
conversion of original data to sifer data-encrpytion
breach-loss of control
event-any observable occurance
incident-whichs affects CIA
intrusion-security event
threat-possibility to damage
TOE-Target of Evaluation
Attacks:
ransomeware - focusing on microsoft os by encrypting the messages nd demaning the payment in 2017
botnets-done by bots focusing on online customers by changing their ip address
phising- social engineering attack , it is a difficult attack by cliking a link , downloading a document
chain of custody(forensic security)-prove in court about logs
logs-os logs,data logs,application level logs ,network logs
steps to treat a crime: identify the request,check the type of authorization,response should have awarness about each specific attacks
cryptography is atechnique used to hide the information(crpyto-hidden/secret)
types: symmetric/single key- only 2 people authorized people can access given by password
asymmetric/public/private key- many of them have the password to access
.bat and .exec window path
simple attacks:
@echo off
start mspaint
start cmd
ipconfig --help
linux -c switch counts
windows -n switch no.of counts
network device permanent address is mac
ceaser cipher
DES-data encryption standard 56bit
3XDES
AES-128 bit,192bit,256 bit
DHCP-AUTOMATICALLY ASSIGNS IP ADDRESS
DNS SERVER-CONVERTS DOMAIN NAME TO IP AND IP TO DOMAIN NAME
LINUX OPERATING SYSTEM RELEASED-*1991*
COMMAND USED FOR OUTPUT-*echo TEXT*
USERNAME LOGGED TO DEPLOYED LINUX MACHINE-*tryhackme*
If we wanted to run a command in the background, what operator would we want to use-*&*
If I wanted to replace the contents of a file named "passwords" with the word "password123", what would my command be-*echo password123>passwords*
Now if I wanted to add "tryhackme" to this file named "passwords" but also keep "passwords123", what would my command be-*echo tryhackme>>passwords*
*LINUX IS USED IN:*
         CAR,ENTERTAINMENT,REGISTER IN SHOPS,TRAFFIC LIGHT INFRASTRUCTURE
*echo*== Output any text that we provide
*whoami* ==	Find out what user we're currently logged in as!
what exists in the first place ==*ls*
DISPLAY THE CURRENT FILE == *cd*
CONCATENATION ==*cat
displays the full pathname of the current directory == *pwd*
a command used for searching specific values in content == *grep*
to brute-force FakeBank's website to find hidden directories and pages we will use the command *"GoBuster"*
 python -m http.server 80
 LINUX OPERATING SYSTEM RELEASED-*1991*
COMMAND USED FOR OUTPUT-*echo TEXT*
USERNAME LOGGED TO DEPLOYED LINUX MACHINE-*tryhackme*
If we wanted to run a command in the background, what operator would we want to use-*&*
If I wanted to *replace* the contents of a file named "passwords" with the word "password123", what would my command be-*echo password123>passwords*
Now if I wanted to add "tryhackme" to this file named "passwords" but also keep "passwords123", what would my command be-*echo tryhackme>>passwords*
*LINUX IS USED IN:*
         CAR,ENTERTAINMENT,REGISTER IN SHOPS,TRAFFIC LIGHT INFRASTRUCTURE
*echo*== Output any text that we provide
*whoami* ==	Find out what user we're currently logged in as!
what exists in the first place ==*ls*
DISPLAY THE CURRENT FILE IN LS DIRECTORY == *cd*
CONCATENATION ==*cat*
displays the full pathname of the current directory == *pwd*
a command used for searching specific values in content == *grep*
to brute-force FakeBank's website to find hidden directories and pages we will use the command *"GoBuster"*
COMMANDS USED IN WINDOWS==*dir*
cd..\..\ = *FORWARD*
*cd .. * -backward
WHERE PROGRAM IS DOWNLOADED=*where python*
*cd ../../../* =HOW MANY SLASHES THERE IT WILL GO THAT MUCH TIMES BACKWARD
*where*COMMAND IS ONLY USED IN COMMAND PROMPT NOT IN POWERSHELL
*echo "test" > filename== A FILE IS CREATED*
*cat.\filename == test*
*more* command is used to read the file name in command prompt
IF EXTENSION IS NOT THERE THEN IT IS NOT VISIBLE IN WINDOWS
The *mkdir*command in Linux/Unix is a command-line utility that allows users to create new directories
*mv* COMMAND IS USED TO MOVE
mv .\sourcefilename .\destfilename\
*cp* - USED TO COPY THE FILE
Dns server works in port 53
lo- loop back-network interface
etho-ethernet0
vpn to break firewall,masking,encrypt the connection btw client and server,encryption/decryption
after vpn connect ip(like 10.10.10.2) will get changed by encryotion algorithm
encryption-clear text->cipher text
decryption-cipher text->clear text
encryption(2 way) and hashing(1 way)
md4 hash generator to get hash
brute force attack is all possible permutation and combination
finding password from txt document is called dictonary attack
a set of tools used for penetration testing of web applications - *BURPSUITE*
Which edition of Burp Suite runs on a server and provides constant scanning for target web apps? - *Burp Suite Enterprise*
Burp Suite is frequently used when attacking web applications and __ applications - *Mobile*
Which Burp Suite feature allows us to intercept requests between ourselves and the target? - *Proxy*
Which Burp tool would we use to brute-force a login form? - *Intruder*
What menu provides information about the actions performed by Burp Suite, such as starting the proxy, and details about connections made through Burp? - *Event log*
Which tab Ctrl + Shift + P will switch us to? - *Proxy tab*
In which category can you find a reference to a "Cookie jar"? - *Sessions*
In which base category can you find the "Updates" sub-category, which controls the Burp Suite update behaviour? - *Suite*
What is the name of the sub-category which allows you to change the keybindings for shortcuts in Burp Suite? - *Hotkeys*
If we have uploaded Client-Side TLS certificates, can we override these on a per-project basis (yea/nay)? -*yea*
3 ,**TLS** handshake  will occur in https(assymetric)(encrypted)(port 80)(secured)
urgent and push flag will send the packets automatically
PACKET CRAFTER-Packet will be created by own and will be sent
Clent Request ------->server  Response ---->DB
HTTP Methods                              **Response code**
GET                                 starts with **1xx**-Informational
POST used to send data                          **2xx**-(SUCCESS)OK
PUT used to change the data                     **3xx**-REDIRECTION
OPTIONS                                         **4xx**-Client-side  Error
DELETE                                          **5xx**-Server side error
Security Testing  done by three ways
QA Environment-testing build
Staging Environment-Actual cpy of production
Production Environment-Live websites/web app
Client----->**BURP PROXY* ----->Server   <----- **BRUPSUITE**
6 Proxy are working in** TOR** Between clent and server
Proxy controls responses and req
User Agent is the browser
****kali commands**
sudo- do as super user
route for linux
1.sudo service NetworkManager start
2.sudo nmcli networking on
3. cat /etc/apt/sources.list to read
4.nano /etc/apt/sources.list 





























































same devices connecting crossover wire
different devices connecting strainghthrough wire
for connecting 2 routers serial cables r used
