
# What kind of hosting ?

This section I will elaborate about my decision in what kind of hosting i'm going to follow. Probably something with Kubenetes 
# ArchLinux Server

These are the steps I took to configure ArchLinux on an old laptop


# Why ArchLinux ?

# ArchLinux

Disable hibernate on lid close

https://bbs.archlinux.org/viewtopic.php?id=161719

In order to disable hibernate on lid close I had to edit the `/etc/systemd/logind.conf` file and modify the line:

`#HandleLidSwitch=suspend` to `HandleLidSwitch=ignore`

Then you need to restart the logind service `systemctl restart systemd-logind` 

# Todo

* [] Explain why ArchLinux
* [] Add networkmanager 
