# BabyGate
Simple UFW manager script that tails Apache access_log. Searches for malicious request 
and bans connections from the ip. The ban is timed and released afterwards.

Systemd service file included, should be placed in /etc/systemd/system and 
/path/to/script modified to suit your installation

requires: https://wiki.ubuntu.com/UncomplicatedFirewall and 
https://pypi.org/project/tailer/

