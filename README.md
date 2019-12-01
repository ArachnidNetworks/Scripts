# Scripts
***Maintenance Scripts for Arachnid.*** </br>

**What do these do?** </br>
These scripts are various useful tools to assist in the day-to-day maintenance of Arachnid Networks Infrastructure. These tools are open source for the sake of improvement and giving back to the community so you can power your own infrastructure that runs on Arachnid. </br>

*backup.sh* </br>
A simple backup script, read and configure the script before using to avoid backing up to the wrong location! Docs can be found inside the file. </br>

*Update.sh* </br>
This script comes in several flavors for several distros, and works on systems based on these said distros. This program is intended to aid in the automation of updating infrastructure. To do complete headless automation, write your own expect scripts! The current supported package managers are apt, yum, pacman and emerge. </br>

*LinuxHardened.sh* </br>
This script is intended to aid in the installation of a Hardened Linux kernel for your linux distribution. Installs package Linux-Hardened on pacman-based systems, Linux-grsec kernel on apt based systems, and compiles a grsec kernel from scratch on yum based systems. The script for compiling a kernel from scratch is still a prototype and not recommended for production use! Currently supports debian based systems, Arch based systems and RHEL-based systems. 
