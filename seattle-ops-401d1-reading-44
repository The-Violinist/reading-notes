David Armstrong 12-07-2020

Because today’s reading was a repeat of a previous one I decided to do
something new today. The reading I chose is Jonathan‘s blog post on Metasploit
for beginners. It started out by describing what Metasploit is. However, once it
got into the implementation, there was much new material for me. The first item
was using a database to store results. This was done with the following
commands:

service postgresql start
msfdbinit

Once the database is initialized then you can run msfconsole. 

As a starting point you find all possible targets by running:
db_nmap -sV [network address]
All hosts can be listed using the command: hosts
Horse or added to the database with: hosts -R
Available scanners can be listed using: search port-scan
Within msfconsole, you can find exploits by using the search command with:
type, cve, name.

You then type the following command: use [path to exploit]
From there you can use the “show” command for payloads and targets.

Finally run the payload using the command “exploit”.
