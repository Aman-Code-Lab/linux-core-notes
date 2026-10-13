<h1 align="left">🐧 Linux Core Notes</h1>

<p align="left">
  <img src="https://img.shields.io/badge/LINUX-CORE%20NOTES-E95420?style=for-the-badge&logo=linux&logoColor=white"/>
  <img src="https://img.shields.io/badge/OPEN%20SOURCE-GNU-222222?style=for-the-badge&logo=gnu&logoColor=white"/>
  <img src="https://img.shields.io/badge/STATUS-LEARNING-238636?style=for-the-badge&logo=github&logoColor=white"/>
</p>

<p align="left">
  <i>Exploring Linux architecture, system internals, commands, and operating system fundamentals.</i>
</p>

---

<h2>🕰️ 01. History of Linux</h2>

<table>
<tr>
<td width="65%" valign="top">

Linux was created by <b>Linus Torvalds in 1991</b> as a Unix-like kernel. Inspired by Unix and developed with contributions from the open-source community, Linux became the foundation of many modern operating systems.

### 📌 Important Milestones

- **1969:** Unix development began at Bell Labs.
- **1983:** Richard Stallman launched the GNU Project to develop a free Unix-like operating system.
- **1991:** Linus Torvalds announced the Linux kernel.
- **1992:** The Linux kernel adopted the GNU GPL license.
- **Today:** Linux powers servers, cloud platforms, Android devices, supercomputers, and embedded systems.

</td>
<td width="35%" valign="middle" align="center">

<img src="https://img.shields.io/badge/CREATOR-LINUS%20TORVALDS-E95420?style=for-the-badge&logo=linux&logoColor=white"/>

<br><br>

<img src="https://img.shields.io/badge/STARTED-1991-238636?style=for-the-badge"/>

<br><br>

<img src="https://img.shields.io/badge/POWERED%20BY-OPEN%20SOURCE-222222?style=for-the-badge"/>

</td>
</tr>
</table>

---

<h2>🧑‍💻 02. What Is Linux?</h2>

<table>
<tr>
<td width="65%" valign="top">

### 🐧 Linux at a Glance

Linux is an open-source, Unix-like operating system ecosystem built around the Linux kernel. It is widely used in servers, smartphones, cloud computing, embedded devices, and software development.

### 🗝️ Key Features

- 🔓 **Open Source:** Users can inspect, modify, and distribute source code under the applicable license.
- 🛡️ **Secure & Stable:** Provides permissions, process isolation, and security mechanisms.
- 👥 **Multi-User:** Multiple users can access system resources with appropriate permissions.
- ⚡ **Multitasking:** Executes multiple processes efficiently.
- ⚙️ **Customizable:** Offers extensive control over system configuration.
- 🚀 **Resource Efficient:** Runs on a wide range of hardware.

</td>
<td width="35%" valign="middle" align="center">

<img src="https://skillicons.dev/icons?i=linux,bash,ubuntu,debian" alt="Linux ecosystem" width="100%"/>

<br><br>

<img src="https://img.shields.io/badge/POWER-FLEXIBILITY-161B22?style=for-the-badge&logo=linux&logoColor=white"/>

</td>
</tr>
</table>

---

<h2>⚖️ 03. Linux vs Unix</h2>

<p>
Linux is a Unix-like operating system kernel, while Unix refers to an older family of operating systems and related standards. Linux was inspired by Unix but was developed independently.
</p>

<table>
<tr>
<th align="left">Feature</th>
<th align="left">Linux</th>
<th align="left">Unix</th>
</tr>
<tr>
<td>Origin</td>
<td>Created by Linus Torvalds in 1991.</td>
<td>Originated at Bell Labs in 1969.</td>
</tr>
<tr>
<td>Source Code</td>
<td>Linux kernel source is publicly available.</td>
<td>Depends on the particular Unix system.</td>
</tr>
<tr>
<td>Licensing</td>
<td>Kernel uses the GNU GPL v2.</td>
<td>Often proprietary, depending on the implementation.</td>
</tr>
<tr>
<td>Examples</td>
<td>Ubuntu, Debian, Fedora, Arch Linux.</td>
<td>AIX, HP-UX, and Solaris.</td>
</tr>
<tr>
<td>Usage</td>
<td>Desktops, servers, cloud, embedded devices.</td>
<td>Enterprise servers and specialized systems.</td>
</tr>
</table>

---

<h2>🌐 04. Linux Is Everywhere</h2>

<table>
<tr>
<td width="33%" valign="top">

### 📱 Smartphones

<img src="https://img.shields.io/badge/ANDROID-LINUX%20KERNEL-3DDC84?style=for-the-badge&logo=android&logoColor=white"/>

Android uses a modified Linux kernel to manage hardware, processes, memory, and system resources.

</td>
<td width="33%" valign="top">

### ☁️ Cloud & IoT

<img src="https://img.shields.io/badge/CLOUD-AND%20IOT-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>

Linux powers cloud infrastructure, connected devices, and embedded systems.

</td>
<td width="33%" valign="top">

### 🚀 Supercomputers

<img src="https://img.shields.io/badge/HPC-LINUX-E95420?style=for-the-badge&logo=linux&logoColor=white"/>

Linux is the dominant operating system family in the TOP500 supercomputer rankings.

</td>
</tr>
</table>

---

<h2>📦 05. Major Linux Distributions</h2>

<p>
A Linux distribution combines the Linux kernel with system utilities, package managers, and applications to create a usable operating system.
</p>

<table>
<tr>
<td width="50%" valign="top">

### 🟠 Debian Family

<img src="https://img.shields.io/badge/DEBIAN-STABLE-A81D33?style=for-the-badge&logo=debian&logoColor=white"/>

**Debian**
- Known for stability and a large software repository.

<img src="https://img.shields.io/badge/UBUNTU-USER%20FRIENDLY-E95420?style=for-the-badge&logo=ubuntu&logoColor=white"/>

**Ubuntu**
- Based on Debian.
- Popular for desktops, development, and cloud servers.

</td>
<td width="50%" valign="top">

### 🔵 Red Hat Family

<img src="https://img.shields.io/badge/FEDORA-MODERN-51A2DA?style=for-the-badge&logo=fedora&logoColor=white"/>

**Fedora**
- Features modern Linux technologies.
- An important upstream for Red Hat Enterprise Linux.

<img src="https://img.shields.io/badge/RHEL-ENTERPRISE-EE0000?style=for-the-badge&logo=redhat&logoColor=white"/>

**Red Hat Enterprise Linux**
- Commercial enterprise Linux with professional support.

</td>
</tr>
<tr>
<td valign="top">

### 🟢 Enterprise Alternatives

**Rocky Linux**
- Provides an enterprise-compatible Linux platform.

**CentOS Stream**
- Tracks development ahead of future RHEL releases.

</td>
<td valign="top">

### 🟣 SUSE Family

**SUSE Linux Enterprise**
- Designed for business infrastructure and enterprise servers.
- Offers commercial support and lifecycle management.

</td>
</tr>
</table>

---

<h2>🏗️ 06. Linux Architecture: Kernel & Shell</h2>

<table>
<tr>
<td width="65%" valign="top">

### 🖥️ User Application Layer

Applications and user programs run here.

**Examples:** Browsers, text editors, office software.

### 🐚 Shell Interface

Interprets commands and launches programs.

**Examples:** Bash, Zsh, Fish.

### ⚙️ Kernel Space

The privileged core manages processes, memory, devices, networking, and system calls.

### 🔩 Hardware Layer

The physical components controlled through kernel subsystems and device drivers.

**Examples:** CPU, RAM, storage, network interfaces.

</td>
<td width="35%" valign="middle" align="center">

<img src="https://github.com/user-attachments/assets/00a5cfdd-80b2-4ede-89f2-fb8e402d8308" width="100%" alt="Linux Architecture Diagram"/>

</td>
</tr>
</table>

---

<h2>🧩 07. The GNU Project</h2>

<p>
The GNU Project was launched by <b>Richard Stallman in 1983</b> to create a free Unix-like operating system. GNU provides essential utilities and tools used by many Linux distributions.
</p>

<table>
<tr>
<th align="left">Component</th>
<th align="left">Purpose</th>
</tr>
<tr>
<td>GNU Coreutils</td>
<td>Provides commands such as ls, cp, mv, rm, and cat.</td>
</tr>
<tr>
<td>GCC</td>
<td>GNU Compiler Collection, used to compile programs.</td>
</tr>
<tr>
<td>GNU Bash</td>
<td>A widely used command-line shell.</td>
</tr>
<tr>
<td>GNU GRUB</td>
<td>A bootloader commonly used by Linux distributions.</td>
</tr>
<tr>
<td>GNU C Library</td>
<td>Provides standard C library functions for programs.</td>
</tr>
</table>

<p>
💡 <b>Remember:</b> Linux is technically the kernel; a complete Linux-based operating system commonly combines it with GNU utilities and other software.
</p>

---

<h2>🐚 08. Understanding the Shell</h2>

<p>
A shell is a command interpreter that allows users to interact with the operating system by entering commands or running scripts.
</p>

<table>
<tr>
<td valign="top">

<b>01 · ⌨️ Command Input</b>

The user enters a command in a terminal.

</td>
<td valign="top">

<b>02 · 🔍 Command Processing</b>

The shell interprets the command, arguments, variables, and operators.

</td>
</tr>
<tr>
<td valign="top">

<b>03 · ⚙️ Program Execution</b>

The shell launches the requested program, which may request kernel services.

</td>
<td valign="top">

<b>04 · 📤 Output</b>

The program's output or error messages appear in the terminal.

</td>
</tr>
</table>

---

<h2>🏁 09. Popular Linux Shells</h2>

<table>
<tr>
<td width="50%" valign="top">

### 🟢 Bash

- Stands for Bourne Again Shell.
- Widely used for Linux command-line work.
- Supports variables, loops, functions, and scripting.

### 🟣 Zsh

- Stands for Z Shell.
- Offers advanced completion and customization.
- Popular among developers.

</td>
<td width="50%" valign="top">

### 🐟 Fish

- Stands for Friendly Interactive Shell.
- Provides interactive suggestions and convenient defaults.
- Has syntax differences from Bash.

### 🐚 Csh / Tcsh

- C Shell and its enhanced version, Tcsh.
- Use a C-like command syntax.
- Found in some Unix and Linux environments.

</td>
</tr>
</table>

---

<h2>🧠 10. The Linux Kernel</h2>

<p>
The kernel is the core component of an operating system. It manages hardware resources and provides essential services through system calls.
</p>

<table>
<tr>
<th align="left">Function</th>
<th align="left">Description</th>
</tr>
<tr>
<td>Process Management</td>
<td>Creates, schedules, and terminates processes.</td>
</tr>
<tr>
<td>Memory Management</td>
<td>Allocates memory and manages virtual address spaces.</td>
</tr>
<tr>
<td>Device Management</td>
<td>Coordinates hardware access through device drivers.</td>
</tr>
<tr>
<td>File System Management</td>
<td>Provides interfaces for accessing files and directories.</td>
</tr>
<tr>
<td>Networking</td>
<td>Supports network protocols and communication.</td>
</tr>
<tr>
<td>System Calls</td>
<td>Provide controlled access to kernel services.</td>
</tr>
</table>

---

<h2>📂 11. Linux File System Hierarchy</h2>

<p>
Linux organizes files and directories in a tree structure that begins at the root directory <code>/</code>. Unlike Windows, Linux does not normally use separate drive letters such as C: and D:.
</p>

<table>
<tr>
<th align="left">Directory</th>
<th align="left">Purpose</th>
<th align="left">Example</th>
</tr>
<tr>
<td><code>/</code></td>
<td>Root of the entire filesystem.</td>
<td><code>/home</code></td>
</tr>
<tr>
<td><code>/home</code></td>
<td>Regular users' personal directories.</td>
<td><code>/home/student</code></td>
</tr>
<tr>
<td><code>/root</code></td>
<td>Home directory of the root user.</td>
<td><code>/root/.bashrc</code></td>
</tr>
<tr>
<td><code>/etc</code></td>
<td>System-wide configuration files.</td>
<td><code>/etc/hosts</code></td>
</tr>
<tr>
<td><code>/var</code></td>
<td>Variable data such as logs and caches.</td>
<td><code>/var/log</code></td>
</tr>
<tr>
<td><code>/tmp</code></td>
<td>Temporary files.</td>
<td><code>/tmp/test.txt</code></td>
</tr>
<tr>
<td><code>/usr</code></td>
<td>Many user applications, libraries, and shared resources.</td>
<td><code>/usr/bin</code></td>
</tr>
<tr>
<td><code>/bin</code></td>
<td>Essential user command programs on systems that provide this directory separately; often linked to <code>/usr/bin</code>.</td>
<td><code>/bin/ls</code></td>
</tr>
<tr>
<td><code>/dev</code></td>
<td>Device files representing hardware and virtual devices.</td>
<td><code>/dev/null</code></td>
</tr>
<tr>
<td><code>/proc</code></td>
<td>Virtual filesystem exposing process and kernel information.</td>
<td><code>/proc/cpuinfo</code></td>
</tr>
<tr>
<td><code>/boot</code></td>
<td>Bootloader files and kernel-related boot files.</td>
<td><code>/boot</code></td>
</tr>
<tr>
<td><code>/opt</code></td>
<td>Optional application software.</td>
<td><code>/opt/app</code></td>
</tr>
<tr>
<td><code>/mnt</code></td>
<td>Commonly used as a temporary mount point.</td>
<td><code>/mnt/drive</code></td>
</tr>
<tr>
<td><code>/media</code></td>
<td>Common mount point for removable media.</td>
<td><code>/media/usb</code></td>
</tr>
</table>

### 💻 Useful Navigation Commands

```bash
pwd                 # Show the current directory
ls                  # List files and directories
ls -la              # List all entries with details
cd /home            # Move to /home
cd ~                # Go to your home directory
cd ..               # Move one directory up
cd /                # Go to the filesystem root
mkdir projects      # Create a directory
touch notes.txt     # Create an empty file

---

<h2>📄 12. Basic Linux File Types</h2><p>
Linux represents files using different types. Run <code>ls -l</code> to see the file-type character at the beginning of each entry's permissions.
</p><table>
<tr>
<th align="left">Symbol</th>
<th align="left">Type</th>
<th align="left">Description</th>
</tr>
<tr>
<td><code>-</code></td>
<td>Regular File</td>
<td>Stores text, images, programs, and other data.</td>
</tr>
<tr>
<td><code>d</code></td>
<td>Directory</td>
<td>Contains entries referring to files and directories.</td>
</tr>
<tr>
<td><code>l</code></td>
<td>Symbolic Link</td>
<td>Points to another file or directory path.</td>
</tr>
<tr>
<td><code>b</code></td>
<td>Block Device</td>
<td>Represents devices that support block-based I/O.</td>
</tr>
<tr>
<td><code>c</code></td>
<td>Character Device</td>
<td>Represents devices that provide character-based I/O.</td>
</tr>
<tr>
<td><code>p</code></td>
<td>Named Pipe</td>
<td>Allows processes to communicate through a FIFO.</td>
</tr>
<tr>
<td><code>s</code></td>
<td>Socket</td>
<td>Enables communication between processes.</td>
</tr>
</table>🔍 Check File Types

ls -l               # View file-type symbols
file notes.txt      # Identify a file's content type
stat notes.txt      # Display file metadata
ln -s notes.txt link.txt  # Create a symbolic link

---

<h2>👥 13. Linux Users and Groups</h2><p>
Linux uses users and groups to control access to files, directories, and system resources.
</p><table>
<tr>
<th align="left">Term</th>
<th align="left">Meaning</th>
</tr>
<tr>
<td>Root User</td>
<td>The superuser account, normally identified by UID 0.</td>
</tr>
<tr>
<td>Regular User</td>
<td>An account for everyday work with limited privileges.</td>
</tr>
<tr>
<td>Group</td>
<td>A collection of users that can share access permissions.</td>
</tr>
<tr>
<td>UID</td>
<td>User ID that identifies a user account.</td>
</tr>
<tr>
<td>GID</td>
<td>Group ID that identifies a group.</td>
</tr>
<tr>
<td><code>sudo</code></td>
<td>Runs permitted commands with elevated privileges.</td>
</tr>
</table>💻 User Management Commands

whoami                      # Show current username
id                          # Show UID, GID, and groups
who                         # Show logged-in users
groups                      # Show your groups
sudo useradd student        # Create a user
sudo passwd student         # Set or change the user's password
sudo groupadd developers    # Create a group
sudo usermod -aG developers student  # Add user to group
sudo userdel student        # Delete a user account

⚠️ User-management commands may require root privileges. Check your distribution's options before deleting accounts or modifying groups.

---

<h2>🔐 14. Linux File Permissions</h2><p>
Linux permissions determine who can read, write, or execute a file. Permissions are commonly defined for the owner, group, and others.
</p><table>
<tr>
<th align="left">Permission</th>
<th align="left">Symbol</th>
<th align="left">Numeric Value</th>
</tr>
<tr>
<td>Read</td>
<td><code>r</code></td>
<td>4</td>
</tr>
<tr>
<td>Write</td>
<td><code>w</code></td>
<td>2</td>
</tr>
<tr>
<td>Execute</td>
<td><code>x</code></td>
<td>1</td>
</tr>
</table>🧠 Understanding Permission Numbers

- 7 = 4 + 2 + 1: Read, write, execute.
- 6 = 4 + 2: Read and write.
- 5 = 4 + 1: Read and execute.
- 4 = 4: Read only.

For example, <code>chmod 755 script.sh</code> gives the owner full permissions and gives the group and others read and execute permissions.

💻 Permission Commands

ls -l                       # View permissions
chmod 755 script.sh         # Change permissions
chmod u+x script.sh         # Add execute permission for owner
chmod 644 notes.txt         # Owner can write; others can read
sudo chown student notes.txt # Change file owner
sudo chgrp developers notes.txt # Change group ownership

Remember:

- <code>chmod</code> changes permissions.
- <code>chown</code> changes ownership.
- <code>chgrp</code> changes group ownership.

---

<h2>🚀 15. Linux Boot Process</h2><p>
The boot process starts when a computer is powered on and continues until the operating system is ready for use.
</p><table>
<tr>
<td align="center" width="20%">01

BIOS / UEFI

Initializes hardware and selects a boot device.

</td>
<td align="center" width="20%">02

Bootloader

Loads the Linux kernel and, where needed, the initial RAM filesystem.

</td>
<td align="center" width="20%">03

Kernel

Initializes hardware, memory, and core subsystems.

</td>
<td align="center" width="20%">04

Init System

Starts as PID 1; commonly systemd.

</td>
<td align="center" width="20%">05

Services

Starts configured services and brings the system to its target state.

</td>
</tr>
</table>🔍 Useful Boot Commands

systemctl status          # View system state
systemctl get-default     # Show default systemd target
systemd-analyze           # Analyze boot time
journalctl -b             # View logs from current boot

💡 Boot details vary depending on firmware, distribution, bootloader, and init system.

---

<h2>📦 16. Linux Package Management</h2><p>
A package manager installs, updates, and removes software while helping manage dependencies.
</p><table>
<tr>
<th align="left">Tool</th>
<th align="left">Commonly Used On</th>
<th align="left">Purpose</th>
</tr>
<tr>
<td>APT</td>
<td>Ubuntu, Debian</td>
<td>Manages packages using repositories and dependencies.</td>
</tr>
<tr>
<td>DPKG</td>
<td>Debian-based systems</td>
<td>Installs and manages local .deb packages.</td>
</tr>
<tr>
<td>DNF</td>
<td>Fedora and related systems</td>
<td>Manages RPM packages and dependencies.</td>
</tr>
<tr>
<td>RPM</td>
<td>Fedora, RHEL, and related systems</td>
<td>Works with .rpm packages.</td>
</tr>
</table>💻 APT Commands

sudo apt update              # Refresh package lists
sudo apt upgrade             # Upgrade installed packages
sudo apt install nginx       # Install a package
sudo apt remove nginx        # Remove a package
apt search nginx             # Search for packages
dpkg -l                      # List installed packages

💻 DNF and RPM Commands

sudo dnf check-update        # Check for available updates
sudo dnf upgrade             # Upgrade installed packages
sudo dnf install nginx       # Install a package
sudo dnf remove nginx        # Remove a package
rpm -qa                      # List installed RPM packages

⚠️ Use the package manager appropriate for your distribution.

---

<h2>⚙️ 17. Linux Process Management</h2><p>
A process is a running instance of a program. Linux assigns each process a Process ID (PID) and records its relationship with its parent process.
</p><table>
<tr>
<th align="left">Concept</th>
<th align="left">Meaning</th>
</tr>
<tr>
<td>PID</td>
<td>Unique process identifier.</td>
</tr>
<tr>
<td>PPID</td>
<td>Parent Process ID.</td>
</tr>
<tr>
<td>Foreground Process</td>
<td>Runs interactively with the shell.</td>
</tr>
<tr>
<td>Background Process</td>
<td>Runs without occupying the shell's foreground.</td>
</tr>
<tr>
<td>Running</td>
<td>Executing or ready to execute.</td>
</tr>
<tr>
<td>Sleeping</td>
<td>Waiting for an event or resource.</td>
</tr>
<tr>
<td>Stopped</td>
<td>Suspended, for example by a job-control signal.</td>
</tr>
<tr>
<td>Zombie</td>
<td>A terminated process whose exit status has not yet been collected by its parent.</td>
</tr>
</table>💻 Process Commands

ps                         # Show processes associated with the terminal
ps aux                     # Show detailed process information
top                        # Monitor processes interactively
pgrep firefox              # Find a process by name
kill PID                   # Send the default termination signal
kill -9 PID                # Force termination as a last resort
jobs                       # List shell jobs
sleep 100 &                # Start a background job
fg                         # Bring a job to the foreground
bg                         # Resume a stopped job in the background

📡 Common Signals

- SIGTERM (15): Requests graceful termination.
- SIGKILL (9): Forces termination; the process cannot catch or ignore it.
- SIGSTOP: Stops a process.
- SIGCONT: Resumes a stopped process.

---

<h2>🌱 18. Environment Variables</h2><p>
Environment variables store values that programs and shells can use to determine settings and behavior.
</p><table>
<tr>
<th align="left">Variable</th>
<th align="left">Purpose</th>
</tr>
<tr>
<td><code>PATH</code></td>
<td>Directories searched for executable commands.</td>
</tr>
<tr>
<td><code>HOME</code></td>
<td>Current user's home directory.</td>
</tr>
<tr>
<td><code>USER</code></td>
<td>Commonly identifies the current username.</td>
</tr>
<tr>
<td><code>SHELL</code></td>
<td>Typically identifies the user's configured login shell.</td>
</tr>
<tr>
<td><code>PWD</code></td>
<td>Current working directory in the shell environment.</td>
</tr>
<tr>
<td><code>LANG</code></td>
<td>Controls the default locale for many programs.</td>
</tr>
</table>💻 Environment Variable Commands

echo "$HOME"                    # Display home directory
echo "$USER"                    # Display username
echo "$SHELL"                   # Display configured shell
echo "$PATH"                    # Display command search paths
printenv                        # Display environment variables
export APP_ENV=development      # Set a variable for child processes
unset APP_ENV                   # Remove an exported variable

💡 Use <code>$VARIABLE_NAME</code> to access a variable's value in the shell.

---

<h2>🌐 19. Linux Networking Basics</h2><p>
Linux networking tools help inspect network interfaces, IP addresses, routing, DNS, remote access, and active connections.
</p><table>
<tr>
<th align="left">Concept</th>
<th align="left">Meaning</th>
</tr>
<tr>
<td>IP Address</td>
<td>Identifies a network interface using IPv4 or IPv6.</td>
</tr>
<tr>
<td>DNS</td>
<td>Resolves domain names to IP addresses and other DNS records.</td>
</tr>
<tr>
<td>SSH</td>
<td>Provides encrypted remote login and command execution.</td>
</tr>
<tr>
<td>Port</td>
<td>Identifies a communication endpoint used by network services.</td>
</tr>
<tr>
<td>Network Interface</td>
<td>A connection point such as Ethernet, Wi-Fi, or loopback.</td>
</tr>
<tr>
<td>Gateway</td>
<td>A router used to reach networks outside the local network.</td>
</tr>
</table>💻 Networking Commands

ip addr                         # Show network interfaces and IP addresses
ip route                        # Display routing table
ping example.com                # Test network reachability
getent hosts example.com        # Look up host information
ssh user@192.168.1.10           # Connect to a remote machine
ss -tuln                        # Show listening TCP/UDP sockets
curl -I https://example.com     # Inspect HTTP response headers

💡 Some systems may require installing additional networking tools.

---

<h2>🔧 20. Linux Services and Daemons</h2><p>
A service is a system function managed by the operating system. A daemon is a background process that commonly provides a service without direct interactive input.
</p><p>
Many modern Linux distributions use <code>systemd</code> to manage services through the <code>systemctl</code> command.
</p>💻 Service Management

systemctl status ssh           # Check SSH service status
sudo systemctl start ssh       # Start a service
sudo systemctl stop ssh        # Stop a service
sudo systemctl restart ssh     # Restart a service
sudo systemctl enable ssh      # Enable startup at boot
sudo systemctl disable ssh     # Disable startup at boot
systemctl list-units --type=service  # List loaded services
journalctl -u ssh              # View service logs

⚠️ Service names differ between distributions. For example, an SSH server service may be named <code>ssh</code> or <code>sshd</code>.

---

<h2>💽 21. Linux File System Types</h2><p>
A filesystem defines how data is organized, stored, and retrieved on a storage device.
</p><table>
<tr>
<th align="left">Filesystem</th>
<th align="left">Typical Use</th>
<th align="left">Key Point</th>
</tr>
<tr>
<td>ext4</td>
<td>Linux installations</td>
<td>Widely used general-purpose Linux filesystem.</td>
</tr>
<tr>
<td>XFS</td>
<td>Linux servers</td>
<td>Designed for scalable, high-performance filesystems.</td>
</tr>
<tr>
<td>Btrfs</td>
<td>Linux desktops and servers</td>
<td>Supports features such as snapshots and checksums.</td>
</tr>
<tr>
<td>FAT32</td>
<td>USB drives and removable media</td>
<td>Broad compatibility; individual files cannot exceed 4 GiB.</td>
</tr>
<tr>
<td>NTFS</td>
<td>Windows systems and shared storage</td>
<td>Windows' modern default filesystem.</td>
</tr>
<tr>
<td>exFAT</td>
<td>Flash drives and external storage</td>
<td>Supports large files and is widely compatible.</td>
</tr>
</table>💻 Filesystem Commands

df -h                  # Show filesystem space usage
du -sh ~/Documents     # Show directory size
lsblk                  # List block devices
findmnt                # Display mounted filesystems
mount                  # Show or manage mounts

⚠️ Formatting a device can permanently erase data. Verify the target device before performing any disk operation.

---

<h2>🔀 22. Standard Input, Output & Redirection</h2><p>
Linux commands use standard input, standard output, and standard error to receive data and produce results.
</p><table>
<tr>
<th align="left">Stream</th>
<th align="left">File Descriptor</th>
<th align="left">Purpose</th>
</tr>
<tr>
<td>stdin</td>
<td>0</td>
<td>Standard input.</td>
</tr>
<tr>
<td>stdout</td>
<td>1</td>
<td>Standard output.</td>
</tr>
<tr>
<td>stderr</td>
<td>2</td>
<td>Standard error output.</td>
</tr>
</table>💻 Pipes and Redirection

ls > files.txt                 # Write output; replace existing contents
ls >> files.txt                # Append output to a file
sort < names.txt               # Read input from a file
ls missing.txt 2> error.txt    # Redirect error output
command > output.txt 2>&1      # Redirect stdout and stderr to one file
cat names.txt | sort           # Send one command's output to another
grep "error" app.log | wc -l   # Count matching lines

🧠 Remember These Operators

- ">" overwrites a file with redirected output.
- ">>" appends output to a file.
- "<" takes input from a file.
- "|" sends one command's output to another command.
- "2>" redirects standard error.

---

<h2>⌨️ 23. Linux Command Structure</h2><p>
A Linux command usually consists of a command name followed by options and arguments.
</p>🧩 General Syntax

command [options] [arguments]

🔍 Example

ls -l /home/student

- Command: "ls"
- Option: "-l"
- Argument: "/home/student"
- Purpose: Lists the contents of the specified directory in long format.

💻 More Examples

pwd                       # Print working directory
ls -a                     # Show hidden entries
mkdir -p projects/linux   # Create nested directories
cp notes.txt backup.txt   # Copy a file
mv old.txt new.txt        # Rename or move a file
rm unwanted.txt           # Remove a file

🚦 Exit Status

The exit status indicates whether a command succeeded.

ls
echo $?                   # 0 usually means success; non-zero indicates failure

---

<h2>🧭 24. Absolute vs Relative Paths</h2><p>
A path identifies the location of a file or directory in the filesystem.
</p><table>
<tr>
<th align="left">Path Type</th>
<th align="left">Example</th>
<th align="left">Explanation</th>
</tr>
<tr>
<td>Absolute Path</td>
<td><code>/home/student/notes.txt</code></td>
<td>Starts from the filesystem root <code>/</code>.</td>
</tr>
<tr>
<td>Relative Path</td>
<td><code>documents/notes.txt</code></td>
<td>Resolved relative to the current working directory.</td>
</tr>
<tr>
<td>Current Directory</td>
<td><code>.</code></td>
<td>Represents the current directory.</td>
</tr>
<tr>
<td>Parent Directory</td>
<td><code>..</code></td>
<td>Represents the parent directory.</td>
</tr>
<tr>
<td>Home Directory</td>
<td><code>~</code></td>
<td>Shell shortcut for the current user's home directory.</td>
</tr>
</table>💻 Path Practice

pwd
cd /home/student
cd documents
cd ..
cd ~/Downloads
cat /home/student/notes.txt

💡 Absolute paths begin at "/"; relative paths depend on your current directory.

---

<h2>📝 25. Linux Text Editors</h2><p>
Text editors let you create and modify configuration files, scripts, source code, and documentation directly in the terminal.
</p><table>
<tr>
<th align="left">Editor</th>
<th align="left">Description</th>
</tr>
<tr>
<td>Nano</td>
<td>Beginner-friendly terminal editor with visible shortcuts.</td>
</tr>
<tr>
<td>Vim</td>
<td>Powerful modal editor with extensive editing capabilities.</td>
</tr>
<tr>
<td>Vi</td>
<td>Traditional Unix text editor available on many systems.</td>
</tr>
<tr>
<td>Emacs</td>
<td>Extensible editor with many additional features.</td>
</tr>
</table>💻 Open and Edit Files

nano notes.txt          # Open a file in Nano
vim notes.txt           # Open a file in Vim
cat notes.txt           # Display file contents
less /var/log/syslog    # Read a file page by page

⌨️ Nano Shortcuts

- Ctrl + O: Save the file.
- Enter: Confirm the filename.
- Ctrl + X: Exit Nano.
- Ctrl + W: Search within the file.
- Ctrl + K: Cut a line.

⌨️ Vim Basics

- Press i to enter insert mode.
- Press Esc to return to normal mode.
- Type ":w" to save.
- Type ":q" to quit.
- Type ":wq" to save and quit.
- Type ":q!" to quit without saving changes.

---

<h2>📜 26. Shell Scripting Basics</h2><p>
A shell script is a text file containing commands that a shell executes in sequence. Scripts automate repetitive tasks and combine commands, variables, conditions, loops, and functions.
</p>💻 Your First Shell Script

Create a file named "hello.sh":

#!/usr/bin/env bash

name="Student"

echo "Hello, $name!"
echo "Welcome to Linux."

Run it:

chmod +x hello.sh
./hello.sh

🔀 Conditions

#!/usr/bin/env bash

number=10

if [ "$number" -gt 5 ]; then
    echo "Number is greater than 5"
else
    echo "Number is 5 or less"
fi

🔁 Loops

#!/usr/bin/env bash

for i in 1 2 3 4 5; do
    echo "Number: $i"
done

🧩 Functions

#!/usr/bin/env bash

greet() {
    echo "Hello, Linux learner!"
}

greet

📌 Core Concepts

- Variables: Store values.
- Conditions: Make decisions.
- Loops: Repeat commands.
- Functions: Organize reusable commands.
- Shebang: Identifies the interpreter used to run a script.
- Exit Status: Indicates success or failure.

---

<h2>🔍 27. Linux Advantages and Limitations</h2><table>
<tr>
<th width="50%" align="left">✅ Advantages</th>
<th width="50%" align="left">⚠️ Limitations</th>
</tr>
<tr>
<td valign="top">- Open-source ecosystem.
- Strong permission and security mechanisms.
- Stable and reliable for many workloads.
- Highly customizable.
- Efficient on a wide range of hardware.
- Powerful command-line tools.
- Excellent support for programming, servers, and automation.
- Many distributions are available without a purchase fee.

</td>
<td valign="top">- Some commercial applications are unavailable or have limited support.
- Certain games and hardware may need extra configuration.
- Beginners may face a learning curve.
- Troubleshooting sometimes requires command-line knowledge.
- Software availability varies by distribution.
- Some professional applications work best on Windows or macOS.

</td>
</tr>
</table><p>
💡 Linux is especially valuable for programming, system administration, cybersecurity education, cloud computing, and automation, but the best operating system depends on your requirements.
</p>---

<h2>🛠️ 28. Essential Linux Commands Cheat Sheet</h2><table>
<tr>
<th align="left">Task</th>
<th align="left">Command</th>
</tr>
<tr>
<td>Show current directory</td>
<td><code>pwd</code></td>
</tr>
<tr>
<td>List files</td>
<td><code>ls -la</code></td>
</tr>
<tr>
<td>Change directory</td>
<td><code>cd directory</code></td>
</tr>
<tr>
<td>Create directory</td>
<td><code>mkdir projects</code></td>
</tr>
<tr>
<td>Create empty file</td>
<td><code>touch notes.txt</code></td>
</tr>
<tr>
<td>Copy file</td>
<td><code>cp source.txt copy.txt</code></td>
</tr>
<tr>
<td>Move or rename file</td>
<td><code>mv old.txt new.txt</code></td>
</tr>
<tr>
<td>Remove file</td>
<td><code>rm file.txt</code></td>
</tr>
<tr>
<td>Display file contents</td>
<td><code>cat file.txt</code></td>
</tr>
<tr>
<td>Search file contents</td>
<td><code>grep "word" file.txt</code></td>
</tr>
<tr>
<td>Find files</td>
<td><code>find . -name "*.txt"</code></td>
</tr>
<tr>
<td>Display disk space</td>
<td><code>df -h</code></td>
</tr>
<tr>
<td>Display memory usage</td>
<td><code>free -h</code></td>
</tr>
<tr>
<td>Show running processes</td>
<td><code>ps aux</code></td>
</tr>
<tr>
<td>Show network addresses</td>
<td><code>ip addr</code></td>
</tr>
<tr>
<td>Show command manual</td>
<td><code>man ls</code></td>
</tr>
<tr>
<td>Clear terminal screen</td>
<td><code>clear</code></td>
</tr>
</table>⚠️ Use destructive commands such as "rm", "chmod", "chown", and disk-formatting tools carefully. Never run unfamiliar commands with elevated privileges without understanding their effects.

---

<h2>📚 Quick Revision</h2><table>
<tr>
<th align="left">Concept</th>
<th align="left">Meaning</th>
</tr>
<tr>
<td>Linux</td>
<td>An operating system ecosystem built around the Linux kernel.</td>
</tr>
<tr>
<td>Kernel</td>
<td>Manages hardware resources and essential system operations.</td>
</tr>
<tr>
<td>Shell</td>
<td>Interprets commands and launches programs.</td>
</tr>
<tr>
<td>Terminal</td>
<td>A text-based interface for interacting with a shell.</td>
</tr>
<tr>
<td>Distribution</td>
<td>A complete operating system built around the Linux kernel and supporting software.</td>
</tr>
<tr>
<td>GNU</td>
<td>A free-software project that provides many utilities used with Linux.</td>
</tr>
<tr>
<td>Root</td>
<td>The superuser account with extensive system privileges.</td>
</tr>
<tr>
<td>Filesystem</td>
<td>Organizes and manages how files and directories are stored.</td>
</tr>
<tr>
<td>chmod</td>
<td>Changes file permissions.</td>
</tr>
<tr>
<td>chown</td>
<td>Changes file ownership.</td>
</tr>
<tr>
<td>PID</td>
<td>Identifies a process.</td>
</tr>
<tr>
<td>PATH</td>
<td>Lists directories searched for executable commands.</td>
</tr>
<tr>
<td>systemctl</td>
<td>Controls and inspects systemd-managed services and units.</td>
</tr>
<tr>
<td>APT / DNF</td>
<td>Package management tools used by different Linux distributions.</td>
</tr>
<tr>
<td>SSH</td>
<td>Provides encrypted remote access.</td>
</tr>
<tr>
<td>Pipe (<code>|</code>)</td>
<td>Connects one command's output to another command's input.</td>
</tr>
</table>---

<p align="left">
  <img src="https://img.shields.io/badge/LINUX-LEARN%20BY%20DOING-E95420?style=for-the-badge&logo=linux&logoColor=white"/>
  <img src="https://img.shields.io/badge/LEVEL-BEGINNER%20TO%20INTERMEDIATE-238636?style=for-the-badge"/>
</p><p align="left">
  <i>💡 Understand the concepts. Practice the commands. Build real skills.</i>
</p>
```Quick note: Your notes now cover Linux fundamentals, architecture, filesystem, permissions, users, booting, packages, processes, networking, services, scripting, and practical commands—all in one organized reference.
