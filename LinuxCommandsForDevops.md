# ========================================
# Linux Commands for DevOps Engineers
# ========================================

1. **File and Directory Management**
   - `ls`: List files and directories.
     Example: `ls -l` (detailed list), `ls -a` (show hidden files).
   - `cd`: Change directory.
     Example: `cd /var/log` (move to /var/log).
   - `pwd`: Print the current working directory.
   - `mkdir`: Create a directory.
     Example: `mkdir my_folder`.
   - `rm`: Remove files or directories.
     Example: `rm file.txt`, `rm -r folder` (recursively delete a directory).
   - `cp`: Copy files or directories.
     Example: `cp file.txt /backup/`.
   - `mv`: Move or rename files/directories.
     Example: `mv file.txt new_name.txt`.
   - `touch`: Create an empty file or update the timestamp of a file.
     Example: `touch file.txt`.

2. **File Viewing and Editing**
   - `cat`: Display file content.
     Example: `cat file.txt`.
   - `less` / `more`: View file content page by page.
     Example: `less large_file.log`.
   - `head`: Display the first few lines of a file.
     Example: `head -n 10 file.log`.
   - `tail`: Display the last few lines of a file.
     Example: `tail -n 20 file.log`, `tail -f file.log` (follow live updates).
   - `nano` / `vim`: Text editors for editing files.
     Example: `vim file.txt`.

3. **System Monitoring and Process Management**
   - `top`: Display real-time system processes and resource usage.
   - `htop`: Interactive process viewer (enhanced version of `top`).
   - `ps`: Display running processes.
     Example: `ps aux` (show all processes).
   - `kill`: Terminate a process by PID.
     Example: `kill 1234`, `kill -9 1234` (force kill).
   - `systemctl`: Manage system services.
     Example: `systemctl start nginx`, `systemctl status nginx`.
   - `journalctl`: View system logs.
     Example: `journalctl -u nginx` (logs for the nginx service).

4. **Networking**
   - `ping`: Check network connectivity to a host.
     Example: `ping google.com`.
   - `curl` / `wget`: Download files or interact with web services.
     Example: `curl -O http://example.com/file.zip`, `wget http://example.com/file.zip`.
   - `netstat`: Display network connections, routing tables, and interface statistics.
     Example: `netstat -tuln` (show listening ports).
   - `ss`: Socket statistics (modern replacement for `netstat`).
     Example: `ss -tuln`.
   - `ifconfig` / `ip`: Configure and display network interfaces.
     Example: `ip addr show`.

5. **Package Management**
   - `apt` (Debian/Ubuntu): Package management tool.
     Example: `apt update`, `apt install nginx`.
   - `yum` / `dnf` (CentOS/RHEL): Package management tool.
     Example: `yum install nginx`.
   - `rpm`: Install RPM packages.
     Example: `rpm -i package.rpm`.

6. **File Permissions and Ownership**
   - `chmod`: Change file permissions.
     Example: `chmod 755 script.sh`.
   - `chown`: Change file ownership.
     Example: `chown user:group file.txt`.
   - `chgrp`: Change group ownership of a file.
     Example: `chgrp admin file.txt`.

7. **Disk and Storage Management**
   - `df`: Display disk space usage.
     Example: `df -h` (human-readable format).
   - `du`: Estimate file/directory space usage.
     Example: `du -sh /var/log` (summary of directory size).
   - `fdisk`: Partition table manipulator.
     Example: `fdisk -l` (list partitions).
   - `mount` / `umount`: Mount/unmount file systems.
     Example: `mount /dev/sdb1 /mnt`.

8. **Searching and Filtering**
   - `grep`: Search text using patterns.
     Example: `grep "error" logfile.log`.
   - `find`: Search for files/directories.
     Example: `find /var/log -name "*.log"`.
   - `awk`: Text processing and pattern scanning.
     Example: `awk '{print $1}' file.txt` (print the first column).
   - `sed`: Stream editor for text manipulation.
     Example: `sed 's/foo/bar/g' file.txt` (replace "foo" with "bar").

9. **Compression and Archiving**
   - `tar`: Archive files.
     Example: `tar -czvf archive.tar.gz folder/` (create a compressed archive).
   - `gzip` / `gunzip`: Compress/decompress files.
     Example: `gzip file.txt`, `gunzip file.txt.gz`.
   - `zip` / `unzip`: Compress/decompress ZIP files.
     Example: `zip archive.zip file.txt`, `unzip archive.zip`.

10. **User and Group Management**
    - `useradd` / `userdel`: Add/delete users.
      Example: `useradd john`, `userdel john`.
    - `passwd`: Change user password.
      Example: `passwd john`.
    - `groupadd` / `groupdel`: Add/delete groups.
      Example: `groupadd devops`, `groupdel devops`.

11. **SSH and Remote Access**
    - `ssh`: Connect to a remote server.
      Example: `ssh user@hostname`.
    - `scp`: Securely copy files between hosts.
      Example: `scp file.txt user@hostname:/path/`.
    - `rsync`: Synchronize files/directories between systems.
      Example: `rsync -avz /local/folder/ user@hostname:/remote/folder/`.

12. **Environment Variables**
    - `export`: Set environment variables.
      Example: `export PATH=$PATH:/new/path`.
    - `env`: Display environment variables.
    - `echo`: Print text or variables.
      Example: `echo $PATH`.

13. **Shell Scripting**
    - `sh` / `bash`: Execute shell scripts.
      Example: `bash script.sh`.
    - `chmod +x`: Make a script executable.
      Example: `chmod +x script.sh`.

14. **Logs and Debugging**
    - `dmesg`: Display kernel messages.
    - `tail -f`: Monitor log files in real-time.
      Example: `tail -f /var/log/syslog`.
    - `strace`: Trace system calls and signals.
      Example: `strace -p <PID>`.

15. **Version Control (Git)**
    - `git clone`: Clone a repository.
      Example: `git clone https://github.com/user/repo.git`.
    - `git pull`: Update local repository.
    - `git push`: Push changes to a remote repository.
    - `git status`: Check the status of the repository.

# ========================================
# End of Linux Commands for DevOps Engineers 🧑‍💻
# ========================================
