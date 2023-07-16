Linux - preface and introduction (1h)
Read about linux, its advantages & disadvantages and the philosophy of unix, understand what is linux and explain the differences between linux distros.
Answer the following questions:
Who created linux? When and why?
Give a few uses of linux in our modern world.
Why do most of the servers In the world run linux? Why normal people use windows instead?
What’s the difference between a file and a folder in linux?
What is RHEL?
Permissions, Theory, Ownership, Users, Accounts (0.5h)
Read about linux file permission and ownership, umasks, and how to change it.
Read about the different files that are in the user home directory, files such as profile, .bashrc.
Read about the management of users in linux.
Answer the following questions:
What are the three different file permissions in linux?
What permission every directory has?
What’s a umask?
What’s uid? 
SSH
Might be redundant….
File system structure (1h)
Read about the linux file system structure, and about the directories in it.
Answer the following questions:
Where will I save a bin file that only my user needs?
What’s the difference between /lib and /bin?
What’s saved inside /mnt if you are using wsl?
The super-user (root) and others (2.5h)
Read about the root user, the sudoers file and wheel groups.
Answer the following questions
What does the su command do?
Can I (a non root user), run a command as root without using su or sudo?
What is the difference between setuid and setgid?
Working with a terminal command line (2h)
Read about and use the following commands, for each of them write what it does:
pwd
cd
ls
clear
cp 
mv
rm
cat
less
whereis
watch
whoami
date
echo
vim
reboot
tar
gzip
find
grep
less
uniq 
cut
wc
sort
tail
head
awk
sed
Man
Explain the difference between yum and apt.
Linux files, I/O, piping (1h)
Read about the different linux file types, links and data streams.
Answer the following questions:
What do we need soft links?
How can we use the value of one command in another?
Services and systemd (3h)
Read about systemd.
Read about linux services, understand their benefits and how to create a service.
And answer the following questions:
Give three known services in linux.
What is a deamon?
System administration commands (4h)
Read about and use the following commands, for each of them write what it does:
hostname
systemctl
who
free
top 
vmstat
ps
Answer the following questions:
Which of the commands can help u detect problems in your linux system?
What is a process  and how can u end it?
Bash (13h)
Read about bash, environment variables, shell scripts and PATH.
Answer the following questions:
What is #!/bin/bash?
Do all of the shells run as the same process?
Write a bash script that takes all the logs from the last hour and append them all in one file under /home/<your-user>/one_log_to_rule_them_all, in addition to that count how man error logs are in this file and write the amount in /home/<your-user>/counting_logs.
After you are finished write a linux service that runs the script.
File-system utilities (2h)
Read about partitions in linux and nfs.
Answer the following questions:
How does the system “know” on what partition it needs to save each path?
What is /etc/exports?
User mode / Kernel mode(2h)
Read about user and kernel modes.
Answer the following questions:
Detail the process in which a application gets access to a hardware component.
When we create a file do we go into kernel mode?
The Linux boot process(3h)
Read about BIOS and UEFI, partition tables, GRUB, sysv-init and the linux boot process.
Answer the following questions:
What is PXE? How does it differ from BIOS?
What is initrd?
Detail the process in your linux pc?
Why should I use systemd vs sysV-init
The logon \ Logout process(1h)
Read about the logon/logout process.
Answer the following questions:
What files are important during the logon process?
What files are unique for every user?
What is getty and agetty?
Nsswitch
Read about the name service switch and its configuration.

