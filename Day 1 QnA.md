
### What is the GNU project?
The GNU(GNU’s Not Unix) project was an initiative to provide development of a free operating system. Here free operating system doesn’t mean free of cost but an operating system in which others can copy, study, contribute & improve. That’s why it is a copyleft all rights reserved product.


### Difference between unix & linux.
| Linux | Unix |
| ------------------------------ | ------------------------------ |
| It is available to everyone, free of cost & open source. | It is only available to its copywriters. |
| It can be used anywhere & by anyone (Students, developers, home users). | It is used for workstations, servers & mainframes. |
| Free of cost. | Different cost for respective Unix distribution. |
| Error & threat detection & cure provision is fast in Linux. | Users have to wait for some time for the solution. |
|It supports a wide variety of file systems. Ext1 to ext4, JFS file system, xfs, Swap, Btrfs. | It does support file systems but less than Linux. S5, ufs, ext2, ms dos/pcfs, swap. |
| Linux is just a kernel. | Unix is a complete package of operating systems. |


### What is the Integrity check of BIOS?
The system integrity check performed by BIOS is called POST(Power On Self Test). This is a very brief test on CPU, memory and storage devices to verify that the system is in a boot-able state.
Then, it will check in the boot priority order to find a boot-able device. It will check in Disk drive, SD card reader, CD/DVD ROM, hard drive according to the boot priority that is configured.


### What is UEFI? Difference between BIOS & UEFI.
UEFI(Unified Extensible Firmware Interface ) is the successor of BIOS and is designed to boot the system instead of BIOS. UEFI stores all the info in a .efi file. This file is stored in another partition called EFI partition along with the bootloader. UEFI comes with many improvements than BIOS but linux is still using BIOS.

| UEFI | BIOS |
| ------------------------------ | ------------------------------ | 
| Supports drive sizes upto 9 zettabytes | BIOS only supports 2.2 terabytes |
| Faster boot time | Slower compared to UEFI |
| Provides secure boot to prevent unauthorised | BIOS can be compromised |


### What does 5 mean in systemd.unit(5)?
Here in the braces the digit denotes the manual page which consists of 8 sections.
| S NO | Description |
| ----- | -------------------------------|
| 1 | General Commands |
| 2 | System Calls |
| 3 | Library functions, covering in particular the C standard library |
| 4 | Special files (usually devices, those found in /dev) and drivers |
| 5 | File formats and conventions |
| 6 | Games and screensavers |
| 7 | Miscellanea |
| 8 | System administration commands and daemons |


### What does the uname command do?
Uname Command is used for displaying the information about this system.
SYNTAX- uname [option]
OPTIONS-      
-a  It prints all the system information in the following order: 
Kernel name, network node hostname, kernel release date, kernel version, machine hardware name, hardware platform, operating system
Syntax: $uname  -a

-s  It prints the kernel name.
Syntax: $uname  -s

-n  It prints the hostname of the network node (current computer).
Syntax: $uname  -n

-r   It prints the kernel release date.
Syntax: $uname  -r

-v   It prints the version of the current kernel.
Syntax: $uname  -v

-m  It prints the machine hardware name.
Syntax: $uname  -m

-p   It prints the type of the processor.
Syntax: $uname  -p

-i    It prints the platform of the hardware.
Syntax: $uname  -i

-o   It prints the name of the operating system.
Syntax: $uname  -o

### Various linux distributions
* `Ubuntu` For personal computers & servers
* `Debian`  Bug Tracking, penetration testing, Network scanning
* `CentOs` Rich base for open source communities
* `Arch Linux` x86-64 base
* `Fedora` Vast Software availability, Rapid release of softwares, excellent snap support

### Various operating systems & their uses.
MS DOS- Single user operating system, lightweight, direct contact to BIOS & hardware.
Windows- Provides a rich GUI for novice users too. It is backward compatible too(old programs can run on newer versions). Automatically detect hardware changes.
Linux- Open source, easily portable on many devices. Has CLI that's why it is faster than many operating systems.
Solaris- Can handle a massive scalability & can still deliver indisputable results. Hardly crashes. Specially built for network computing.

### Getty Command
The getty command sets and manages terminal lines and ports. The getty command is run by the init command. The getty command is linked to the Terminal State Manager program. The Terminal State Manager program provides combined terminal control and login functions.

### Difference between Systemd & init d.
Init d is a daemon process which means that it starts when the system boots up & stops when it shuts down. While systemd is designed to start a service in parallel. When run as a system instance, systemd interprets the configuration file system.config & the files in system.conf.d directories & when run as a user instance, systemd interprets the configuration file user.conf & the files in user.conf.d directories.

### Init command
init [OPTIONS...] COMMAND \
Send control commands to the init daemon.\
Commands:\
  * `0`              Power-off the machine \
  * `6`              Reboot the machine \
  * `2, 3, 4, 5`     Start runlevelX.target unit \
  * `1, s, S`        Enter rescue mode \
  * `q, Q`           Reload init daemon configuration \
  * `u, U`           Reexecute init daemon \

Options: \
     --help      Show this help \
     --no-wall   Don't send wall message before halt/power-off/reboot \

### When should I go for Ubuntu & when for other systems?
Ubuntu is an open source OS & is well known for it’s faster response rate & provides virus free environment. In comparison to windows, Ubuntu provides much better security. Ubuntu is only for developers & coders. Open source contributions can also be made. 

When a user wants more user-friendly OS then Windows is best for such novice users. It is a great platform to enjoy GUI based applications including games. It provides a wide variety of softwares. Almost every application is available for windows.

Solaris is the priority of organizations which have a great demand for scalability & continuous results. Provides a very secure environment. Best for java & network based applications.

