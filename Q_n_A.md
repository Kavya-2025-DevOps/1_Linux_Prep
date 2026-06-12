
Basic Linux Questions:

1. What is Linux? How is it different from Windows?
   Linux is open-source and usually free, while Windows is proprietary and licensed by Microsoft.
   Linux offers greater customization and is preferred for servers and development.
   Windows is generally more user-friendly and has broader support for commercial software and games.
   Linux is considered more secure and lightweight than Windows.

2. What are the different Linux distributions?
   Linux distributions (distros) are different versions of Linux designed for specific users and purposes.
   Popular Linux distributions include Ubuntu, Red Hat Enterprise Linux, CentOS, Fedora, Debian, SUSE, and Arch Linux, each designed for different use cases such as desktop, server, or enterprise environments.

3. Explain the Linux file system hierarchy.
   The Linux file system follows a hierarchical structure that starts from the root directory (/). All files and directories are organized under this root. The Linux file system is organized as a hierarchical tree with standard directories like /bin, /etc, /home, /var, and /usr serving specific purposes.  
     / – Root directory, the top level of the file system.  
    /bin – Essential user commands.  
    /sbin – System administration commands.  
    /etc – Configuration files.  
    /home – User home directories.  
    /root – Home directory of the root user.  
    /var – Variable data such as logs and mail.  
    /tmp – Temporary files.  
    /usr – User programs and utilities.  
    /dev – Device files.  
    /proc – Process and kernel information.  
    /boot – Boot loader and kernel files.  
   
4. What are the basic Linux file permissions?  
   Linux file permissions control who can access a file or directory. There are three types of permissions:  
     Read (r) – Permission to view the file contents.  
     Write (w) – Permission to modify the file.  
     Execute (x) – Permission to run the file as a program.  
   Permissions are assigned to three categories of users:  

    Owner (u) – The file creator/owner.  
    Group (g) – Users belonging to the file's group.  
    Others (o) – All other users.  

5. How do you check the current working directory?  
   "pwd" - Print Working Directory    

6. What command is used to list files and directories?  
   The ls command is used in Linux to list files and directories  
   Common options:  
        ls -l → long listing format (permissions, size, owner)  
        ls -a → shows hidden files  
        ls -lh → human-readable file sizes  
        ls -R → recursive listing  

7. How do you create, delete, move, and rename files in Linux?    
   1. Create a file -> "touch file.txt" OR "cat > file.txt"    
   2. Delete a file -> "rm file.txt"    
   3. Move a file -> "mv file.txt /home/user/Documents/"    
   4. Rename a file -> "mv old.txt new.txt" (Note: In Linux, rename is also done using mv command.)  

8. How do you view the contents of a file?  
   File contents in Linux can be viewed using commands like cat, less, more, head, and tail depending on whether you want full, paged, or partial output.  
    cat – Displays the entire file content at once => cat file.txt  
    less – Views file page by page (scrollable) => less file.txt  
    more – Similar to less, but with limited navigation => more file.txt  
    head – Shows first 10 lines of a file => head file.txt  
    tail – Shows last 10 lines of a file => tail file.txt  

9. What is the difference between absolute and relative paths?   
   An absolute path starts from the root directory (/) and gives the full location,    
   while a relative path is based on the current working directory.  
   
10.How do you check disk space usage in Linux?  
    To check disk space usage in Linux, we use the following command: "df -h "  
    Explanation:  
	      df → shows disk space usage of file systems  
	      -h → human-readable format (KB, MB, GB)  
    Example output:  
      	Filesystem      Size  Used Avail Use% Mounted on  
      	/dev/sda1       100G   45G   55G  45% /  
    Additional command (for directory usage):  
        "du -sh *"  => Shows size of files and directories in current folder  

11.What is the difference between rm, rmdir, and rm -rf?  
    1. rm => "rm file.txt"  
        Used to delete files  
        Can also delete directories with options  
    2. rmdir =>  "rmdir myfolder"  
        Used to delete empty directories only  
        Will not work if the directory has files inside  
    3. rm -rf => "rm -rf myfolder"  
        Used to delete directories and their contents recursively  
        -r → recursive (delete folders and files inside)  
        -f → force (no confirmation prompts)  
        Dangerous command: Can permanently delete important data if used incorrectly.  
    
12.How do you create a new user and group in Linux?  

13.What is the purpose of the passwd command?
14.How do you change file ownership in Linux? 
15.What is the purpose of the chmod command? 
