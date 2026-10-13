<div align="center">

# ⚡ LINUX COMMANDS VAULT
### 💻 The Ultimate Linux Cheat Sheet

<img src="https://img.shields.io/badge/Linux-Command%20Vault-black?style=for-the-badge&logo=linux&logoColor=white"/>
<img src="https://img.shields.io/badge/Level-Beginner%20to%20Advanced-00C7B7?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Focus-Coding%20%7C%20AI%2FML-blue?style=for-the-badge"/>

**One vault. Essential commands. Unlimited possibilities. 🚀**

*A practical Linux reference for coding, programming, system administration,
networking, DevOps, and AI/ML development.*

</div>

---

## 📚 TABLE OF CONTENTS

<!-- ⚡ LINUX COMMANDS — BADGE INDEX -->

<h2 align="center">⚡ LINUX COMMANDS NAVIGATION</h2>

<p align="center">
  <a href="#-1-directory-navigation"><img src="https://img.shields.io/badge/📁_01_Directory_Navigation-blue?style=for-the-badge" alt="Directory Navigation"></a>
  <a href="#️-2-file-and-directory-management"><img src="https://img.shields.io/badge/🛠️_02_File_Management-green?style=for-the-badge" alt="File Management"></a>
  <a href="#-3-text-processing-and-search"><img src="https://img.shields.io/badge/📄_03_Text_Processing-orange?style=for-the-badge" alt="Text Processing"></a>
  <a href="#-4-pipes-and-redirection"><img src="https://img.shields.io/badge/🔗_04_Pipes_&_Redirection-purple?style=for-the-badge" alt="Pipes and Redirection"></a>
  <a href="#-5-file-search-and-storage"><img src="https://img.shields.io/badge/🔍_05_File_Search-blueviolet?style=for-the-badge" alt="File Search"></a>
  <a href="#-6-permissions-and-ownership"><img src="https://img.shields.io/badge/🔐_06_Permissions-red?style=for-the-badge" alt="Permissions"></a>
  <a href="#-7-user-and-group-management"><img src="https://img.shields.io/badge/👤_07_User_Management-yellow?style=for-the-badge" alt="User Management"></a>
  <a href="#️-8-process-management"><img src="https://img.shields.io/badge/⚙️_08_Process_Management-orange?style=for-the-badge" alt="Process Management"></a>
  <a href="#️-9-system-information"><img src="https://img.shields.io/badge/🖥️_09_System_Information-blue?style=for-the-badge" alt="System Information"></a>
  <a href="#-10-package-management"><img src="https://img.shields.io/badge/📦_10_Package_Management-green?style=for-the-badge" alt="Package Management"></a>
  <a href="#-11-networking-commands"><img src="https://img.shields.io/badge/🌐_11_Networking-brightgreen?style=for-the-badge" alt="Networking"></a>
  <a href="#-12-ssh-and-remote-access"><img src="https://img.shields.io/badge/🔑_12_SSH_&_Remote_Access-purple?style=for-the-badge" alt="SSH and Remote Access"></a>
  <a href="#️-13-archives-and-compression"><img src="https://img.shields.io/badge/🗜️_13_Compression-orange?style=for-the-badge" alt="Compression"></a>
  <a href="#-14-environment-variables"><img src="https://img.shields.io/badge/🧠_14_Environment_Variables-blueviolet?style=for-the-badge" alt="Environment Variables"></a>
  <a href="#-15-bash-scripting"><img src="https://img.shields.io/badge/🐚_15_Bash_Scripting-green?style=for-the-badge" alt="Bash Scripting"></a>
  <a href="#-16-services-and-logs"><img src="https://img.shields.io/badge/⏰_16_Services_&_Logs-blue?style=for-the-badge" alt="Services and Logs"></a>
  <a href="#-17-disk-and-filesystem-management"><img src="https://img.shields.io/badge/💽_17_Disk_Management-red?style=for-the-badge" alt="Disk Management"></a>
  <a href="#-18-programming-and-development"><img src="https://img.shields.io/badge/🐍_18_Programming_Tools-brightgreen?style=for-the-badge" alt="Programming Tools"></a>
  <a href="#-19-git-and-github"><img src="https://img.shields.io/badge/🌿_19_Git_&_GitHub-green?style=for-the-badge" alt="Git and GitHub"></a>
  <a href="#-20-docker-basics"><img src="https://img.shields.io/badge/🐳_20_Docker-blue?style=for-the-badge" alt="Docker"></a>
  <a href="#-21-advanced-linux-utilities"><img src="https://img.shields.io/badge/🧪_21_Advanced_Utilities-purple?style=for-the-badge" alt="Advanced Utilities"></a>
  <a href="#-22-common-linux-troubleshooting"><img src="https://img.shields.io/badge/🚨_22_Troubleshooting-red?style=for-the-badge" alt="Troubleshooting"></a>
  <a href="#-23-terminal-shortcuts"><img src="https://img.shields.io/badge/⚡_23_Terminal_Shortcuts-orange?style=for-the-badge" alt="Terminal Shortcuts"></a>
</p>

---

# 📁 1. DIRECTORY NAVIGATION

<details open>
<summary><b>🔹 Essential Navigation Commands</b></summary>

| Command | Description |
|---|---|
| `pwd` | Show current working directory |
| `ls` | List files and directories |
| `ls -a` | Show hidden files |
| `ls -l` | Show detailed file information |
| `ls -lh` | Show readable file sizes |
| `ls -la` | Show all files with details |
| `ls -R` | List directories recursively |
| `cd folder` | Enter a directory |
| `cd ..` | Move to parent directory |
| `cd ../..` | Move up two directory levels |
| `cd ~` | Go to home directory |
| `cd /` | Go to filesystem root |
| `cd -` | Return to previous directory |
| `tree` | Display directory structure |
| `tree -L 2` | Display tree up to two levels |
| `realpath file` | Show absolute path |
| `basename /a/b/file.txt` | Extract filename |
| `dirname /a/b/file.txt` | Extract parent directory |

</details>

### 💡 Example

```bash
pwd
ls -la
mkdir linux-project
cd linux-project
pwd
```

---

# 🛠️ 2. FILE AND DIRECTORY MANAGEMENT

<details open>
<summary><b>🔹 Create, Copy, Move, Rename and Delete</b></summary>

| Command | Description |
|---|---|
| `mkdir folder` | Create a directory |
| `mkdir -p a/b/c` | Create nested directories |
| `touch file.txt` | Create an empty file |
| `cp a.txt b.txt` | Copy a file |
| `cp -r dir backup` | Copy a directory |
| `cp -i a.txt b.txt` | Ask before overwriting |
| `mv old.txt new.txt` | Rename a file |
| `mv file.txt folder/` | Move a file |
| `rm file.txt` | Delete a file |
| `rm -i file.txt` | Confirm before deleting |
| `rm -r folder` | Delete a directory recursively |
| `rmdir folder` | Delete an empty directory |
| `file document.pdf` | Identify file type |
| `stat file.txt` | Show file metadata |
| `ln -s target link` | Create symbolic link |
| `install -d project` | Create a directory |

</details>

### 💡 Example

```bash
mkdir -p project/src
touch project/src/main.py
cp project/src/main.py backup.py
mv backup.py main_backup.py
```

> ⚠️ **Safety:** Always verify the target before using `rm -r`. Avoid careless use of `rm -rf`, especially with administrator privileges.

---

# 📄 3. TEXT PROCESSING AND SEARCH

<details open>
<summary><b>🔹 Read, Search, Edit and Analyze Text</b></summary>

| Command | Description |
|---|---|
| `cat file.txt` | Display file contents |
| `less file.txt` | Read a file interactively |
| `more file.txt` | Read text page by page |
| `head file.txt` | Display first 10 lines |
| `head -n 20 file.txt` | Display first 20 lines |
| `tail file.txt` | Display last 10 lines |
| `tail -n 20 file.txt` | Display last 20 lines |
| `tail -f app.log` | Follow new log entries |
| `grep "error" file.txt` | Search for text |
| `grep -i "error" file.txt` | Search without case sensitivity |
| `grep -n "error" file.txt` | Show matching line numbers |
| `grep -r "TODO" project/` | Search recursively |
| `grep -v "debug" file.txt` | Exclude matching lines |
| `wc file.txt` | Count lines, words and bytes |
| `wc -l file.txt` | Count lines |
| `wc -w file.txt` | Count words |
| `sort names.txt` | Sort lines |
| `sort -n numbers.txt` | Sort numerically |
| `uniq file.txt` | Remove adjacent duplicates |
| `cut -d ',' -f 1 data.csv` | Extract a CSV field |
| `paste file1 file2` | Combine corresponding lines |
| `tr 'a-z' 'A-Z'` | Convert lowercase to uppercase |
| `sed 's/old/new/g' file.txt` | Replace text in output |
| `awk '{print $1}' file.txt` | Extract the first field |
| `diff file1 file2` | Compare two files |
| `tee output.txt` | Save and display output |
| `nl file.txt` | Number lines |
| `rev file.txt` | Reverse characters per line |

</details>

### 💡 Example: Find Errors in Logs

```bash
grep -in "error" app.log
```

### 💡 Example: Monitor Live Logs

```bash
tail -f app.log
```

### 💡 Example: Count Python Files' Lines

```bash
wc -l main.py
```

---

# 🔗 4. PIPES AND REDIRECTION

<details open>
<summary><b>🔹 Connect Commands and Control Output</b></summary>

| Symbol | Description |
|---|---|
| `>` | Write output, overwriting the file |
| `>>` | Append output to a file |
| `<` | Read input from a file |
| `2>` | Redirect error output |
| `2>>` | Append error output |
| `2>&1` | Redirect errors to standard output |
| `\|` | Send output to another command |
| `&&` | Run the next command if successful |
| `\|\|` | Run the next command if unsuccessful |
| `;` | Run commands sequentially |
| `&` | Run a command in the background |
| `tee file.txt` | Display and save output |
| `xargs` | Build commands from input |
| `/dev/null` | Discard output |

</details>

### 💡 Examples

```bash
ls -la > files.txt
```

```bash
echo "Linux Notes" >> notes.txt
```

```bash
ps aux | grep python
```

```bash
mkdir project && cd project
```

```bash
command > output.log 2>&1
```

```bash
command 2>/dev/null
```

---

# 🔍 5. FILE SEARCH AND STORAGE

<details open>
<summary><b>🔹 Find Files and Check Disk Usage</b></summary>

| Command | Description |
|---|---|
| `find . -name "file.txt"` | Find a file by name |
| `find . -iname "*.pdf"` | Search case-insensitively |
| `find . -type f` | Find regular files |
| `find . -type d` | Find directories |
| `find . -empty` | Find empty files and directories |
| `find . -size +100M` | Find files larger than 100 MB |
| `find . -mtime -7` | Find recently modified files |
| `find . -maxdepth 2 -type f` | Limit search depth |
| `locate file.txt` | Search an indexed file database |
| `which python3` | Locate a command in PATH |
| `command -v python3` | Check command availability |
| `whereis python3` | Locate binary and documentation |
| `du -sh folder/` | Show total directory size |
| `du -h --max-depth=1 .` | Summarize subdirectory sizes |
| `df -h` | Show filesystem space |
| `df -i` | Show inode usage |
| `lsblk` | List block devices |
| `lsblk -f` | Show filesystem information |
| `findmnt` | Show mounted filesystems |

</details>

### 💡 Example: Find Every Python File

```bash
find . -type f -name "*.py"
```

### 💡 Example: Find Large Files

```bash
find . -type f -size +100M
```

### 💡 Example: Check Storage

```bash
df -h
du -sh ~/Downloads
```

---

# 🔐 6. PERMISSIONS AND OWNERSHIP

<details open>
<summary><b>🔹 Linux Permission Management</b></summary>

| Command | Description |
|---|---|
| `chmod 644 file.txt` | Owner writes; everyone reads |
| `chmod 755 script.sh` | Owner has full access; others read and execute |
| `chmod +x script.sh` | Add execute permission |
| `chmod u+w file.txt` | Add owner write permission |
| `chmod g-w file.txt` | Remove group write permission |
| `chmod -R u+rwX folder/` | Change permissions recursively |
| `chown user file.txt` | Change file owner |
| `chown user:group file.txt` | Change owner and group |
| `chown -R user:group folder/` | Change ownership recursively |
| `chgrp group file.txt` | Change group ownership |
| `umask` | Display default permission mask |
| `getfacl file.txt` | Display access control lists |
| `setfacl -m u:user:r file.txt` | Add an ACL entry |
| `sudo command` | Run a command with elevated privileges |
| `sudo -l` | List your sudo permissions |
| `passwd` | Change your password |

</details>

### 🧠 Permission Values

| Permission | Value |
|---|---:|
| Read (`r`) | 4 |
| Write (`w`) | 2 |
| Execute (`x`) | 1 |
| `rwx` | 7 |
| `rw-` | 6 |
| `r-x` | 5 |
| `r--` | 4 |

### 💡 Example

```bash
chmod 755 script.sh
./script.sh
```

> 🔒 Use `sudo` only when necessary. Never assume every command needs administrator privileges.

---

# 👤 7. USER AND GROUP MANAGEMENT

| Command | Description |
|---|---|
| `whoami` | Show current username |
| `id` | Display user and group IDs |
| `who` | Show logged-in users |
| `w` | Show logged-in users and activity |
| `groups` | Show group membership |
| `groups username` | Show a user's groups |
| `getent passwd` | Query user accounts |
| `getent group` | Query groups |
| `sudo adduser username` | Create a user on supported systems |
| `sudo useradd -m username` | Create a user with a home directory |
| `sudo usermod -aG group username` | Add a user to a supplementary group |
| `sudo passwd username` | Set another user's password |
| `sudo userdel username` | Delete a user |
| `sudo groupadd developers` | Create a group |
| `sudo groupdel developers` | Delete a group |
| `su - username` | Switch user |
| `last` | Display login history |
| `chage -l username` | Inspect password-aging information |

---

# ⚙️ 8. PROCESS MANAGEMENT

<details open>
<summary><b>🔹 Monitor and Control Processes</b></summary>

| Command | Description |
|---|---|
| `top` | Monitor running processes |
| `htop` | Interactive process monitor |
| `ps` | Show current shell processes |
| `ps aux` | Display a detailed process snapshot |
| `ps -ef` | Display processes in full format |
| `pgrep python` | Find Python process IDs |
| `pgrep -a python` | Display matching commands |
| `pidof nginx` | Find process IDs by program name |
| `kill PID` | Request process termination |
| `kill -9 PID` | Force termination |
| `pkill process_name` | Signal processes by name |
| `killall process_name` | Signal matching processes by name |
| `jobs` | List shell jobs |
| `bg %1` | Resume a job in the background |
| `fg %1` | Bring a job to the foreground |
| `nohup command &` | Run a command independently of terminal logout |
| `nice -n 10 command` | Start with adjusted priority |
| `renice 5 -p PID` | Adjust process priority |
| `watch -n 2 free -h` | Repeat a command |
| `time command` | Measure execution time |
| `lsof` | List open files |
| `fuser -v file` | Identify processes using a resource |
| `ulimit -a` | Display shell resource limits |

</details>

### 💡 Example: Find and Stop a Process

```bash
pgrep -a python
kill PID
```

Replace `PID` with the actual process ID.

**Important:** Use `kill -9 PID` only if normal termination fails.

---

# 🖥️ 9. SYSTEM INFORMATION

| Command | Description |
|---|---|
| `uname -a` | Display system and kernel information |
| `uname -r` | Show kernel version |
| `cat /etc/os-release` | Identify Linux distribution |
| `hostname` | Display hostname |
| `hostnamectl` | Display system identity |
| `uptime` | Show uptime and load averages |
| `date` | Display current date and time |
| `timedatectl` | Inspect time configuration |
| `lscpu` | Display CPU information |
| `lsmem` | Display memory layout |
| `free -h` | Show memory usage |
| `vmstat 1` | Monitor virtual memory statistics |
| `lspci` | List PCI devices |
| `lsusb` | List USB devices |
| `lsmod` | List loaded kernel modules |
| `dmesg` | Display kernel messages |
| `env` | Display environment variables |
| `printenv HOME` | Display the HOME variable |
| `getconf LONG_BIT` | Display the environment's word size |

---

# 📦 10. PACKAGE MANAGEMENT

### 🟠 Ubuntu / Debian / Linux Mint

| Command | Description |
|---|---|
| `sudo apt update` | Refresh package lists |
| `sudo apt upgrade` | Upgrade installed packages |
| `sudo apt install git` | Install Git |
| `sudo apt remove git` | Remove a package |
| `sudo apt purge git` | Remove package and system configuration |
| `sudo apt autoremove` | Remove unused dependencies |
| `apt search python3` | Search packages |
| `apt show git` | Display package information |
| `dpkg -l` | List installed packages |

### 🔵 Fedora / RHEL

```bash
sudo dnf check-update
sudo dnf upgrade
sudo dnf install git
sudo dnf remove git
dnf search python3
dnf info git
rpm -qa
```

### 🟣 Arch Linux

```bash
sudo pacman -Syu
sudo pacman -S git
sudo pacman -R git
pacman -Ss python
```

### 🟢 Universal Application Managers

```bash
flatpak list
flatpak update
snap list
sudo snap refresh
```

> ⚠️ Use the package manager supported by your Linux distribution.

---

# 🌐 11. NETWORKING COMMANDS

<details open>
<summary><b>🔹 Network Configuration and Diagnostics</b></summary>

| Command | Description |
|---|---|
| `ip a` | Show network interfaces and IP addresses |
| `ip link` | Display network interfaces |
| `ip route` | Show routing table |
| `ip neigh` | Show neighbor table |
| `ip -s link` | Display interface statistics |
| `ping -c 4 example.com` | Test network reachability |
| `curl -I https://example.com` | Request HTTP headers |
| `curl -L URL` | Follow redirects |
| `wget URL` | Download a resource |
| `ss -tuln` | Show listening TCP and UDP sockets |
| `ss -tunap` | Inspect network sockets and processes |
| `dig example.com` | Query DNS |
| `nslookup example.com` | Look up DNS records |
| `host example.com` | Perform DNS lookup |
| `getent hosts example.com` | Resolve a hostname |
| `hostname -I` | Display assigned IP addresses |
| `nmcli device status` | Inspect NetworkManager devices |
| `traceroute example.com` | Trace network hops |
| `tracepath example.com` | Investigate a network path |
| `mtr example.com` | Monitor route and latency |
| `nc -vz example.com 443` | Test TCP connectivity |
| `lsof -i` | Inspect network-related open files |
| `tcpdump -i any` | Capture packets |
| `nmap 127.0.0.1` | Scan localhost |

</details>

### 💡 Example: Basic Network Troubleshooting

```bash
ip a
ip route
ping -c 4 1.1.1.1
ping -c 4 example.com
curl -I https://example.com
```

**Note:** Network scans and packet captures should be performed only on systems and networks you are authorized to test.

---

# 🔑 12. SSH AND REMOTE ACCESS

| Command | Description |
|---|---|
| `ssh user@host` | Connect to a remote machine |
| `ssh -p 2222 user@host` | Connect using a custom port |
| `ssh-keygen -t ed25519` | Generate an SSH key pair |
| `ssh-copy-id user@host` | Install a public key remotely |
| `scp file.txt user@host:/path/` | Copy a file to a remote host |
| `scp -r folder/ user@host:/path/` | Copy a directory remotely |
| `sftp user@host` | Start secure file transfer |
| `rsync -av source/ destination/` | Synchronize files |
| `ssh -v user@host` | Debug an SSH connection |
| `ssh -L 8080:localhost:80 user@host` | Set up local port forwarding |

### 💡 Example

```bash
ssh username@192.168.1.10
```

Replace the username and IP address with the correct remote account and host.

---

# 🗜️ 13. ARCHIVES AND COMPRESSION

| Command | Description |
|---|---|
| `tar -cf archive.tar folder/` | Create TAR archive |
| `tar -xf archive.tar` | Extract TAR archive |
| `tar -czf backup.tar.gz folder/` | Create compressed TAR archive |
| `tar -xzf backup.tar.gz` | Extract compressed TAR archive |
| `tar -tf archive.tar` | List TAR contents |
| `gzip file.txt` | Compress a file |
| `gunzip file.txt.gz` | Decompress a Gzip file |
| `zip -r archive.zip folder/` | Create ZIP archive |
| `unzip archive.zip` | Extract ZIP archive |
| `unzip -l archive.zip` | List ZIP contents |
| `xz file.txt` | Compress using XZ |
| `unxz file.txt.xz` | Decompress XZ |
| `zstd file.txt` | Compress using Zstandard |
| `sha256sum file.iso` | Calculate a SHA-256 checksum |

### 💡 Backup Example

```bash
tar -czf backup.tar.gz project/
```

### 💡 Extract Example

```bash
tar -xzf backup.tar.gz
```

---

# 🧠 14. ENVIRONMENT VARIABLES

| Command | Description |
|---|---|
| `env` | Display environment |
| `printenv` | Print environment variables |
| `echo "$HOME"` | Display home directory |
| `echo "$PATH"` | Display executable search paths |
| `export NAME=value` | Export a variable |
| `unset NAME` | Remove a shell variable |
| `alias ll='ls -lah'` | Create a command alias |
| `unalias ll` | Remove an alias |
| `history` | Display command history |
| `source ~/.bashrc` | Reload Bash configuration |
| `type ls` | Identify a command |
| `command -v python3` | Check command availability |
| `which python3` | Locate a command in PATH |
| `bash --version` | Display Bash version |

### 💡 Example

```bash
export PROJECT_NAME="LinuxVault"
echo "$PROJECT_NAME"
```

---

# 🐚 15. BASH SCRIPTING

### 📝 Create a Script

```bash
nano hello.sh
```

```bash
#!/usr/bin/env bash

echo "Hello, Linux!"
```

### ▶️ Execute a Script

```bash
chmod +x hello.sh
./hello.sh
```

### 🔹 Variables

```bash
name="Aman"
echo "$name"
```

### 🔹 User Input

```bash
read -r -p "Enter your name: " name
echo "Hello, $name"
```

### 🔹 Conditions

```bash
if [ "$name" = "Aman" ]; then
    echo "Welcome!"
else
    echo "Hello!"
fi
```

### 🔹 For Loop

```bash
for i in 1 2 3 4 5; do
    echo "$i"
done
```

### 🔹 While Loop

```bash
count=1

while [ "$count" -le 5 ]; do
    echo "$count"
    count=$((count + 1))
done
```

### 🔹 Functions

```bash
greet() {
    echo "Hello, $1"
}

greet "Linux User"
```

### 🔹 Command-Line Arguments

```bash
echo "Script name: $0"
echo "First argument: $1"
echo "All arguments: $@"
echo "Argument count: $#"
```

### 🔹 Exit Status

```bash
ls
echo "$?"
```

### 🔹 Debugging

```bash
bash -n script.sh
bash -x script.sh
```

### 🔹 Script Quality

```bash
shellcheck script.sh
```

`ShellCheck` must be installed separately.

---

# ⏰ 16. SERVICES AND LOGS

### 🔹 Service Management

| Command | Description |
|---|---|
| `systemctl status SERVICE` | Inspect service status |
| `sudo systemctl start SERVICE` | Start a service |
| `sudo systemctl stop SERVICE` | Stop a service |
| `sudo systemctl restart SERVICE` | Restart a service |
| `sudo systemctl enable SERVICE` | Enable at boot |
| `sudo systemctl disable SERVICE` | Disable at boot |
| `sudo systemctl enable --now SERVICE` | Enable and start |
| `systemctl --failed` | Show failed units |
| `systemctl list-units` | List loaded units |
| `systemctl list-unit-files` | List installed unit files |

### 🔹 System Logs

| Command | Description |
|---|---|
| `journalctl` | Display system journal |
| `journalctl -f` | Follow live journal entries |
| `journalctl -b` | Show current boot logs |
| `journalctl -k` | Display kernel logs |
| `journalctl -u nginx` | Display service logs |
| `journalctl -p err` | Show error-level messages |
| `journalctl --since "1 hour ago"` | Filter by time |
| `dmesg` | Display kernel messages |

### 🔹 Scheduled Tasks

```bash
crontab -e
crontab -l
```

Example cron expression:

```text
0 9 * * * /home/user/script.sh
```

Runs the script daily at 9:00 AM according to the cron daemon's time configuration.

> ⚠️ Always check the service name and configuration before starting, stopping, or disabling system services.

---

# 💽 17. DISK AND FILESYSTEM MANAGEMENT

| Command | Description |
|---|---|
| `df -h` | Show filesystem capacity |
| `df -T` | Display filesystem types |
| `du -sh folder/` | Show directory size |
| `lsblk -f` | Inspect disks and filesystems |
| `blkid` | Display filesystem identifiers |
| `findmnt` | Show mounted filesystems |
| `mount` | Display mounted filesystems |
| `sudo mount DEVICE DIRECTORY` | Mount a device |
| `sudo umount DIRECTORY` | Unmount a filesystem |
| `sudo fdisk -l` | Inspect partition tables |
| `swapon --show` | Display active swap |
| `free -h` | Show memory and swap usage |
| `sync` | Flush pending filesystem changes |

### ⚠️ Advanced Disk Commands

The following commands can modify or erase data:

```bash
sudo mkfs.ext4 /dev/DEVICE_PARTITION
sudo fsck /dev/DEVICE_PARTITION
sudo mkswap /dev/DEVICE_PARTITION
sudo swapon /dev/DEVICE_PARTITION
```

**Never execute them blindly.** Replace placeholders only after verifying the correct device and following filesystem-specific instructions. Formatting creates a new filesystem and may destroy existing data.

---

# 🐍 18. PROGRAMMING AND DEVELOPMENT

## 🐍 Python

```bash
python3 --version
python3
python3 main.py
python3 -m pip --version
python3 -m venv .venv
source .venv/bin/activate
deactivate
python3 -m pip install -r requirements.txt
```

| Command | Purpose |
|---|---|
| `python3 --version` | Check Python version |
| `python3` | Open Python interpreter |
| `python3 main.py` | Execute a Python script |
| `python3 -m venv .venv` | Create virtual environment |
| `source .venv/bin/activate` | Activate environment |
| `deactivate` | Exit environment |
| `python3 -m pip list` | List installed packages |
| `python3 -m pip show PACKAGE` | Inspect a package |

## 🟦 C / C++

```bash
gcc --version
gcc -Wall -Wextra main.c -o main
./main

g++ --version
g++ -Wall -Wextra main.cpp -o main
./main
```

## ☕ Java

```bash
java --version
javac --version
javac Main.java
java Main
```

## 🟨 JavaScript / Node.js

```bash
node --version
npm --version
node app.js
npm install
npm run start
```

The `start` script must exist in `package.json`.

## 📝 Editors

```bash
nano file.txt
vim file.txt
code .
```

`code .` opens the current directory in Visual Studio Code when its command-line launcher is installed and available.

---

# 🌿 19. GIT AND GITHUB

| Command | Description |
|---|---|
| `git --version` | Check Git version |
| `git init` | Initialize repository |
| `git clone URL` | Clone a repository |
| `git status` | Check working tree |
| `git add file.txt` | Stage a file |
| `git add .` | Stage changes under current directory |
| `git commit -m "message"` | Create a commit |
| `git log --oneline` | Show compact history |
| `git diff` | Inspect unstaged changes |
| `git diff --staged` | Inspect staged changes |
| `git branch` | List local branches |
| `git switch main` | Switch branches |
| `git switch -c feature` | Create and switch branches |
| `git merge feature` | Merge a branch |
| `git pull` | Fetch and integrate remote changes |
| `git push` | Push commits |
| `git stash` | Temporarily save changes |
| `git restore file.txt` | Restore working-tree content |
| `git show HEAD` | Inspect latest commit |
| `git remote -v` | Display remotes |
| `git reflog` | Inspect reference history |

### 💡 Basic Git Workflow

```bash
git init
git add .
git commit -m "Initial commit"
git status
```

Configure your identity before your first commit if needed:

```bash
git config --global user.name "Your Name"
git config --global user.email "you@example.com"
```

---

# 🐳 20. DOCKER BASICS

| Command | Description |
|---|---|
| `docker --version` | Check Docker version |
| `docker info` | Display Docker information |
| `docker ps` | Show running containers |
| `docker ps -a` | Show all containers |
| `docker images` | List images |
| `docker pull nginx` | Download an image |
| `docker run -d nginx` | Start a container |
| `docker run -d -p 8080:80 nginx` | Publish a port |
| `docker logs CONTAINER` | Display container logs |
| `docker exec -it CONTAINER sh` | Open a shell inside a container |
| `docker stop CONTAINER` | Stop a container |
| `docker start CONTAINER` | Start a stopped container |
| `docker restart CONTAINER` | Restart a container |
| `docker inspect CONTAINER` | Inspect a container |
| `docker stats` | Display resource usage |
| `docker network ls` | List Docker networks |
| `docker volume ls` | List Docker volumes |
| `docker compose up -d` | Start a Compose application |
| `docker compose down` | Stop and remove Compose resources |

> 🐳 These commands require Docker or a compatible container runtime.

---

# 🧪 21. ADVANCED LINUX UTILITIES

| Command | Description |
|---|---|
| `strace command` | Trace system calls |
| `ltrace command` | Trace library calls |
| `lsof -i` | Inspect network-related open files |
| `lsof +L1` | Find open deleted files |
| `vmstat 1` | Monitor virtual memory |
| `iostat -xz 1` | Monitor CPU and disk I/O |
| `mpstat -P ALL 1` | Monitor CPU statistics |
| `pidstat 1` | Monitor process statistics |
| `sar -u 1 5` | Collect CPU activity statistics |
| `perf stat command` | Measure performance counters |
| `sysctl -a` | Display kernel parameters |
| `lsmod` | List loaded kernel modules |
| `modinfo MODULE` | Inspect a kernel module |
| `openssl version` | Check OpenSSL version |
| `sha256sum file` | Calculate SHA-256 hash |
| `gpg --verify file.sig file` | Verify a signature |
| `nft list ruleset` | Display nftables rules |
| `aa-status` | Inspect AppArmor status |
| `sestatus` | Inspect SELinux status |

Some commands require additional packages, permissions, or distribution-specific configuration.

---

# 🚨 22. COMMON LINUX TROUBLESHOOTING

<details>
<summary><b>❌ Error: Permission denied</b></summary>

```bash
ls -l file.txt
whoami
id
```

Inspect permissions and ownership before deciding whether elevated privileges are appropriate.

</details>

<details>
<summary><b>❌ Error: Command not found</b></summary>

```bash
command -v python3
echo "$PATH"
```

Check the command name, installation, and PATH configuration.

</details>

<details>
<summary><b>❌ Error: No such file or directory</b></summary>

```bash
pwd
ls -la
realpath file.txt
```

Verify the current directory and exact filename.

</details>

<details>
<summary><b>❌ Disk full</b></summary>

```bash
df -h
df -i
du -sh ~/Downloads
```

Check disk space, inode usage, and large directories before deleting anything.

</details>

<details>
<summary><b>❌ High RAM usage</b></summary>

```bash
free -h
top
ps aux --sort=-%mem | head
```

Identify memory-intensive processes before stopping them.

</details>

<details>
<summary><b>❌ High CPU usage</b></summary>

```bash
top
ps aux --sort=-%cpu | head
uptime
```

Inspect the busiest processes and system load.

</details>

<details>
<summary><b>❌ Network not working</b></summary>

```bash
ip a
ip route
ping -c 4 1.1.1.1
ping -c 4 example.com
```

These checks help distinguish interface, routing, and DNS problems. A failed ping alone does not prove that the internet is unavailable.

</details>

<details>
<summary><b>❌ Service not starting</b></summary>

```bash
systemctl status SERVICE_NAME
journalctl -u SERVICE_NAME -n 50
```

Replace `SERVICE_NAME` with the actual service name.

</details>

---

# ⚡ 23. TERMINAL SHORTCUTS

| Shortcut | Function |
|---|---|
| `Ctrl + C` | Interrupt the foreground process |
| `Ctrl + Z` | Suspend the foreground job |
| `Ctrl + D` | Send end-of-file input |
| `Ctrl + L` | Clear the terminal display |
| `Ctrl + A` | Move to the beginning of the line |
| `Ctrl + E` | Move to the end of the line |
| `Ctrl + U` | Delete text before the cursor |
| `Ctrl + K` | Delete text after the cursor |
| `Ctrl + W` | Delete the previous word |
| `Ctrl + R` | Search command history |
| `Tab` | Autocomplete commands and paths |
| `↑ / ↓` | Navigate command history |

Shortcuts can vary slightly by terminal and shell configuration.

---

# 🏆 BONUS: 20 COMMANDS EVERY LINUX BEGINNER SHOULD MASTER

```bash
pwd
ls -la
cd ..
mkdir project
touch file.txt
cp file.txt backup.txt
mv old.txt new.txt
rm file.txt
cat file.txt
less file.txt
grep "error" file.txt
find . -name "*.py"
chmod +x script.sh
sudo apt update
sudo apt install git
ps aux
top
df -h
free -h
ip a
```

---

# ⚠️ IMPORTANT SAFETY RULES

- Never run commands with `sudo` without understanding their purpose.
- Double-check paths before deleting or overwriting files.
- Avoid blindly copying commands from the internet.
- Never expose passwords, private SSH keys, API keys, or tokens.
- Back up important files before performing disk operations.
- Test destructive commands in a disposable virtual machine first.
- Use network diagnostic and security tools only on authorized systems.
- Prefer official documentation and verify commands for your distribution.

---

<div align="center">

## 🚀 KEEP LEARNING. KEEP BUILDING.

**Linux • Python • SQL • Git • Networking • DevOps • AI/ML**

*Master the terminal, one command at a time.*

⭐ If this cheat sheet helps you, consider starring the repository!

</div>
