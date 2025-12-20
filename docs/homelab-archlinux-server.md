
# What kind of hosting ?

This section I will elaborate about my decision in what kind of hosting i'm going to follow. Probably something with Kubenetes 

# ArchLinux Server

These are the steps I took to configure ArchLinux on an old laptop


# Why ArchLinux ?

Arch linux is a minimal base system, configured by the user to only have what is required. Order than that, the instalation proccess is very enriching since give a lot of knowlegment about the linux proccess

I used to use Arch Linux on college, but didn't understand what was happening under the hood. My goal is use as minimal as possible third-party software an use `systemd` when possible. For example, I'm using systemd-resolved to manage my network.

# ArchLinux

Disable hibernate on lid close

https://bbs.archlinux.org/viewtopic.php?id=161719

In order to disable hibernate on lid close I had to edit the `/etc/systemd/logind.conf` file and modify the line:

`#HandleLidSwitch=suspend` to `HandleLidSwitch=ignore`

Then you need to restart the logind service `systemctl restart systemd-logind` 


# K3s

K3s is a highly available, certified Kubernetes distribution designed for production workloads. K3s is packaged as a single <70MB binary that reduces the dependencies and steps needed to install, run and auto-update a production Kubernetes cluster.



# Todo

* [] Explain why ArchLinux
