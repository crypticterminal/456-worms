Assignment 1
Fall 2016 --- CPSC 456


Virtual Machines:
Attacker - VM3 (192.168.1.6)
Victims - VM1 (192.168.1.4) and VM2 (192.168.1.7)
Credentials - Username: ubuntu        Password: 123456


How To Execute:
replicator_worm.py - From attacker machine (VM3), enter 
python /tmp/replicator_worm.py in the command line.

passwordthief_worm.py - From attacker machine (VM3), enter 
python /tmp/passwordthief_worm.py in the command line.

extorter_worm.py - From attacker machine (VM3), enter 
python /tmp/extorter_worm.py in the command line.


Extra Credit:
We did not implement the extra credit.


Special Notes:
Man, it’s worm in here.
All worms and the infected marker reside in the /tmp/ folder under their respective names. This is where the worm propagates from. There are also copies in the ~/Desktop/Worms/ folder in case the /tmp/ folder gets cleaned out by the system.
