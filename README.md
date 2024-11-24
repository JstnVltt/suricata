# Suricata
A small project to discover Suricata IDS/IPS.

## Setup
To setup this project, I created with VirtualBox two machines : one Ubuntu to be the server, and one Kali Linux to serve the role of attacker. The two machines were updated.

I installed Suricata on the Ubuntu and configured some alert rules to detect unusual activity. I specially focused on a special scenario where the attacker would ping the server, proceed to an nmap to look after open ports, then try to bruteforce ssh.

You can find configuration files I modified to incorporate rules there.

