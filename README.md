# 🔐 Summer Training Projects - Red Hat System Administration

This repository contains shell scripts developed during my **Red Hat System Administration I (RH124)** and **II (RH134)** training. The focus is on automating key tasks in a Linux environment. Each script is built with efficiency and cybersecurity best practices in mind.

![Cybersecurity Banner](https://img.shields.io/badge/Cybersecurity-%F0%9F%94%92-blue)

---

## 🛠️ Project Overview

| **Task**  | **Description**                                | **Script Name**                          |
| --------- | ---------------------------------------------- | ---------------------------------------- |
| Task 1    | User Account Creation Automation               | `task1_user_account_creation.sh`         |
| Task 2    | Disk Usage Monitoring and Reporting            | `task2_disk_usage_report.sh`             |
| Task 4    | Service Monitoring and Notification System     | `task4_service_monitoring.sh`            |
| Task 5    | Automated Log File Rotation                    | `task5_log_rotation.sh`                  |
| Task 9    | System Information Retrieval                   | `task9_system_info.sh`                   |

---

## 📂 Detailed Description

### Task 1: 🧑‍💻 User Account Creation
Automates the process of creating user accounts with error checking to prevent duplicate accounts. It's a secure and efficient way to manage user provisioning in Linux.

---

### Task 2: 💾 Disk Usage Report
Generates a report displaying disk usage for all mounted file systems, ensuring that you can easily monitor available space and prevent storage issues.

---

### Task 4: ⚙️ Service Monitoring
This script monitors essential system services (like `httpd` and `sshd`) and restarts them automatically if they fail. If a service is restarted, an email is sent to the administrator.

---

### Task 5: 🗂 Log Rotation
Helps manage disk space by rotating and archiving old log files. It ensures logs do not fill up disk space over time and keeps the system running efficiently.

---

### Task 9: 🔍 System Information Script
Displays key system metrics like CPU usage, memory usage, and network statistics in one place. A handy tool for system administrators to quickly check the health of the system.

---

## 🛡️ Security Features
These scripts are built with security in mind. Whether it's restricting unauthorized access, managing system resources, or ensuring uptime, they contribute to overall system resilience.

---

## 🚀 How to Use

1. **Clone this repository** to your local machine:
   ```bash
   git clone https://github.com/yourusername/summer-training-projects.git
