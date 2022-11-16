# Excalibur

---

Excalibur is determined to show that not everything is forever. We have no intention of deploying Excalibur, but just remember that it exists so nothing is impossible. Main code in Excalibur will be locked so no one except the developers can deploy it. Most code will be accesible to display it abilitys, but not enough to be used for harm.

 
<a href=""><img
src="https://img.shields.io/security-headers?url=https%3A%2F%2Fgithub.com%2FFeesh09%2FExcalibur%2Ftree%2Fmain" /></a>

<a href="https://github.com/Feesh09/Excalibur/releases"><img
src="https://img.shields.io/github/downloads/Feesh09/Excalibur/total" /></a>

<a href="https://github.com/Feesh09/Excalibur"><img
src="https://img.shields.io/github/directory-file-count/Feesh09/Excalibur" /></a>
<a href="https://github.com/Feesh09/Excalibur"><img
src="https://img.shields.io/github/languages/code-size/Feesh09/Excalibur" /></a>
<a href="https://github.com/sponsors/Feesh09"><img
src="https://img.shields.io/github/sponsors/Feesh09" /></a>

<a href="https://codeclimate.com/github/Feesh09/Excalibur/test_coverage"><img 
src="https://api.codeclimate.com/v1/badges/625ac657215f73bab8e5/test_coverage" /></a>
<a href="https://codeclimate.com/github/Feesh09/Excalibur/maintainability"><img src="https://api.codeclimate.com/v1/badges/625ac657215f73bab8e5/maintainability" /></a>

**ftpsniffer.py**: This Python script is designed to sniff the host machine for any FTP attempts. When a user attempts to FTP onto a server, the script will print to the console the username, password, and IP used for the FTP connection.\

**httpsniffer.py**: This Python script is designed to sniff the host machine for any HTTP packet in an attempt to grab a packet that contains a user's username and password they used to log into a website. The script will print out the captured packet's URL for the site logged into and payload that contains the username and password./

**synflood.py**: This Python script will attempt a SYN Flood attack. The script will consistently send packets to the destination IP address and port specified by the user, masquerading as an IP address different than the machine that is running the program. For example, this script can be used to block port 80 on the target, resulting in the target being unable to/slowly able to access the internet.\

**machineinfo.py**: This Python program will analyze each packet received by the host machine and print out the contents of its Ethernet, IP, and TCP/UDP headers to the console. The script will differentiate the packet's protocol as either TCP or UDP and print their respective headers to the console.\

**openportscan.py:** A simple port scanner coded in Python that asks to specify an IP address. With this IP address, the script will scan the first 1000 ports and print out which ports are open and which ports are closed.\

