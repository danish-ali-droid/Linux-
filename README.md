# 🐧 Introduction to Linux: The Ultimate Mastery Guide

<p align="center">
  <img src="banner.png" alt="Linux Banner" width="100%">
</p>

<p align="center">
  <a href="https://www.linux.org/">
    <img src="https://img.shields.io/badge/OS-Linux-orange?style=for-the-badge&logo=linux&logoColor=white" alt="Linux">
  </a>
  <a href="https://www.gnu.org/software/bash/">
    <img src="https://img.shields.io/badge/Shell-Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white" alt="Bash">
  </a>
  <a href="https://en.wikipedia.org/wiki/DevOps">
    <img src="https://img.shields.io/badge/Field-DevOps-blue?style=for-the-badge&logo=azure-devops" alt="DevOps">
  </a>
  <img src="https://img.shields.io/badge/Status-Active-success?style=for-the-badge" alt="Status">
</p>

---

## 🌟 Overview

Welcome to the **Introduction to Linux** repository! This is a comprehensive, module-based learning journey designed to take you from a Linux novice to a confident System Administrator and DevOps professional. 

This repository isn't just a collection of files; it's a curated roadmap featuring **19 specialized modules**, high-resolution **architectural diagrams**, and **automation scripts** that bridge the gap between theory and real-world application.

---

## 🏗️ System Architecture & Design

Understanding the "Why" before the "How" is the key to mastering Linux.

### 🔌 The Linux Boot Sequence
From the moment you press the power button to the moment you see the login prompt, a lot happens under the hood. 

> [!IMPORTANT]
> Mastering the boot process is essential for kernel-level troubleshooting and system recovery.

<p align="center">
  <img src="booting_proccess.png" alt="Booting Process" width="80%">
</p>

### 📂 The File System Hierarchy (FHS)
In Linux, **Everything is a file.** Whether it's a hardware device, a configuration, or a process, it exists somewhere in the file tree.

<p align="center">
  <img src="file_hirachy.png" alt="File Hierarchy" width="80%">
</p>

---

## 🗺️ The Learning Roadmap (19 Modules)

I've broken down the complexities of Linux into logical, bite-sized modules. Each module contains a deep-dive PDF guide.

### 🧱 Phase 1: The Core Foundation
| Module | Title | Key Takeaways |
| :--- | :--- | :--- |
| **01** | **Introduction** | History, Open Source philosophy, and Kernel vs. User space. |
| **02** | **Booting System** | BIOS/UEFI, GRUB, Initrd, and Systemd initialization. |
| **03** | **FHS Mastery** | Deep dive into `/etc`, `/var`, `/proc`, and `/sys`. |
| **04** | **Directory Mgmt** | Navigation (`cd`, `pwd`), Creation (`mkdir`), and path logic. |
| **05** | **File Operations** | Permissions (`chmod`, `chown`), Archiving (`tar`, `gzip`), and links. |

### 🐚 Phase 2: Power User & Shell Mastery
| Module | Title | Key Takeaways |
| :--- | :--- | :--- |
| **06** | **Shell Environment** | Variables, Aliases, and Shell configuration files. |
| **07** | **Globbing & Ops** | Wildcards (`*`, `?`), Control operators (`&&`, `||`, `;`). |
| **08** | **Pipes & Filters** | Stream redirection (`>`, `>>`) and complex command chaining. |
| **09** | **Unix Tools** | Mastering `grep`, `sed`, `awk`, and Regular Expressions. |
| **10** | **The Vi Editor** | Command mode, Insert mode, and advanced text manipulation. |

### 🛠️ Phase 3: System Administration
| Module | Title | Key Takeaways |
| :--- | :--- | :--- |
| **11** | **Process Mgmt** | `ps`, `top`, `kill`, and backgrounding jobs (`&`, `fg`, `bg`). |
| **12** | **LVM & Disk Mgmt** | Logical Volume Management, PV, VG, and LV concepts. |
| **13** | **RAID & Repair** | Data redundancy (RAID 0, 1, 5, 10) and filesystem fsck. |
| **14** | **Scheduling** | Crontab, `at` jobs, and Log Rotation management. |
| **15** | **Package Mgmt** | DNF/YUM, RPM, and Kdump for kernel crash analysis. |

### 🔒 Phase 4: Networking, Security & Containers
| Module | Title | Key Takeaways |
| :--- | :--- | :--- |
| **16** | **Networking** | IP Addressing, Routing, and secure access via SSH. |
| **17** | **Firewalls** | `firewalld` zones, rules, and network security policies. |
| **18** | **SELinux** | Security-Enhanced Linux: Contexts, Booleans, and Troubleshooting. |
| **19** | **Podman** | Modern containerization: Managing pods and images without root. |

---

## 💻 Automation & Scripting

The `Script/` directory contains practical examples of how to automate your workflow. 

### 🤖 Example: Logic & Control Flow
```bash
#!/bin/bash
# argument.sh - Accessing inputs passed to the script
echo "Script Name: $0"
echo "First Argument: $1"
echo "Total Arguments: $#"
```

> [!TIP]
> Use the scripts in `Script/Basic/` to practice Bash logic, loops, and conditional statements.

---

## 📸 Lab Environment

This project is built and tested in a real-world Linux environment.

<p align="center">
  <img src="Screenshot From 2026-03-27 19-35-04.png" alt="Lab Snapshot" width="90%">
</p>

---

## 🚀 Getting Started

1. **Clone the Repo:**
   ```bash
   git clone https://github.com/danish-ali-droid/Introduction_to_Linux.git
   ```
2. **Explore Modules:** Navigate to the root directory and open the PDF modules in sequence.
3. **Run Scripts:**
   ```bash
   chmod +x Script/Basic/*.sh
   ./Script/Basic/argument.sh "Hello World"
   ```

</p>
