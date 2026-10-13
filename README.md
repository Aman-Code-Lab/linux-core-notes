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

<h2 align="left">🧑‍💻 01. What Is Linux?</h2>

<table>
<tr>
<td width="65%" valign="top">

### 🐧 Linux at a Glance

Linux is an open-source, Unix-like operating system ecosystem built around the Linux kernel. It is widely used in servers, smartphones, cloud computing, embedded devices, and software development.

#### 🗝️ Key Features

- 🔓 **Open Source:** Users can inspect, modify, and distribute source code under the applicable license.
- 🛡️ **Secure & Stable:** Provides permissions, process isolation, and security mechanisms.
- 👥 **Multi-User:** Multiple users can access system resources with appropriate permissions.
- ⚡ **Multitasking:** Executes multiple processes efficiently.
- ⚙️ **Customizable:** Offers extensive control over system configuration.
- 🚀 **Resource Efficient:** Can run on a wide range of hardware, from lightweight devices to powerful servers.

</td>
<td width="35%" valign="middle" align="center">

<img src="https://skillicons.dev/icons?i=linux,bash,ubuntu,debian" alt="Linux ecosystem"/>

<br><br>

<img src="https://img.shields.io/badge/POWER-FLEXIBILITY-161B22?style=for-the-badge&logo=linux&logoColor=white"/>

<br><br>

<img src="https://img.shields.io/badge/BUILT-FOR%20EVERYONE-238636?style=for-the-badge&logo=opensourceinitiative&logoColor=white"/>

</td>
</tr>
</table>

---

<h2 align="left">🌐 02. Linux Is Everywhere</h2>

<table>
<tr>
<td width="33%" valign="top">

### 📱 Smartphones

<img src="https://img.shields.io/badge/ANDROID-LINUX%20KERNEL-3DDC84?style=for-the-badge&logo=android&logoColor=white"/>

Android uses a modified Linux kernel to manage hardware, processes, memory, and other system resources.

</td>
<td width="33%" valign="top">

### ☁️ Cloud & IoT

<img src="https://img.shields.io/badge/CLOUD-AND%20IOT-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>

Linux powers cloud infrastructure, connected devices, embedded systems, and many automotive computing platforms.

</td>
<td width="33%" valign="top">

### 🚀 Supercomputers

<img src="https://img.shields.io/badge/HPC-LINUX-E95420?style=for-the-badge&logo=linux&logoColor=white"/>

Linux dominates the TOP500 list of the world's most powerful supercomputers.

</td>
</tr>
</table>

---

<h2 align="left">⚖️ 03. Linux vs Windows</h2>

<table>
<tr>
<th width="50%" align="left">🪟 Microsoft Windows</th>
<th width="50%" align="left">🐧 Linux</th>
</tr>

<tr>
<td valign="top">

**💰 Licensing Model**

Primarily proprietary, with licensing depending on the product and edition.

**⚙️ Customization**

System customization is subject to the operating system's design and licensing.

**🛡️ Security**

Includes security features such as Microsoft Defender, access controls, and security policies.

**📦 Distribution**

Developed and distributed through Microsoft's Windows product ecosystem.

</td>

<td valign="top">

**🔓 Licensing Model**

The Linux kernel is open source under the GNU GPL, while distributions may combine software with different licenses.

**⚙️ Customization**

Extensive control over the kernel, shell, services, and system configuration.

**🛡️ Security**

Supports permissions, user isolation, SELinux, AppArmor, and other security mechanisms.

**📦 Distribution**

Available in many distributions designed for desktops, servers, cloud infrastructure, and specialized tasks.

</td>
</tr>
</table>

---

<h2 align="left">📦 04. Major Linux Distributions</h2>

<p align="left">
  A Linux distribution combines the Linux kernel with system utilities, software management tools, and other components to create a usable operating system.
</p>

<table>
<tr>
<td width="50%" valign="top">

### 🟠 Debian Family

<img src="https://img.shields.io/badge/DEBIAN-STABLE-A81D33?style=for-the-badge&logo=debian&logoColor=white"/>

**Debian**
- One of the oldest major Linux distributions.
- Known for stability and its large software repository.

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
- Serves as an important upstream for Red Hat Enterprise Linux.

<img src="https://img.shields.io/badge/RHEL-ENTERPRISE-EE0000?style=for-the-badge&logo=redhat&logoColor=white"/>

**Red Hat Enterprise Linux**
- Commercial enterprise Linux with professional support options.

</td>
</tr>

<tr>
<td width="50%" valign="top">

### 🟢 Enterprise Alternatives

<img src="https://img.shields.io/badge/ROCKY%20LINUX-ENTERPRISE-10B981?style=for-the-badge&logo=rockylinux&logoColor=white"/>

**Rocky Linux & CentOS**
- Rocky Linux provides an enterprise-compatible Linux platform.
- CentOS Stream tracks development ahead of future RHEL releases.

</td>
<td width="50%" valign="top">

### 🟣 SUSE Family

<img src="https://img.shields.io/badge/SUSE-ENTERPRISE-73BA25?style=for-the-badge&logo=suse&logoColor=white"/>

**SUSE Linux Enterprise**
- Enterprise Linux platform for servers and business infrastructure.
- Offers commercial support and lifecycle management.

</td>
</tr>
</table>

---

<h2 align="left">🏗️ 05. Linux Architecture: Kernel & Shell</h2>

<p align="left">
  <img src="https://github.com/user-attachments/assets/00a5cfdd-80b2-4ede-89f2-fb8e402d8308" width="85%" alt="Linux Architecture Diagram"/>
</p>

<table>
<tr>
<td width="50%" valign="top">

### 🖥️ User Application Layer

The layer where applications, command-line utilities, and user programs run.

**Examples:** Browsers, text editors, terminal applications.

</td>
<td width="50%" valign="top">

### 🐚 Shell Interface

The command interpreter that reads user input, processes commands, and launches programs.

**Examples:** Bash, Zsh, Fish.

</td>
</tr>

<tr>
<td width="50%" valign="top">

### ⚙️ Kernel Space

The privileged core that manages processes, memory, devices, networking, and system calls.

**Examples:** Process scheduling and memory allocation.

</td>
<td width="50%" valign="top">

### 🔩 Hardware Layer

The physical components controlled through kernel subsystems and device drivers.

**Examples:** CPU, RAM, storage, network interfaces.

</td>
</tr>
</table>

---

<h2 align="left">🐚 06. Understanding the Shell</h2>

<p align="left">
  <img src="https://img.shields.io/badge/SHELL-COMMAND%20INTERPRETER-238636?style=for-the-badge&logo=gnubash&logoColor=white"/>
</p>

<p align="left">
  A shell is a command interpreter that allows users to interact with the operating system by entering commands or running scripts.
</p>

<table>
<tr>
<td valign="top">

**01 · ⌨️ Command Input**

The user enters a command into a terminal.

</td>
<td valign="top">

**02 · 🔍 Command Processing**

The shell interprets the command, handles arguments, and prepares the program for execution.

</td>
</tr>
<tr>
<td valign="top">

**03 · ⚙️ Program Execution**

The shell launches the requested program. The program may use system calls to request kernel services.

</td>
<td valign="top">

**04 · 📤 Output**

The program's output or error messages are displayed in the terminal.

</td>
</tr>
</table>

---

<h2 align="left">🏁 07. Popular Linux Shells</h2>

<p align="left">
  <img src="https://github.com/user-attachments/assets/4fe27a61-764c-4896-b228-1a65aa7a80d4" width="85%" alt="Linux Shells Overview"/>
</p>

<table>
<tr>
<td width="50%" valign="top">

### 🟢 Bash

<img src="https://img.shields.io/badge/BASH-WIDELY%20USED-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white"/>

- Bourne Again Shell.
- Widely used for Linux command-line work.
- Supports scripting, variables, loops, and functions.

</td>
<td width="50%" valign="top">

### 🟣 Zsh

<img src="https://img.shields.io/badge/ZSH-CUSTOMIZABLE-674188?style=for-the-badge&logo=zsh&logoColor=white"/>

- Z Shell.
- Offers advanced completion and customization.
- Popular among developers.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🐟 Fish

<img src="https://img.shields.io/badge/FISH-USER%20FRIENDLY-00A6D6?style=for-the-badge&logo=fishshell&logoColor=white"/>

- Friendly Interactive Shell.
- Provides interactive suggestions and convenient defaults.
- Uses syntax that differs from Bash in several areas.

</td>
<td width="50%" valign="top">

### 🐚 Csh / Tcsh

<img src="https://img.shields.io/badge/CSH-C%20LIKE%20SYNTAX-64748B?style=for-the-badge&logo=linux&logoColor=white"/>

- C Shell and its enhanced version, Tcsh.
- Use a C-like command syntax.
- Found in some Unix and Linux environments.

</td>
</tr>
</table>

---

<h2 align="left">🧠 08. The Linux Kernel</h2>

<p align="left">
  <img src="https://img.shields.io/badge/KERNEL-SYSTEM%20CORE-E95420?style=for-the-badge&logo=linux&logoColor=white"/>
</p>

<p align="left">
  The kernel is the core component of an operating system. It manages hardware resources and provides essential services that applications use through system calls.
</p>

<p align="left">
  <img src="https://github.com/user-attachments/assets/977281fa-c97d-4d16-8a5a-ebaf506635a2" width="85%" alt="Linux Kernel Functions Diagram"/>
</p>

<table>
<tr>
<td width="50%" valign="top">

### ⚙️ Process Management

- Creates and terminates processes.
- Schedules processes for CPU time.
- Coordinates multitasking.

</td>
<td width="50%" valign="top">

### 🧠 Memory Management

- Allocates and frees memory.
- Manages virtual memory.
- Isolates process address spaces.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🔌 Device Management

- Communicates with hardware through drivers.
- Coordinates access to devices.
- Supports storage and network interfaces.

</td>
<td width="50%" valign="top">

### 🔐 System Calls

- Provide an interface between programs and kernel services.
- Allow controlled access to system resources.
- Support operations such as file access and process creation.

</td>
</tr>
</table>

---

<h2 align="left">📚 Quick Revision</h2>

<table>
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
<td>Distribution</td>
<td>A complete operating system built around the Linux kernel and supporting software.</td>
</tr>
<tr>
<td>Terminal</td>
<td>A text-based interface used to interact with a shell.</td>
</tr>
<tr>
<td>Root</td>
<td>The superuser account with extensive system privileges.</td>
</tr>
</table>

---

<p align="left">
  <img src="https://img.shields.io/badge/LEARNING-ONE%20COMMAND%20AT%20A%20TIME-238636?style=for-the-badge&logo=github&logoColor=white"/>
</p>

<p align="left">
  <i>💡 Understand the concepts. Practice the commands. Build real skills.</i>
</p>
