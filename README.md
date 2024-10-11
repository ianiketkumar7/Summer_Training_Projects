# Summer Training Projects - Red Hat System Administration

This repository contains the shell scripts created during my Red Hat System Administration I (RH124) and II (RH134) training. Each script performs a specific system administration task, helping automate various aspects of managing a Linux system.

## Task 1: User Account Creation
**Script Name**: `task1_user_account_creation.sh`  
This script automates the process of creating a user account in Linux. It allows the system administrator to input a username, password, and other necessary details. Error handling is implemented to check if the user already exists.

## Task 2: Disk Usage Report
**Script Name**: `task2_disk_usage_report.sh`  
Generates a detailed disk usage report for all mounted file systems. The script displays the available, used, and total disk space, helping administrators monitor and manage storage more effectively.

## Task 4: Service Monitoring
**Script Name**: `task4_service_monitoring.sh`  
Monitors the status of a specified service (e.g., `httpd`, `sshd`). If the service is not running, it will attempt to restart it and send a notification email to the administrator, ensuring essential services remain available.

## Task 5: Log Rotation
**Script Name**: `task5_log_rotation.sh`  
This script helps manage log files by automating their rotation. It compresses, archives, or deletes old log files based on predefined criteria, ensuring that log files don’t consume excessive disk space.

## Task 9: System Information Script
**Script Name**: `task9_system_info.sh`  
Displays essential system information such as CPU usage, memory usage, disk space, and network details. This script is useful for quickly retrieving vital system metrics.

## Setup and Usage

1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/yourusername/summer-training-projects.git
