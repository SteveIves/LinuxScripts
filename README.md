# LinuxScripts
A selection of Linux shell scripts that I find useful when configuring Synergy environments on init-based Linux systems.

1. Put these scripts in /etc/init.d
2. Use update-rc.d to hook the scripts into the system boot sequence

E.g.:

$ sudo update-rc.d synlm defaults

