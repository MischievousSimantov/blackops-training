**File system structure (1h)**

-   Read about the [linux file system
    structure](https://www.howtogeek.com/117435/htg-explains-the-linux-directory-structure-explained/),
    and about the directories in it.

    Answer the following questions:

    -   Where will I save a bin file that only my user needs?

        > What's the difference between /lib and /bin?

        > What's saved inside /mnt if you are using wsl?


**Services and systemd (3h)**

-   Read about
    [systemd](https://www.linux.com/training-tutorials/understanding-and-using-systemd/).

    Read about [linux
    services](https://www.imaginelinux.com/service-in-linux/),
    understand their benefits and [how to create a
    service](https://linuxhandbook.com/create-systemd-services/).

    And answer the following questions:

    -   Give three known services in linux.

        > What is a deamon?

**System administration commands (4h)**

-   Read about and use the following commands, for each of them write
    what it does:

    -   hostname

        > systemctl

        > who

        > free

        > top

        > vmstat

        > ps

    Answer the following questions:

    -   Which of the commands can help u detect problems in your linux
        > system?

        > What is a process and how can u end it?

**File-system utilities (2h)**

-   Read about [partitions in
    linux](https://www.2daygeek.com/linux-fdisk-command-to-manage-disk-partitions/)
    and
    [nfs](https://access.redhat.com/documentation/en-us/red_hat_enterprise_linux/7/html/storage_administration_guide/ch-nfs#s1-nfs-how).

    Answer the following questions:

    -   How does the system "know" on what partition it needs to save
        > each path?

        > What is /etc/exports?

**The Linux boot process(3h)**

-   Read about [BIOS and
    UEFI](https://www.howtogeek.com/56958/htg-explains-how-uefi-will-replace-the-bios/),
    [partition
    tables](https://en.wikipedia.org/wiki/GUID_Partition_Table)[,](http://www.apple.com/)
    [GRUB](https://www.gnu.org/software/grub/),
    [sysv-init](https://wiki.archlinux.org/title/SysVinit) and the
    [linux boot
    process](https://opensource.com/article/17/2/linux-boot-and-startup).

    Answer the following questions:

    -   What is PXE? How does it differ from BIOS?

        > What is initrd?

        > Detail the process in your linux pc?

        > Why should I use systemd vs sysV-init


**Nsswitch(1h)**

-   Read about the [name service
    switch](https://en.wikipedia.org/wiki/Name_Service_Switch) and its
    [configuration](https://developers.redhat.com/blog/2018/11/26/etc-nsswitch-conf-non-complexity).

    Answer the following questions:

    -   What are the different service options?

        > What are the different switching options?

**Advanced commands and tools for linux administrators(8h)**

-   Read about and use the following commands, for each of them write
    what it does:

    -   jq

        > lsof

        > lspci

        > lsblk

        > strace

        > fdisk

        > mkfs

        > tune2fs

        > fsck

        > crontab

        > nmcli

        > nmtui

        > tcpdump

        > nmap

        > telnet

        > netcat

    Answer the following questions:

    -   Use one of the above command and find out what is the largest
        > root directory, why is that directory the largest?

        > How can you change the dns server of a host, explain in
        > detail?

        > Can you add another network interface to your host, how can u
        > do that? And how does it not interfere with the other
        > interface?

    Load up a test web server and create a chat.

**LVM - Logical volume manager(1.5h)**

-   Read about
    [lvms](https://www.digitalocean.com/community/tutorials/an-introduction-to-lvm-concepts-terminology-and-operations).

    Answer the following questions.

    -   Why can't you easily decrease the size of a volume?

        > Why would we want to use logical volumes?

**File system concepts(2h)**

-   Read about [different unix
    filesystems](https://opensource.com/article/18/4/ext4-filesystem),
    and
    [inodes](https://www.howtogeek.com/465350/everything-you-ever-wanted-to-know-about-inodes-on-linux/).

    Answer the following questions:

    -   What is xfs?

        > What is the connection between inodes and lvm?

**Advanced Linux and Security(2.5h)**

-   Read about [namespaces and
    cgroups](https://www.nginx.com/blog/what-are-namespaces-cgroups-how-do-they-work/),
    [selinux](https://www.techtarget.com/searchdatacenter/definition/SELinux-Security-Enhanced-Linux)
    and
    [capabilities](https://man7.org/linux/man-pages/man7/capabilities.7.html).

    Answer the following questions:

    -   Why do we need cgroups?

        > What is the connection between namespaces and containers?

        > What does selinux seek to solve?

        > What is the difference between selinux and AppArmor?

        > Explain why there are that many capabilities. Can you devide
        > the different capabilities to major groups?

