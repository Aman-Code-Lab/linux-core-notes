<h1 align="left">🐧 Linux Core Notes</h1>

<!-- 🧭 LINUX CORE NOTES INDEX -->
<h2 id="index">🧭 Linux Core Notes — Quick Navigation</h2>

<p align="center">
  <a href="#history"><img src="https://img.shields.io/badge/01-History%20of%20Linux-E95420?style=for-the-badge" alt="History of Linux"></a>
  <a href="#what-is-linux"><img src="https://img.shields.io/badge/02-What%20Is%20Linux-238636?style=for-the-badge" alt="What Is Linux"></a>
  <a href="#linux-vs-unix"><img src="https://img.shields.io/badge/03-Linux%20vs%20Unix-0078D4?style=for-the-badge" alt="Linux vs Unix"></a>
  <a href="#linux-everywhere"><img src="https://img.shields.io/badge/04-Linux%20Is%20Everywhere-2496ED?style=for-the-badge" alt="Linux Is Everywhere"></a>
  <a href="#distributions"><img src="https://img.shields.io/badge/05-Major%20Linux%20Distributions-A81D33?style=for-the-badge" alt="Major Linux Distributions"></a>
  <a href="#architecture"><img src="https://img.shields.io/badge/06-Linux%20Architecture-6F42C1?style=for-the-badge" alt="Linux Architecture"></a>
  <a href="#gnu-project"><img src="https://img.shields.io/badge/07-The%20GNU%20Project-FCC624?style=for-the-badge" alt="The GNU Project"></a>
  <a href="#understanding-shell"><img src="https://img.shields.io/badge/08-Understanding%20the%20Shell-333333?style=for-the-badge" alt="Understanding the Shell"></a>
  <a href="#popular-shells"><img src="https://img.shields.io/badge/09-Popular%20Linux%20Shells-4EAA25?style=for-the-badge" alt="Popular Linux Shells"></a>
  <a href="#kernel"><img src="https://img.shields.io/badge/10-The%20Linux%20Kernel-1793D1?style=for-the-badge" alt="The Linux Kernel"></a>
  <a href="#filesystem-hierarchy"><img src="https://img.shields.io/badge/11-Linux%20File%20System%20Hierarchy-0078D4?style=for-the-badge" alt="Linux File System Hierarchy"></a>
  <a href="#file-types"><img src="https://img.shields.io/badge/12-Basic%20Linux%20File%20Types-795548?style=for-the-badge" alt="Basic Linux File Types"></a>
  <a href="#users-groups"><img src="https://img.shields.io/badge/13-Linux%20Users%20and%20Groups-238636?style=for-the-badge" alt="Linux Users and Groups"></a>
  <a href="#permissions"><img src="https://img.shields.io/badge/14-Linux%20File%20Permissions-EA4B71?style=for-the-badge" alt="Linux File Permissions"></a>
  <a href="#boot-process"><img src="https://img.shields.io/badge/15-Linux%20Boot%20Process-FF6F00?style=for-the-badge" alt="Linux Boot Process"></a>
  <a href="#package-management"><img src="https://img.shields.io/badge/16-Linux%20Package%20Management-2496ED?style=for-the-badge" alt="Linux Package Management"></a>
  <a href="#process-management"><img src="https://img.shields.io/badge/17-Linux%20Process%20Management-6F42C1?style=for-the-badge" alt="Linux Process Management"></a>
  <a href="#environment-variables"><img src="https://img.shields.io/badge/18-Environment%20Variables-008080?style=for-the-badge" alt="Environment Variables"></a>
  <a href="#networking"><img src="https://img.shields.io/badge/19-Linux%20Networking%20Basics-0078D4?style=for-the-badge" alt="Linux Networking Basics"></a>
  <a href="#services"><img src="https://img.shields.io/badge/20-Linux%20Services%20and%20Daemons-555555?style=for-the-badge" alt="Linux Services and Daemons"></a>
  <a href="#filesystem-types"><img src="https://img.shields.io/badge/21-Linux%20File%20System%20Types-795548?style=for-the-badge" alt="Linux File System Types"></a>
  <a href="#redirection"><img src="https://img.shields.io/badge/22-Standard%20Input%2C%20Output%20%26%20Redirection-FF6F00?style=for-the-badge" alt="Standard Input, Output and Redirection"></a>
  <a href="#command-structure"><img src="https://img.shields.io/badge/23-Linux%20Command%20Structure-333333?style=for-the-badge" alt="Linux Command Structure"></a>
  <a href="#paths"><img src="https://img.shields.io/badge/24-Absolute%20vs%20Relative%20Paths-0078D4?style=for-the-badge" alt="Absolute vs Relative Paths"></a>
  <a href="#text-editors"><img src="https://img.shields.io/badge/25-Linux%20Text%20Editors-238636?style=for-the-badge" alt="Linux Text Editors"></a>
  <a href="#shell-scripting"><img src="https://img.shields.io/badge/26-Shell%20Scripting%20Basics-4EAA25?style=for-the-badge" alt="Shell Scripting Basics"></a>
  <a href="#advantages-limitations"><img src="https://img.shields.io/badge/27-Linux%20Advantages%20and%20Limitations-795548?style=for-the-badge" alt="Linux Advantages and Limitations"></a>
  <a href="#essential-commands"><img src="https://img.shields.io/badge/28-Essential%20Linux%20Commands%20Cheat%20Sheet-E95420?style=for-the-badge" alt="Essential Linux Commands Cheat Sheet"></a>
  <a href="#quick-revision"><img src="https://img.shields.io/badge/29-Quick%20Revision-6F42C1?style=for-the-badge" alt="Quick Revision"></a>
</p>

<hr>

<p align="center">
  <a href="#index"
     title="Back to Index"
     aria-label="Back to Index"
     style="display:inline-block; width:34px; height:34px; line-height:34px; border-radius:50%;
            background:#2563eb; color:#fff; text-align:center; text-decoration:none;
            font-size:18px; font-weight:bold; box-shadow:0 2px 8px rgba(0,0,0,.25);">
    ↑
  </a>
</p>

<h2 id="history">🕰️ 01. History of Linux</h2>

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

<p align="center">
  <a href="#index"
     title="Back to Index"
     aria-label="Back to Index"
     style="display:inline-block; width:34px; height:34px; line-height:34px; border-radius:50%;
            background:#2563eb; color:#fff; text-align:center; text-decoration:none;
            font-size:18px; font-weight:bold; box-shadow:0 2px 8px rgba(0,0,0,.25);">
    ↑
  </a>
</p>

---

<h2 id="what-is-linux">🧑‍💻 02. What Is Linux?</h2>

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

<p align="center">
  <a href="#index"
     title="Back to Index"
     aria-label="Back to Index"
     style="display:inline-block; width:34px; height:34px; line-height:34px; border-radius:50%;
            background:#2563eb; color:#fff; text-align:center; text-decoration:none;
            font-size:18px; font-weight:bold; box-shadow:0 2px 8px rgba(0,0,0,.25);">
    ↑
  </a>
</p>

---

<h2 id="linux-vs-unix">⚖️ 03. Linux vs Unix</h2>

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

<p align="center">
  <a href="#index"
     title="Back to Index"
     aria-label="Back to Index"
     style="display:inline-block; width:34px; height:34px; line-height:34px; border-radius:50%;
            background:#2563eb; color:#fff; text-align:center; text-decoration:none;
            font-size:18px; font-weight:bold; box-shadow:0 2px 8px rgba(0,0,0,.25);">
    ↑
  </a>
</p>

---

<h2 id="linux-everywhere">🌐 04. Linux Is Everywhere</h2>

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

<p align="center">
  <a href="#index"
     title="Back to Index"
     aria-label="Back to Index"
     style="display:inline-block; width:34px; height:34px; line-height:34px; border-radius:50%;
            background:#2563eb; color:#fff; text-align:center; text-decoration:none;
            font-size:18px; font-weight:bold; box-shadow:0 2px 8px rgba(0,0,0,.25);">
    ↑
  </a>
</p>

---

<h2 id="distributions">📦 05. Major Linux Distributions</h2>

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

<p align="center">
  <a href="#index"
     title="Back to Index"
     aria-label="Back to Index"
     style="display:inline-block; width:34px; height:34px; line-height:34px; border-radius:50%;
            background:#2563eb; color:#fff; text-align:center; text-decoration:none;
            font-size:18px; font-weight:bold; box-shadow:0 2px 8px rgba(0,0,0,.25);">
    ↑
  </a>
</p>

---

<h2 id="architecture">🏗️ 06. Linux Architecture: Kernel & Shell</h2>

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

<p align="center">
  <a href="#index"
     title="Back to Index"
     aria-label="Back to Index"
     style="display:inline-block; width:34px; height:34px; line-height:34px; border-radius:50%;
            background:#2563eb; color:#fff; text-align:center; text-decoration:none;
            font-size:18px; font-weight:bold; box-shadow:0 2px 8px rgba(0,0,0,.25);">
    ↑
  </a>
</p>

---

<h2 id="gnu-project">🧩 07. The GNU Project</h2>

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

<p align="center">
  <a href="#index"
     title="Back to Index"
     aria-label="Back to Index"
     style="display:inline-block; width:34px; height:34px; line-height:34px; border-radius:50%;
            background:#2563eb; color:#fff; text-align:center; text-decoration:none;
            font-size:18px; font-weight:bold; box-shadow:0 2px 8px rgba(0,0,0,.25);">
    ↑
  </a>
</p>

---

<h2 id="understanding-shell">🐚 08. Understanding the Shell</h2>

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

<p align="center">
  <a href="#index"
     title="Back to Index"
     aria-label="Back to Index"
     style="display:inline-block; width:34px; height:34px; line-height:34px; border-radius:50%;
            background:#2563eb; color:#fff; text-align:center; text-decoration:none;
            font-size:18px; font-weight:bold; box-shadow:0 2px 8px rgba(0,0,0,.25);">
    ↑
  </a>
</p>

---

<h2 id="popular-shells">🏁 09. Popular Linux Shells</h2>

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

<p align="center">
  <a href="#index"
     title="Back to Index"
     aria-label="Back to Index"
     style="display:inline-block; width:34px; height:34px; line-height:34px; border-radius:50%;
            background:#2563eb; color:#fff; text-align:center; text-decoration:none;
            font-size:18px; font-weight:bold; box-shadow:0 2px 8px rgba(0,0,0,.25);">
    ↑
  </a>
</p>

---

<h2 id="kernel">🧠 10. The Linux Kernel</h2>

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

<p align="center">
  <a href="#index"
     title="Back to Index"
     aria-label="Back to Index"
     style="display:inline-block; width:34px; height:34px; line-height:34px; border-radius:50%;
            background:#2563eb; color:#fff; text-align:center; text-decoration:none;
            font-size:18px; font-weight:bold; box-shadow:0 2px 8px rgba(0,0,0,.25);">
    ↑
  </a>
</p>

---

<h2 id="filesystem-hierarchy">📂 11. Linux File System Hierarchy</h2>

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

<h2>🧭 Useful Navigation Commands</h2>

<pre><code>pwd                 # Show the current directory
ls                  # List files and directories
ls -la              # List all entries with details
cd /home            # Move to /home
cd ~                # Go to your home directory
cd ..               # Move one directory up
cd /                # Go to the filesystem root
mkdir projects      # Create a directory
touch notes.txt     # Create an empty file</code></pre>

<p align="center">
  <a href="#index"
     title="Back to Index"
     aria-label="Back to Index"
     style="display:inline-block; width:34px; height:34px; line-height:34px; border-radius:50%;
            background:#2563eb; color:#fff; text-align:center; text-decoration:none;
            font-size:18px; font-weight:bold; box-shadow:0 2px 8px rgba(0,0,0,.25);">
    ↑
  </a>
</p>

<hr>

<h2 id="file-types">📄 12. Basic Linux File Types</h2>

<p>Linux supports different file types. Use <code>ls -l</code> to see the file-type symbol at the beginning of each entry.</p>

<table>
<tr><th align="left">Symbol</th><th align="left">Type</th><th align="left">Description</th></tr>
<tr><td><code>-</code></td><td>Regular File</td><td>Stores text, images, programs, and other data.</td></tr>
<tr><td><code>d</code></td><td>Directory</td><td>Contains files and other directories.</td></tr>
<tr><td><code>l</code></td><td>Symbolic Link</td><td>Points to another file or directory.</td></tr>
<tr><td><code>b</code></td><td>Block Device</td><td>Represents devices that support block-based I/O.</td></tr>
<tr><td><code>c</code></td><td>Character Device</td><td>Represents devices that provide character-based I/O.</td></tr>
<tr><td><code>p</code></td><td>Named Pipe</td><td>Allows processes to communicate through a FIFO.</td></tr>
<tr><td><code>s</code></td><td>Socket</td><td>Enables communication between processes.</td></tr>
</table>

<h3>🔍 File Type Commands</h3>

<pre><code>ls -l                       # View file-type symbols
file notes.txt              # Identify file content type
stat notes.txt              # Display file metadata
ln -s notes.txt link.txt    # Create a symbolic link</code></pre>

<p align="center">
  <a href="#index"
     title="Back to Index"
     aria-label="Back to Index"
     style="display:inline-block; width:34px; height:34px; line-height:34px; border-radius:50%;
            background:#2563eb; color:#fff; text-align:center; text-decoration:none;
            font-size:18px; font-weight:bold; box-shadow:0 2px 8px rgba(0,0,0,.25);">
    ↑
  </a>
</p>

<hr>

<h2 id="users-groups">👥 13. Linux Users and Groups</h2>

<p>Linux uses users and groups to control access to files, directories, and system resources.</p>

<table>
<tr><th align="left">Term</th><th align="left">Meaning</th></tr>
<tr><td>Root User</td><td>The superuser account, normally identified by UID 0.</td></tr>
<tr><td>Regular User</td><td>An account for everyday work with limited privileges.</td></tr>
<tr><td>Group</td><td>A collection of users who can share permissions.</td></tr>
<tr><td>UID</td><td>User ID that identifies a user account.</td></tr>
<tr><td>GID</td><td>Group ID that identifies a group.</td></tr>
<tr><td><code>sudo</code></td><td>Runs permitted commands with elevated privileges.</td></tr>
</table>

<h3>💻 User Management Commands</h3>

<pre><code>whoami                              # Show current username
id                                  # Show UID, GID, and groups
who                                 # Show logged-in users
groups                              # Show your groups
sudo useradd student                # Create a user
sudo passwd student                 # Set or change password
sudo groupadd developers            # Create a group
sudo usermod -aG developers student # Add user to group
sudo userdel student                # Delete a user account</code></pre>

<p><strong>⚠️ Note:</strong> These commands may require root privileges. Check your distribution's options before deleting accounts or changing groups.</p>

<p align="center">
  <a href="#index"
     title="Back to Index"
     aria-label="Back to Index"
     style="display:inline-block; width:34px; height:34px; line-height:34px; border-radius:50%;
            background:#2563eb; color:#fff; text-align:center; text-decoration:none;
            font-size:18px; font-weight:bold; box-shadow:0 2px 8px rgba(0,0,0,.25);">
    ↑
  </a>
</p>

<hr>

<h2 id="permissions">🔐 14. Linux File Permissions</h2>

<p>Permissions determine who can read, write, or execute a file. They are commonly assigned to the owner, group, and others.</p>

<table>
<tr><th align="left">Permission</th><th align="left">Symbol</th><th align="left">Numeric Value</th></tr>
<tr><td>Read</td><td><code>r</code></td><td>4</td></tr>
<tr><td>Write</td><td><code>w</code></td><td>2</td></tr>
<tr><td>Execute</td><td><code>x</code></td><td>1</td></tr>
</table>

<h3>🧠 Understanding Permission Numbers</h3>

<ul>
<li><strong>7 = 4 + 2 + 1:</strong> Read, write, and execute.</li>
<li><strong>6 = 4 + 2:</strong> Read and write.</li>
<li><strong>5 = 4 + 1:</strong> Read and execute.</li>
<li><strong>4:</strong> Read only.</li>
</ul>

<p>Example: <code>chmod 755 script.sh</code> gives the owner full permissions and gives the group and others read and execute permissions.</p>

<h3>💻 Permission Commands</h3>

<pre><code>ls -l                         # View permissions
chmod 755 script.sh           # Change permissions
chmod u+x script.sh           # Add execute permission for owner
chmod 644 notes.txt           # Owner writes; others can read
sudo chown student notes.txt  # Change file owner
sudo chgrp developers notes.txt # Change group ownership</code></pre>

<ul>
<li><code>chmod</code> changes permissions.</li>
<li><code>chown</code> changes ownership.</li>
<li><code>chgrp</code> changes group ownership.</li>
</ul>

<p align="center">
  <a href="#index"
     title="Back to Index"
     aria-label="Back to Index"
     style="display:inline-block; width:34px; height:34px; line-height:34px; border-radius:50%;
            background:#2563eb; color:#fff; text-align:center; text-decoration:none;
            font-size:18px; font-weight:bold; box-shadow:0 2px 8px rgba(0,0,0,.25);">
    ↑
  </a>
</p>

<hr>

<h2 id="boot-process">🚀 15. Linux Boot Process</h2>

<p>The boot process begins when the computer is powered on and continues until the operating system is ready to use.</p>

<table>
<tr>
<td align="center" width="20%"><strong>01 · BIOS / UEFI</strong><br><br>Initializes hardware and selects a boot device.</td>
<td align="center" width="20%"><strong>02 · Bootloader</strong><br><br>Loads the kernel and, where needed, the initial RAM filesystem.</td>
<td align="center" width="20%"><strong>03 · Kernel</strong><br><br>Initializes hardware, memory, and core subsystems.</td>
<td align="center" width="20%"><strong>04 · Init System</strong><br><br>Starts as PID 1; commonly systemd.</td>
<td align="center" width="20%"><strong>05 · Services</strong><br><br>Starts configured services and reaches the target state.</td>
</tr>
</table>

<p><strong>Boot sequence:</strong> BIOS/UEFI → Bootloader → Kernel → Init System → Services</p>

<h3>🔍 Useful Boot Commands</h3>

<pre><code>systemctl status       # View system state
systemctl get-default  # Show default systemd target
systemd-analyze        # Analyze boot time
journalctl -b          # View logs from current boot</code></pre>

<p><em>💡 Boot details vary by firmware, distribution, bootloader, and init system.</em></p>

<p align="center">
  <a href="#index"
     title="Back to Index"
     aria-label="Back to Index"
     style="display:inline-block; width:34px; height:34px; line-height:34px; border-radius:50%;
            background:#2563eb; color:#fff; text-align:center; text-decoration:none;
            font-size:18px; font-weight:bold; box-shadow:0 2px 8px rgba(0,0,0,.25);">
    ↑
  </a>
</p>

<hr>

<h2 id="package-management">📦 16. Linux Package Management</h2>

<p>A package manager installs, updates, and removes software while helping manage dependencies.</p>

<table>
<tr><th align="left">Tool</th><th align="left">Commonly Used On</th><th align="left">Purpose</th></tr>
<tr><td>APT</td><td>Ubuntu, Debian</td><td>Manages packages, repositories, and dependencies.</td></tr>
<tr><td>DPKG</td><td>Debian-based systems</td><td>Installs and manages local <code>.deb</code> packages.</td></tr>
<tr><td>DNF</td><td>Fedora and related systems</td><td>Manages RPM packages and dependencies.</td></tr>
<tr><td>RPM</td><td>Fedora, RHEL, and related systems</td><td>Works with <code>.rpm</code> packages.</td></tr>
</table>

<h3>💻 APT Commands</h3>

<pre><code>sudo apt update         # Refresh package lists
sudo apt upgrade        # Upgrade installed packages
sudo apt install nginx  # Install a package
sudo apt remove nginx   # Remove a package
apt search nginx        # Search for packages
dpkg -l                 # List installed packages</code></pre>

<h3>💻 DNF and RPM Commands</h3>

<pre><code>sudo dnf check-update   # Check for available updates
sudo dnf upgrade        # Upgrade installed packages
sudo dnf install nginx  # Install a package
sudo dnf remove nginx   # Remove a package
rpm -qa                 # List installed RPM packages</code></pre>

<p><strong>⚠️ Note:</strong> Use the package manager appropriate for your Linux distribution.</p>

<p align="center">
  <a href="#index"
     title="Back to Index"
     aria-label="Back to Index"
     style="display:inline-block; width:34px; height:34px; line-height:34px; border-radius:50%;
            background:#2563eb; color:#fff; text-align:center; text-decoration:none;
            font-size:18px; font-weight:bold; box-shadow:0 2px 8px rgba(0,0,0,.25);">
    ↑
  </a>
</p>

<hr>

<h2 id="process-management">⚙️ 17. Linux Process Management</h2>

<p>A process is a running instance of a program. Linux assigns each process a Process ID (PID) and records its relationship with its parent process.</p>

<table>
<tr><th align="left">Concept</th><th align="left">Meaning</th></tr>
<tr><td>PID</td><td>Unique process identifier.</td></tr>
<tr><td>PPID</td><td>Parent Process ID.</td></tr>
<tr><td>Foreground Process</td><td>Runs interactively with the shell.</td></tr>
<tr><td>Background Process</td><td>Runs without occupying the shell's foreground.</td></tr>
<tr><td>Running</td><td>Executing or ready to execute.</td></tr>
<tr><td>Sleeping</td><td>Waiting for an event or resource.</td></tr>
<tr><td>Stopped</td><td>Suspended, for example by a job-control signal.</td></tr>
<tr><td>Zombie</td><td>A terminated process whose exit status has not yet been collected by its parent.</td></tr>
</table>

<h3>💻 Process Commands</h3>

<pre><code>ps                       # Show terminal-associated processes
ps aux                   # Show detailed process information
top                      # Monitor processes interactively
pgrep firefox            # Find a process by name
kill PID                 # Request process termination
kill -9 PID              # Force termination as a last resort
jobs                     # List shell jobs
sleep 100 &amp;              # Start a background job
fg                       # Bring a job to the foreground
bg                       # Resume a stopped job in the background</code></pre>

<h3>📡 Common Signals</h3>

<ul>
<li><strong>SIGTERM (15):</strong> Requests graceful termination.</li>
<li><strong>SIGKILL (9):</strong> Forces termination; cannot be caught or ignored.</li>
<li><strong>SIGSTOP:</strong> Stops a process.</li>
<li><strong>SIGCONT:</strong> Resumes a stopped process.</li>
</ul>

<p align="center">
  <a href="#index"
     title="Back to Index"
     aria-label="Back to Index"
     style="display:inline-block; width:34px; height:34px; line-height:34px; border-radius:50%;
            background:#2563eb; color:#fff; text-align:center; text-decoration:none;
            font-size:18px; font-weight:bold; box-shadow:0 2px 8px rgba(0,0,0,.25);">
    ↑
  </a>
</p>

<hr>

<h2 id="environment-variables">🌱 18. Environment Variables</h2>

<p>Environment variables store values that programs and shells use to determine settings and behavior.</p>

<table>
<tr><th align="left">Variable</th><th align="left">Purpose</th></tr>
<tr><td><code>PATH</code></td><td>Directories searched for executable commands.</td></tr>
<tr><td><code>HOME</code></td><td>Current user's home directory.</td></tr>
<tr><td><code>USER</code></td><td>Commonly identifies the current username.</td></tr>
<tr><td><code>SHELL</code></td><td>Typically identifies the configured login shell.</td></tr>
<tr><td><code>PWD</code></td><td>Current working directory in the shell environment.</td></tr>
<tr><td><code>LANG</code></td><td>Controls the default locale for many programs.</td></tr>
</table>

<h3>💻 Environment Variable Commands</h3>

<pre><code>echo "$HOME"               # Display home directory
echo "$USER"               # Display username
echo "$SHELL"              # Display configured shell
echo "$PATH"               # Display command search paths
printenv                   # Display environment variables
export APP_ENV=development # Set a variable for child processes
unset APP_ENV              # Remove the variable</code></pre>

<p>💡 Use <code>$VARIABLE_NAME</code> to access a variable's value in the shell.</p>

<p align="center">
  <a href="#index"
     title="Back to Index"
     aria-label="Back to Index"
     style="display:inline-block; width:34px; height:34px; line-height:34px; border-radius:50%;
            background:#2563eb; color:#fff; text-align:center; text-decoration:none;
            font-size:18px; font-weight:bold; box-shadow:0 2px 8px rgba(0,0,0,.25);">
    ↑
  </a>
</p>

<hr>

<h2 id="networking">🌐 19. Linux Networking Basics</h2>

<p>Linux networking tools help inspect interfaces, IP addresses, routing, DNS, remote access, and active connections.</p>

<table>
<tr><th align="left">Concept</th><th align="left">Meaning</th></tr>
<tr><td>IP Address</td><td>Identifies a network interface using IPv4 or IPv6.</td></tr>
<tr><td>DNS</td><td>Resolves domain names to IP addresses and other DNS records.</td></tr>
<tr><td>SSH</td><td>Provides encrypted remote login and command execution.</td></tr>
<tr><td>Port</td><td>Identifies a communication endpoint used by network services.</td></tr>
<tr><td>Network Interface</td><td>A connection point such as Ethernet, Wi-Fi, or loopback.</td></tr>
<tr><td>Gateway</td><td>A router used to reach networks outside the local network.</td></tr>
</table>

<h3>💻 Networking Commands</h3>

<pre><code>ip addr                         # Show interfaces and IP addresses
ip route                        # Display routing table
ping example.com                # Test network reachability
getent hosts example.com        # Look up host information
ssh user@192.168.1.10           # Connect to a remote machine
ss -tuln                        # Show listening TCP/UDP sockets
curl -I https://example.com     # Inspect HTTP response headers</code></pre>

<p><em>💡 Some systems may require installing additional networking tools.</em></p>

<p align="center">
  <a href="#index"
     title="Back to Index"
     aria-label="Back to Index"
     style="display:inline-block; width:34px; height:34px; line-height:34px; border-radius:50%;
            background:#2563eb; color:#fff; text-align:center; text-decoration:none;
            font-size:18px; font-weight:bold; box-shadow:0 2px 8px rgba(0,0,0,.25);">
    ↑
  </a>
</p>

<hr>

<h2 id="services">🔧 20. Linux Services and Daemons</h2>

<p>A service is a system function managed by the operating system. A daemon is a background process that commonly provides a service without direct interactive input.</p>

<p>Many modern Linux distributions use <code>systemd</code> to manage services through <code>systemctl</code>.</p>

<h3>💻 Service Management Commands</h3>

<pre><code>systemctl status ssh                 # Check service status
sudo systemctl start ssh             # Start a service
sudo systemctl stop ssh              # Stop a service
sudo systemctl restart ssh           # Restart a service
sudo systemctl enable ssh            # Enable startup at boot
sudo systemctl disable ssh           # Disable startup at boot
systemctl list-units --type=service  # List loaded services
journalctl -u ssh                    # View service logs</code></pre>

<p><strong>⚠️ Note:</strong> Service names vary by distribution. An SSH server may use the name <code>ssh</code> or <code>sshd</code>.</p>

<p align="center">
  <a href="#index"
     title="Back to Index"
     aria-label="Back to Index"
     style="display:inline-block; width:34px; height:34px; line-height:34px; border-radius:50%;
            background:#2563eb; color:#fff; text-align:center; text-decoration:none;
            font-size:18px; font-weight:bold; box-shadow:0 2px 8px rgba(0,0,0,.25);">
    ↑
  </a>
</p>

<hr>

<h2 id="filesystem-types">💽 21. Linux File System Types</h2>

<p>A filesystem defines how data is organized, stored, and retrieved on a storage device.</p>

<table>
<tr><th align="left">Filesystem</th><th align="left">Typical Use</th><th align="left">Key Point</th></tr>
<tr><td>ext4</td><td>Linux installations</td><td>Widely used general-purpose Linux filesystem.</td></tr>
<tr><td>XFS</td><td>Linux servers</td><td>Designed for scalable, high-performance filesystems.</td></tr>
<tr><td>Btrfs</td><td>Linux desktops and servers</td><td>Supports snapshots and checksums.</td></tr>
<tr><td>FAT32</td><td>USB drives and removable media</td><td>Broad compatibility; individual files cannot exceed 4 GiB.</td></tr>
<tr><td>NTFS</td><td>Windows systems and shared storage</td><td>Windows' modern default filesystem.</td></tr>
<tr><td>exFAT</td><td>Flash drives and external storage</td><td>Supports large files and is widely compatible.</td></tr>
</table>

<h3>💻 Filesystem Commands</h3>

<pre><code>df -h              # Show filesystem space usage
du -sh ~/Documents # Show directory size
lsblk              # List block devices
findmnt            # Display mounted filesystems
mount              # Show or manage mounts</code></pre>

<p><strong>⚠️ Warning:</strong> Formatting a device can permanently erase data. Always verify the target device before performing disk operations.</p>

<p align="center">
  <a href="#index"
     title="Back to Index"
     aria-label="Back to Index"
     style="display:inline-block; width:34px; height:34px; line-height:34px; border-radius:50%;
            background:#2563eb; color:#fff; text-align:center; text-decoration:none;
            font-size:18px; font-weight:bold; box-shadow:0 2px 8px rgba(0,0,0,.25);">
    ↑
  </a>
</p>

<hr>

<h2 id="redirection">🔀 22. Standard Input, Output &amp; Redirection</h2>

<p>Linux commands use standard input, standard output, and standard error to receive data and produce results.</p>

<table>
<tr><th align="left">Stream</th><th align="left">File Descriptor</th><th align="left">Purpose</th></tr>
<tr><td>stdin</td><td>0</td><td>Standard input.</td></tr>
<tr><td>stdout</td><td>1</td><td>Standard output.</td></tr>
<tr><td>stderr</td><td>2</td><td>Standard error output.</td></tr>
</table>

<h3>💻 Pipes and Redirection</h3>

<pre><code>ls &gt; files.txt                  # Write output; overwrite existing contents
ls &gt;&gt; files.txt                 # Append output to a file
sort &lt; names.txt                # Read input from a file
ls missing.txt 2&gt; error.txt     # Redirect error output
command &gt; output.txt 2&gt;&amp;1      # Redirect stdout and stderr to one file
cat names.txt | sort            # Send output to another command
grep "error" app.log | wc -l    # Count matching lines</code></pre>

<h3>🧠 Remember These Operators</h3>

<ul>
<li><code>&gt;</code> Overwrites a file with redirected output.</li>
<li><code>&gt;&gt;</code> Appends output to a file.</li>
<li><code>&lt;</code> Takes input from a file.</li>
<li><code>|</code> Sends one command's output to another command.</li>
<li><code>2&gt;</code> Redirects standard error.</li>
</ul>

<p align="center">
  <a href="#index"
     title="Back to Index"
     aria-label="Back to Index"
     style="display:inline-block; width:34px; height:34px; line-height:34px; border-radius:50%;
            background:#2563eb; color:#fff; text-align:center; text-decoration:none;
            font-size:18px; font-weight:bold; box-shadow:0 2px 8px rgba(0,0,0,.25);">
    ↑
  </a>
</p>

<hr>

<h2 id="command-structure">⌨️ 23. Linux Command Structure</h2>

<p>A Linux command usually consists of a command name followed by options and arguments.</p>

<h3>🧩 General Syntax</h3>

<pre><code>command [options] [arguments]</code></pre>

<h3>🔍 Example</h3>

<pre><code>ls -l /home/student</code></pre>

<ul>
<li><strong>Command:</strong> <code>ls</code></li>
<li><strong>Option:</strong> <code>-l</code></li>
<li><strong>Argument:</strong> <code>/home/student</code></li>
<li><strong>Purpose:</strong> Lists the specified directory in long format.</li>
</ul>

<h3>💻 More Examples</h3>

<pre><code>pwd                       # Print working directory
ls -a                     # Show hidden entries
mkdir -p projects/linux   # Create nested directories
cp notes.txt backup.txt   # Copy a file
mv old.txt new.txt        # Rename or move a file
rm unwanted.txt           # Remove a file</code></pre>

<h3>🚦 Exit Status</h3>

<p>The exit status indicates whether a command succeeded. Zero usually means success; a non-zero value indicates failure.</p>

<pre><code>ls
echo $?                   # Display the previous command's exit status</code></pre>

<p align="center">
  <a href="#index"
     title="Back to Index"
     aria-label="Back to Index"
     style="display:inline-block; width:34px; height:34px; line-height:34px; border-radius:50%;
            background:#2563eb; color:#fff; text-align:center; text-decoration:none;
            font-size:18px; font-weight:bold; box-shadow:0 2px 8px rgba(0,0,0,.25);">
    ↑
  </a>
</p>

<hr>

<h2 id="paths">🧭 24. Absolute vs Relative Paths</h2>

<p>A path identifies the location of a file or directory in the filesystem.</p>

<table>
<tr><th align="left">Path Type</th><th align="left">Example</th><th align="left">Explanation</th></tr>
<tr><td>Absolute Path</td><td><code>/home/student/notes.txt</code></td><td>Starts from the filesystem root <code>/</code>.</td></tr>
<tr><td>Relative Path</td><td><code>documents/notes.txt</code></td><td>Resolved relative to the current working directory.</td></tr>
<tr><td>Current Directory</td><td><code>.</code></td><td>Represents the current directory.</td></tr>
<tr><td>Parent Directory</td><td><code>..</code></td><td>Represents the parent directory.</td></tr>
<tr><td>Home Directory</td><td><code>~</code></td><td>Shell shortcut for the current user's home directory.</td></tr>
</table>

<h3>💻 Path Practice</h3>

<pre><code>pwd
cd /home/student
cd documents
cd ..
cd ~/Downloads
cat /home/student/notes.txt</code></pre>

<p>💡 Absolute paths begin at <code>/</code>; relative paths depend on the current directory.</p>

<p align="center">
  <a href="#index"
     title="Back to Index"
     aria-label="Back to Index"
     style="display:inline-block; width:34px; height:34px; line-height:34px; border-radius:50%;
            background:#2563eb; color:#fff; text-align:center; text-decoration:none;
            font-size:18px; font-weight:bold; box-shadow:0 2px 8px rgba(0,0,0,.25);">
    ↑
  </a>
</p>

<hr>

<h2 id="text-editors">📝 25. Linux Text Editors</h2>

<p>Text editors let you create and modify configuration files, scripts, source code, and documentation directly in the terminal.</p>

<table>
<tr><th align="left">Editor</th><th align="left">Description</th></tr>
<tr><td>Nano</td><td>Beginner-friendly terminal editor with visible shortcuts.</td></tr>
<tr><td>Vim</td><td>Powerful modal editor with extensive editing capabilities.</td></tr>
<tr><td>Vi</td><td>Traditional Unix text editor available on many systems.</td></tr>
<tr><td>Emacs</td><td>Extensible editor with many additional features.</td></tr>
</table>

<h3>💻 Open and Edit Files</h3>

<pre><code>nano notes.txt          # Open a file in Nano
vim notes.txt           # Open a file in Vim
cat notes.txt           # Display file contents
less /var/log/syslog    # Read a file page by page</code></pre>

<h3>⌨️ Nano Shortcuts</h3>

<ul>
<li><strong>Ctrl + O:</strong> Save the file.</li>
<li><strong>Enter:</strong> Confirm the filename.</li>
<li><strong>Ctrl + X:</strong> Exit Nano.</li>
<li><strong>Ctrl + W:</strong> Search within the file.</li>
<li><strong>Ctrl + K:</strong> Cut a line.</li>
</ul>

<h3>⌨️ Vim Basics</h3>

<ul>
<li>Press <code>i</code> to enter insert mode.</li>
<li>Press <code>Esc</code> to return to normal mode.</li>
<li>Type <code>:w</code> to save.</li>
<li>Type <code>:q</code> to quit.</li>
<li>Type <code>:wq</code> to save and quit.</li>
<li>Type <code>:q!</code> to quit without saving changes.</li>
</ul>

<p align="center">
  <a href="#index"
     title="Back to Index"
     aria-label="Back to Index"
     style="display:inline-block; width:34px; height:34px; line-height:34px; border-radius:50%;
            background:#2563eb; color:#fff; text-align:center; text-decoration:none;
            font-size:18px; font-weight:bold; box-shadow:0 2px 8px rgba(0,0,0,.25);">
    ↑
  </a>
</p>

<hr>

<h2 id="shell-scripting">📜 26. Shell Scripting Basics</h2>

<p>A shell script is a text file containing commands executed by a shell. Scripts automate repetitive tasks using variables, conditions, loops, and functions.</p>

<h3>💻 Your First Shell Script</h3>

<p>Create a file named <code>hello.sh</code> with the following content:</p>

<pre><code>#!/usr/bin/env bash

name="Student"

echo "Hello, $name!"
echo "Welcome to Linux."</code></pre>

<p>Run the script:</p>

<pre><code>chmod +x hello.sh
./hello.sh</code></pre>

<h3>🔀 Conditions</h3>

<pre><code>#!/usr/bin/env bash

number=10

if [ "$number" -gt 5 ]; then
    echo "Number is greater than 5"
else
    echo "Number is 5 or less"
fi</code></pre>

<h3>🔁 Loops</h3>

<pre><code>#!/usr/bin/env bash

for i in 1 2 3 4 5; do
    echo "Number: $i"
done</code></pre>

<h3>🧩 Functions</h3>

<pre><code>#!/usr/bin/env bash

greet() {
    echo "Hello, Linux learner!"
}

greet</code></pre>

<h3>📌 Core Concepts</h3>

<ul>
<li><strong>Variables:</strong> Store values.</li>
<li><strong>Conditions:</strong> Make decisions.</li>
<li><strong>Loops:</strong> Repeat commands.</li>
<li><strong>Functions:</strong> Organize reusable commands.</li>
<li><strong>Shebang:</strong> Identifies the interpreter used to run a script.</li>
<li><strong>Exit Status:</strong> Indicates success or failure.</li>
</ul>

<p align="center">
  <a href="#index"
     title="Back to Index"
     aria-label="Back to Index"
     style="display:inline-block; width:34px; height:34px; line-height:34px; border-radius:50%;
            background:#2563eb; color:#fff; text-align:center; text-decoration:none;
            font-size:18px; font-weight:bold; box-shadow:0 2px 8px rgba(0,0,0,.25);">
    ↑
  </a>
</p>

<hr>

<h2 id="advantages-limitations">🔍 27. Linux Advantages and Limitations</h2>

<table>
<tr><th width="50%" align="left">✅ Advantages</th><th width="50%" align="left">⚠️ Limitations</th></tr>
<tr>
<td valign="top">

<ul>
<li>Open-source ecosystem.</li>
<li>Strong permission and security mechanisms.</li>
<li>Stable and reliable for many workloads.</li>
<li>Highly customizable.</li>
<li>Efficient on a wide range of hardware.</li>
<li>Powerful command-line tools.</li>
<li>Excellent support for programming, servers, and automation.</li>
<li>Many distributions are available without a purchase fee.</li>
</ul>

</td>
<td valign="top">

<ul>
<li>Some commercial applications are unavailable or have limited support.</li>
<li>Certain games and hardware may need extra configuration.</li>
<li>Beginners may face a learning curve.</li>
<li>Troubleshooting sometimes requires command-line knowledge.</li>
<li>Software availability varies by distribution.</li>
<li>Some professional applications work best on Windows or macOS.</li>
</ul>

</td>
</tr>
</table>

<p>💡 Linux is valuable for programming, system administration, cybersecurity education, cloud computing, and automation. The best operating system depends on your requirements.</p>

<p align="center">
  <a href="#index"
     title="Back to Index"
     aria-label="Back to Index"
     style="display:inline-block; width:34px; height:34px; line-height:34px; border-radius:50%;
            background:#2563eb; color:#fff; text-align:center; text-decoration:none;
            font-size:18px; font-weight:bold; box-shadow:0 2px 8px rgba(0,0,0,.25);">
    ↑
  </a>
</p>

<hr>

<h2 id="essential-commands">🛠️ 28. Essential Linux Commands Cheat Sheet</h2>

<table>
<tr><th align="left">Task</th><th align="left">Command</th></tr>
<tr><td>Show current directory</td><td><code>pwd</code></td></tr>
<tr><td>List files</td><td><code>ls -la</code></td></tr>
<tr><td>Change directory</td><td><code>cd directory</code></td></tr>
<tr><td>Create directory</td><td><code>mkdir projects</code></td></tr>
<tr><td>Create empty file</td><td><code>touch notes.txt</code></td></tr>
<tr><td>Copy file</td><td><code>cp source.txt copy.txt</code></td></tr>
<tr><td>Move or rename file</td><td><code>mv old.txt new.txt</code></td></tr>
<tr><td>Remove file</td><td><code>rm file.txt</code></td></tr>
<tr><td>Display file contents</td><td><code>cat file.txt</code></td></tr>
<tr><td>Search file contents</td><td><code>grep "word" file.txt</code></td></tr>
<tr><td>Find files</td><td><code>find . -name "*.txt"</code></td></tr>
<tr><td>Display disk space</td><td><code>df -h</code></td></tr>
<tr><td>Display memory usage</td><td><code>free -h</code></td></tr>
<tr><td>Show running processes</td><td><code>ps aux</code></td></tr>
<tr><td>Show network addresses</td><td><code>ip addr</code></td></tr>
<tr><td>Show command manual</td><td><code>man ls</code></td></tr>
<tr><td>Clear terminal screen</td><td><code>clear</code></td></tr>
</table>

<p><strong>⚠️ Safety:</strong> Use destructive commands such as <code>rm</code>, <code>chmod</code>, <code>chown</code>, and disk-formatting tools carefully. Never run unfamiliar commands with elevated privileges without understanding their effects.</p>

<p align="center">
  <a href="#index"
     title="Back to Index"
     aria-label="Back to Index"
     style="display:inline-block; width:34px; height:34px; line-height:34px; border-radius:50%;
            background:#2563eb; color:#fff; text-align:center; text-decoration:none;
            font-size:18px; font-weight:bold; box-shadow:0 2px 8px rgba(0,0,0,.25);">
    ↑
  </a>
</p>

<hr>

<h2 id="quick-revision">📚 Quick Revision</h2>

<table>
<tr><th align="left">Concept</th><th align="left">Meaning</th></tr>
<tr><td>Linux</td><td>An operating system ecosystem built around the Linux kernel.</td></tr>
<tr><td>Kernel</td><td>Manages hardware resources and essential system operations.</td></tr>
<tr><td>Shell</td><td>Interprets commands and launches programs.</td></tr>
<tr><td>Terminal</td><td>A text-based interface for interacting with a shell.</td></tr>
<tr><td>Distribution</td><td>A complete operating system built around the Linux kernel and supporting software.</td></tr>
<tr><td>GNU</td><td>A free-software project that provides many utilities used with Linux.</td></tr>
<tr><td>Root</td><td>The superuser account with extensive system privileges.</td></tr>
<tr><td>Filesystem</td><td>Organizes and manages how files and directories are stored.</td></tr>
<tr><td>chmod</td><td>Changes file permissions.</td></tr>
<tr><td>chown</td><td>Changes file ownership.</td></tr>
<tr><td>PID</td><td>Identifies a process.</td></tr>
<tr><td>PATH</td><td>Lists directories searched for executable commands.</td></tr>
<tr><td>systemctl</td><td>Controls and inspects systemd-managed services and units.</td></tr>
<tr><td>APT / DNF</td><td>Package management tools used by different Linux distributions.</td></tr>
<tr><td>SSH</td><td>Provides encrypted remote access.</td></tr>
<tr><td>Pipe (<code>|</code>)</td><td>Connects one command's output to another command's input.</td></tr>
</table>

<p align="center">
  <a href="#index"
     title="Back to Index"
     aria-label="Back to Index"
     style="display:inline-block; width:34px; height:34px; line-height:34px; border-radius:50%;
            background:#2563eb; color:#fff; text-align:center; text-decoration:none;
            font-size:18px; font-weight:bold; box-shadow:0 2px 8px rgba(0,0,0,.25);">
    ↑
  </a>
</p>

<hr>

<p align="left">
<img src="https://img.shields.io/badge/LINUX-LEARN%20BY%20DOING-E95420?style=for-the-badge&logo=linux&logoColor=white" alt="Linux Learn by Doing"/>
<img src="https://img.shields.io/badge/LEVEL-BEGINNER%20TO%20INTERMEDIATE-238636?style=for-the-badge" alt="Beginner to Intermediate"/>
</p>

<p align="left"><i>💡 Understand the concepts. Practice the commands. Build real skills.</i></p>
