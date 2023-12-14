- name: WEEK-3 interview Questions
  topic: Linux
  Questions:
    - Ques: How do you troubleshoot high CPU usage on a Linux server?
      Ans:
      - use top/htop and get that process
      - check what is that process. is it system process our application?
      - check system logs and application logs. /var/log/messages
      - restart if business is going down
      - check hardware health, temperature
      - use monitoring tools like prometheus, grafana, etc.
      - check are you running any unnecessary services.
    - Ques: Describe the boot process of a Linux system?
      Ans:
      - Power-On and BIOS/UEFI. Unified extensive firmware interface is latest instead of BIOS. It wil check post Power-On tests and identifies connected hardware components.
      - Boot Loader Stage. /boot/grub is the location for boot loader.
      - GRUB (Grand Unified Boot Loader). GRUB is a common boot loader that loads the Linux kernel into memory. It presents the user with a boot menu if multiple operating systems are installed.
      - Linux Kernel Initialization. loads kernel into memory. It starts the hardware, configure memory, mount filesystem.
      - Init System. Intialises the systemd processes.
      - Users. System prepares the users.
      - Login Prompt or Graphical User Interface
      - User Login and Session Initialization
    - Ques: You need to transfer a large file securely between two Linux servers. What  tools or protocols would you use, and why?
      Ans:
      - scp command can be used.
      - rsync command can be used, it will compare the files and transfer only files that does not exist. Less occupancy of system resources and higher efficiency.
    - Ques: You notice a sudden increase in the number of failed login attempts on a Linux server. How would you investigate and enhance the server's security in response to this activity?
      Ans:
      - check system logs like /var/log/auth.log and /var/log/secure to identify IP addresses, usernames, and timestamps for failed login attempts.
      - Look for patterns such as repeated failed attempts from specific IP addresses or multiple login attempts for the same user account.
      - Blocking IPs. Tools like fail2ban can automatically detect and block IPs exhibiting suspicious behavior.
      - Implement Two-Factor Authentication (2FA)
      - Server Hardening. CIS benchamarking.
      - Monitoring and Alerts. Configure Alerts and Regular Audits
      - prepare Incident Response Plan
      - Enable connections only from VPN.
    - Ques: A user accidentally deleted an important file, and you need to recover it from the backup. Explain the steps you would take to restore the file.
      Ans:
      - We will raise a request to storage team about file location and IP address. We will take approval from our manager and work with storage team.
      - Locate the Backup
      - Access the Backup
      - Mount the Backup Location
      - Restore the File
      - Backup Verification
    - Ques: A user reports that they are unable to connect to a remote Linux server using SSH. How would you troubleshoot and resolve this connectivity issue?
      Ans:
      - Ping the Server
      - Check SSH Service. systemctl status sshd
      - Check the firewall
      - Check /etc/ssh/sshd_config
      - Check SSH Key Authentication
      - Disk Space and Permissions. Check permissions for the user's home directory and SSH-related files.
      - check /var/log/auth.log for errors
      - Check router configuration
    - Ques: You need to find all files larger than 100MB in the /home directory and its subdirectories. How would you accomplish this task?
      Ans:
      - find /home -type f -size +100M
    - Ques: Forward vs reverse proxy
      Ans:
       Forward Proxy:
       - Client-Side Proxy
       - Helps hide the client's identity and provides anonymity
       - Commonly used to bypass content filters or access restricted content
       - Controls and filters access to certain websites or content based on predefined policies.
       - Controls and filters access to certain websites or content based on predefined policies.
       Reverse Proxy:
       - Positioned in front of servers on server side.
       - Represents servers to clients and forwards requests to the appropriate backend servers.
       - Load Balancing
       - SSL Termination
    - Ques: What is inode?
      Ans:
      - File Location. Inodes store crucial metadata about files, such as File ownership (user and group IDs). File size in bytes. Timestamps (creation, modification, and access times).Permissions (read, write, execute).File type and attributes.
      - File Location. Inodes contain pointers or references to data blocks on the disk where the actual content of the file is stored.
    - Ques: Softlink vs Hardlink
      Ans:
        Softlink:
        - They act as shortcuts or aliases to the original file or directory.
        - They are separate files that contain the path to the target file or directory. inode of Softlink is different to original file.
        - Can point to directories.
        - If the original file is deleted, the symbolic link becomes a dangling link or "broken" link.
        Hardlink:
        - Cannot link to directories
        - If the original file is deleted, the hard link remains, as it points directly to the inode's data.
        - Hardlink inode is same as original file inode.
        - Used to keep the backup of the file.
    
      
      
    
