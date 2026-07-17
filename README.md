# bash-linux-learning
My journey learning Bash, Linux commands, and scripting. Includes notes, scripts, and projects from LinuxBaseCamp, OverTheWire Bandit, and personal experiments.

# 🐧 Bash & Linux Learning Journey

## 🎯 **About This Repo**
This repository documents my progress learning **Bash scripting, Linux commands, and system administration**. It includes:
- **Notes** from tutorials and wargames.
- **Scripts** I’ve written (e.g., file organizers, automation tools).
- **Projects** from platforms like [LinuxBaseCamp](https://linuxbasecamp.com/tutorials) and [OverTheWire Bandit](https://overthewire.org/wargames/bandit/).

---

## 📌 **My Progress**
### ✅ **Completed**
   Resource               | Topic                          | Status          |
 |------------------------|--------------------------------|-----------------|
 | [LinuxBaseCamp](https://linuxbasecamp.com/tutorials) | Getting Started, The Command Line, Text Fu | ✅ Completed    |
 | [OverTheWire Bandit](https://overthewire.org/wargames/bandit/) | Levels 0-10              | ✅ Completed    |

### 🔄 **In Progress**
- Writing **custom Bash scripts** for file management.
- Exploring **permissions (chmod, chown)** and **cron jobs**.

### 🚀 **Up Next**
- **Awk/Sed** for text processing.
- **System monitoring scripts** (e.g., log parsers).

---

## 🗂️ **Repository Structure**
 | Folder       | Description                                                                 |
 |--------------|-----------------------------------------------------------------------------|
 | `/notes`     | Study notes (Markdown files) from tutorials and wargames.                |
 | `/scripts`   | Bash scripts (e.g., file organizers, automation tools).                  |
 | `/projects`  | Larger projects (e.g., Bandit wargame, custom tools).          |
 | `/vm-setups` | Configurations and notes for my **Arch/Fedora/Ubuntu VMs**.               |

---
## 💡 **Featured Scripts & Projects**
### **1. File Organizer Script**
- **File**: [`scripts/file_organizer.sh`](scripts/file_organizer.sh)
- **Description**: Automatically sorts files (e.g., `.jpg`, `.png`) into folders by extension.
- **Usage**:
  ```bash
  chmod +x file_organizer.sh
  ./file_organizer.sh /path/to/directory
