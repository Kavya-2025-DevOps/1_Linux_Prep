
                                           LINUX
Basic Linux Questions:
1. What is Linux? How is it different from Windows?
2. What are the different Linux distributions?
3. Explain the Linux file system hierarchy.
4. What are the basic Linux file permissions?
5. How do you check the current working directory?
6. What command is used to list files and directories?
7. How do you create, delete, move, and rename files in Linux?
8. How do you view the contents of a file?
9. What is the difference between absolute and relative paths?
10.How do you check disk space usage in Linux?
11.What is the difference between rm, rmdir, and rm -rf?
12.How do you create a new user and group in Linux?
13.What is the purpose of the passwd command?
14.How do you change file ownership in Linux?
15.What is the purpose of the chmod command?
16.Intermediate Linux Questions:
17.What are hard links and soft links?
18.What is the difference between cron and at?
19.How do you schedule a cron job?
20.What is the /etc/passwd file?
21.What is the /etc/shadow file?
22.How do you check system uptime?
23.What are Linux runlevels?
24.How do you check the system's hostname?
25.How do you find a file in Linux?
26.What is the grep command used for?
27.How do you search for a specific word in a file?
28.How do you count the number of lines in a file?
29.What is the difference between find and locate?
30.How do you check currently running processes?
31.What is the purpose of the kill command?
32.How do you change a process's priority in Linux?
33.What is the difference between nice and renice?
34.How do you check CPU and memory usage?
Follow on Linkedin @JatinBansalDevops
35.How do you check open ports in Linux?
36.What is the difference between df and du commands?
37.How do you monitor real-time logs in Linux?
38.How do you find which process is using a particular port?
39.How do you check system logs in Linux?
40.What is the dmesg command used for?
41.What is the difference between ps, top, and htop?
42.Advanced Linux Questions:
43.What are the different types of process states in Linux?
44.How do you check environment variables in Linux?
45.How do you permanently set an environment variable?
46.What is the purpose of the /etc/fstab file?
47.How do you mount and unmount a filesystem?
48.What is LVM (Logical Volume Manager) in Linux?
49.How do you check free memory and swap space?
50.How do you clear swap space?
51.What is the difference between hard links and symbolic links?
52.What is the difference between sed and awk?
53.How do you extract specific columns from a file?
54.What is the difference between TCP and UDP?
55.How do you check network connectivity using Linux commands?
56.How do you view the routing table in Linux?
57.What is iptables, and how is it used in Linux?
58.What is the ufw firewall, and how do you configure it?
59.What is SSH, and how do you use it?
60.How do you set up passwordless SSH login?
61.How do you check disk partitions in Linux?
62.What is the purpose of chroot?
63.How do you create a swap file in Linux?
64.What is the difference between /dev/sda1 and /dev/sdb1?
65.What is the difference between systemctl and service commands?
66.How do you start, stop, and restart a service in Linux?
67.How do you check which services are enabled on startup?
68.What is the purpose of the journalctl command?
69.How do you extract specific lines from a file?
70.What is the difference between /proc, /sys, and /dev directories?
71.What are inodes in Linux?
72.What is the difference between nohup, screen, and tmux?
Follow on Linkedin @JatinBansalDevops
73.How do you copy an entire directory in Linux?
74.What is the purpose of the rsync command?
75.How do you set up a simple web server using python3 -m http.server?
76.What is the difference between /bin, /sbin, and /usr/bin?
77.How do you troubleshoot high CPU usage in Linux?
78.How do you kill multiple processes matching a pattern?
79.What is a zombie process in Linux?
80.How do you check if a user has sudo privileges?
81.What is the purpose of the /etc/hosts file?
82.How do you update all installed packages in Linux?
83.How do you list all installed packages on a Linux system?
84.What is the difference between rpm, yum, dnf, and apt?
85.How do you check the Linux kernel version?
86.How do you upgrade the Linux kernel?
87.How do you rollback a package update in Linux?
88.How do you create a new systemd service in Linux?
89.What is the purpose of the /var/log directory?
90.How do you check which Linux distribution you are using?
91.How do you secure an SSH server?
92.What is SELinux, and how does it work?
93.What is AppArmor, and how does it compare to SELinux?
94.What is the purpose of the /etc/resolv.conf file?
95.How do you configure a static IP in Linux?
96.How do you enable IP forwarding in Linux?
97.What is a kernel panic, and how do you troubleshoot it?
98.What is the difference between ext3, ext4, and XFS filesystems?
99.How do you perform a filesystem check in Linux?

Scenario-based Linux interview questions:

File & Directory Management Scenarios
1. You accidentally deleted an important file. How would you recover it in Linux?
2. A user reports that they cannot access a file even though they have read
permissions. What could be the issue?
3. You need to find and delete all log files older than 30 days. How would you do that?
4. A directory has thousands of files, and rm -rf is taking too long to delete them. How
can you speed up the deletion process?
Follow on Linkedin @JatinBansalDevops
5. How do you find the top 10 largest files on your Linux system?
6. A script is failing due to a "permission denied" error, even though you are running it
as root. What could be the reason?
7. You need to rename multiple files in a directory that have spaces in their names.
How would you do it?
8. How do you compare two directories and find the differences in files?
9. A user is unable to create files in a directory, but ls -l shows they have write
permission. What could be the problem?
10.A symbolic link you created is broken. How do you troubleshoot and fix it?

User & Permission Management Scenarios
1. A user complains they cannot log in via SSH but their credentials are correct. How
do you troubleshoot?
2. You need to give a user access to run only a specific command with sudo. How do
you configure that?
3. You have a large team, and you need to create 100 users with a script. How would
you do that?
4. A user left the company, and you need to disable their account but retain their files.
How do you do it?
5. You need to change ownership of all files belonging to a deleted user to another
user. How would you do this?
6. How do you reset the root password if you have lost it?
7. A user has been locked out due to too many failed login attempts. How do you
unlock them?
8. You need to add a user to multiple groups in one command. How would you do it?
9. How do you prevent a user from logging in but allow their cron jobs to continue
running?
10.A team needs shared access to a directory, but files they create should be
automatically accessible by others in the team. How do you configure this?

Process & Performance Management Scenarios
1. Your application is running slowly. How do you diagnose and fix the issue?
2. A process is consuming 100% CPU. How do you identify and fix it?
3. How do you identify which process is using the most memory?
Follow on Linkedin @JatinBansalDevops
4. A critical process keeps getting killed due to an "Out of Memory" error. How do you
debug and prevent this?
5. You need to keep a process running in the background even after logging out. How
would you do that?
6. A process is stuck and not responding to kill -9. What else can you try?
7. How do you set a process to run with low priority automatically?
8. You need to monitor system resource usage over time. Which tools would you use?
9. Your server is running out of swap memory frequently. What steps would you take to
fix this?
10.How do you identify and stop zombie processes?

Networking & Security Scenarios
1. A website running on your Linux server is inaccessible, but the server is up. How do
you troubleshoot?
2. You need to allow only a specific IP to access a server over SSH. How would you
configure it?
3. Your server is under a DDoS attack. How do you mitigate it using Linux commands?
4. You need to check which ports are open and which services are listening. How do
you do that?
5. A user is unable to reach an external website from a Linux server. How do you
troubleshoot network connectivity?
6. You need to set up a firewall to allow only HTTP, HTTPS, and SSH traffic. How do you
do it?
7. How do you check which process is using a specific port?
8. A connection to a database is failing from your Linux server. How do you
troubleshoot it?
9. You need to change the default SSH port for security reasons. How do you do it?
10.How do you enable IP forwarding on a Linux system?

Storage & Filesystem Scenarios
1. Your disk is 100% full. How do you find and remove unnecessary files?
2. How do you check which directories are using the most disk space?
3. A mount point is missing after a server reboot. How do you ensure it mounts
automatically?
4. How do you extend a partition without losing data?
Follow on Linkedin @JatinBansalDevops
5. Your /var partition is full. How do you move it to another disk without downtime?
6. How do you check the health of a hard disk in Linux?
7. How do you recover a deleted partition table?
8. A filesystem is mounted as read-only. How do you fix it?
9. How do you check and repair a corrupted filesystem?
10.What steps would you take to create a swap file and enable it?

System Logs & Troubleshooting Scenarios
1. Your server is rebooting randomly. How do you investigate the cause?
2. A user reports that they are getting a "Permission Denied" error when accessing a
log file. What could be the issue?
3. An application is crashing frequently. How do you collect logs and debug it?
4. How do you configure logging to rotate logs automatically?
5. Your system logs are filling up disk space. How do you manage them?
6. How do you check which user deleted a specific file?
7. How do you troubleshoot a slow boot process in Linux?
8. How do you check if a service crashed and restarted automatically?
9. How do you enable persistent logging on a Linux system?
10.A cron job is not running as expected. How do you debug it?

Backup & Disaster Recovery Scenarios
1. How do you back up a Linux system and restore it after failure?
2. You need to create a scheduled incremental backup of a directory. How do you do
it?
3. A developer accidentally overwrote a configuration file. How do you restore it from a
backup?
4. You need to clone a Linux system to another machine. What tools would you use?
5. How do you take a snapshot of a Linux filesystem for quick rollback?
6. You need to recover files from a failed RAID array. How do you do it?
7. How do you back up a MySQL/PostgreSQL database from the command line?
8. How do you ensure backups are automatically verified for integrity?
9. How do you restore a Linux system from a full disk backup?
10.How do you create a bootable recovery disk in Linux?

System & Kernel Scenarios
1. How do you upgrade the Linux kernel safely?
2. You need to enable a specific kernel module. How do you do it?
3. A server crashes with a kernel panic. How do you troubleshoot and fix it?
4. How do you find out which kernel version is running on your system?
5. You need to disable a specific kernel module permanently. How do you do it?
6. Your server has high load but low CPU and memory usage. What could be causing
it?
7. How do you check if the system supports virtualization?
8. A package update broke a system service. How do you roll back the update?
9. How do you force a system to reboot after a kernel panic?
10.How do you apply security patches to a running Linux system without rebooting?
Real-world situations (problem-solving and troubleshooting)

File Management & Permissions Scenarios
1. You created a file, but another user cannot access it even though they have read
permissions. What could be the issue?
2. A user is unable to delete a file, even though they have write permission on the file.
What might be causing this?
3. You need to change permissions on all files inside a directory but not on the
directory itself. How would you do that?
4. A directory has rwx------ permissions, but the owner cannot execute scripts inside it.
What could be wrong?
5. You need to give full permissions to a user on a file but prevent them from deleting it.
How can you achieve this?
6. You need to transfer a large file between two servers, but SCP is too slow. What
alternative methods can you use?
7. How do you find and list all files with 777 permissions and correct them securely?
8. A user has access to a file but gets a "Permission Denied" error when trying to
execute it. How do you fix it?
9. How do you ensure that newly created files in a shared directory automatically have
the correct permissions?
10.You need to remove execute permission from all .sh files inside a directory. How
would you do it?
Follow on Linkedin @JatinBansalDevops
11.A script runs fine manually but fails with a "Permission Denied" error when executed
via a cron job. What could be wrong?
12.You need to prevent a user from accessing a specific directory while keeping their
other access intact. How do you do it?
13.A user needs write access to a file but must not be able to read it. How can you
achieve this?
14.A file has rwxrwxrwx permissions, but a user still can't modify it. What could be the
reason?
15.You want to track changes made to a critical file. How do you do that?

File System & Storage Scenarios
1. Your /home partition is full, but there is free space in /var. How do you resolve this
without data loss?
2. A user reports that they cannot create new files, but df -h shows enough free space.
What could be the issue?
3. A mounted NFS share is not accessible, but the NFS service is running fine. How do
you troubleshoot?
4. After rebooting, a mounted filesystem disappears. How do you ensure it mounts
automatically?
5. You need to move a large directory from one disk to another without downtime. How
do you do it?
6. How do you check the available inodes on a Linux system? What do you do if inodes
are full?
7. A file appears to be taking up space, but du -sh and ls -lh show different sizes. What
could be happening?
8. How do you find and delete files taking up too much disk space in /var/log/?
9. You resized a partition, but df -h still shows the old size. What should you do next?
10.A user needs to mount an external drive, but they get a "Permission Denied" error.
How do you fix it?
11.How do you safely unmount a filesystem that is currently in use?
12.You need to create a new ext4 filesystem on a raw disk. How do you do it?
13.A disk shows as "read-only" after a power failure. How do you fix it?
14.You need to copy an entire disk to another disk. What command would you use?
15.How do you check which process is consuming the most disk I/O?

Advanced Storage & Backup Scenarios
1. How do you create and restore a tar backup of a directory, while preserving file
permissions?
Follow on Linkedin @JatinBansalDevops
2. You need to take an incremental backup of a directory every day. What tools would
you use?
3. How do you create a snapshot of a filesystem before making changes?
4. You need to set up RAID 1 mirroring for a production server. How would you
configure it?
5. A RAID 5 array has one failed disk. How do you replace it and rebuild the array?
6. You need to move all data from one disk to another without downtime. What’s the
best approach?
7. A user accidentally deleted a file. How do you recover it if it's not in a backup?
8. How do you check disk errors and repair a corrupted filesystem?
9. You need to encrypt a disk partition before storing sensitive data. How do you do it?
10.How do you schedule an automated disk usage report to be sent via email every
week?

NFS & Network Storage Scenarios
1. An NFS mount is extremely slow. How do you diagnose and fix the issue?
2. How do you restrict NFS access to a specific IP range?
3. A user gets "Stale NFS file handle" errors. What could be the cause?
4. You need to allow a client to mount an NFS share with read-only access. How do
you configure it?
5. After restarting the NFS server, clients cannot mount shared directories. How do you
troubleshoot?
6. How do you monitor disk usage on a remote system using SSH?
7. A Samba share is accessible but files copied to it are showing wrong permissions.
How do you fix it?
8. How do you mount a remote Linux filesystem securely over SSH?
9. A CIFS share is not mounting at boot. How do you ensure it mounts automatically?
10.How do you list all mounted remote filesystems and their options?

Logical Volume Management (LVM) Scenarios
1. You need to create a new logical volume from available free space. How do you do
it?
2. A logical volume is full, and you need to extend it. How do you do that?
3. How do you reduce the size of an LVM partition safely?
4. A volume group is out of space. How do you add a new physical disk to extend it?
5. How do you migrate data from one LVM disk to another without downtime?
6. A logical volume got corrupted. How do you restore it from a snapshot?
7. You need to encrypt an existing LVM partition. How do you proceed?
Follow on Linkedin @JatinBansalDevops
8. An LVM partition is not mounting after a reboot. How do you troubleshoot it?
9. How do you move a logical volume from one system to another?
10.How do you check which physical disks are used in an LVM setup?

File & Storage Performance Optimization Scenarios
1. A large number of small files are slowing down disk performance. How do you
optimize it?
2. How do you enable write caching on a disk to improve performance?
3. An application frequently reads a large file, causing high disk I/O. How do you
optimize it?
4. How do you enable and configure filesystem journaling for better data integrity?
5. How do you measure disk I/O speed and latency?
6. You need to optimize an NFS-mounted directory for better performance. What
changes would you make?
7. How do you configure Linux to store temporary files in RAM instead of disk?
8. A server frequently runs out of available disk cache. How do you troubleshoot it?
9. How do you prevent an application from consuming too much disk I/O?
10.What steps would you take to convert an ext4 filesystem to XFS without losing data?










## Check for Dublicates

********** Top Qs ***************

How would you troubleshoot high CPU usage in a Linux server?
How would you identify memory leaks in Linux?
How would you troubleshoot disk space issues in production?
How would you find large files consuming disk space?
How would you troubleshoot a server that is not booting?
How would you handle application downtime in Linux?
How would you troubleshoot network connectivity issues?
How would you check which process is using a specific port?
How would you troubleshoot slow server performance?
How would you manage log rotation in Linux?
How would you troubleshoot SSH login failures?
How would you secure a Linux production server?
How would you manage user permissions in Linux?
How would you monitor system resource usage in real time?
How would you troubleshoot file permission issues?
How would you handle service failures in Linux?
How would you troubleshoot DNS issues in Linux?
How would you automate tasks using cron jobs?
How would you troubleshoot Nginx or Apache issues?
How would you perform backup and recovery in Linux?
How would you troubleshoot filesystem corruption in Linux?
How would you identify zombie processes in production?
How would you troubleshoot high load average in Linux?
How would you monitor real-time logs for troubleshooting?
How would you handle server crash analysis in Linux?
How would you troubleshoot package installation failures?
How would you check failed services after server reboot?
How would you manage swap memory issues in Linux?
How would you troubleshoot firewall-related connectivity issues?
How would you perform performance tuning in Linux servers?

