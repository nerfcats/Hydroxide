# Hydroxide Removal Guide

Removing Hydroxide is relatively easy for the first part. If you didn't restart yet
- Remove win32ch.exe from System32
- Remove start.vbs from shell:startup
- Reenable UAC

If you restarted? It's going to be a lot harder. And you are on a time pressure of 60 seconds.
- Kill win32ch ASAP (to stop the crash timer), else it will restart into an unbootable machine
- Since your MBR or whatever is trashed, you should back up all your files (if they weren't trashed too)
- Recover the MBR with a recovery ISO
- Since the trojan overwrites most user files and programs with random data, it may be hard to recover them. Good luck. The main folders the trojan targets is the Users folder and the Program Files folder.
