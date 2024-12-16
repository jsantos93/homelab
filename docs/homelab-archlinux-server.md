# ArchLinux Server

These are the steps I took to configure ArchLinux on an old laptop


# Why ArchLinux ?



# ArchLinux

Disable hibernate on lid close

https://bbs.archlinux.org/viewtopic.php?id=161719

In order to disable hibernate on lid close I had to edit the /etc/systemd/logind.conf file and modify the line:

`#HandleLidSwitch=suspend` to `HandleLidSwitch=ignore`



# Todo

* [] Explain why ArchLinux
* [] Add networkmanager 
