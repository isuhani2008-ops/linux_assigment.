#  Bash Utility Scripts

##  Overview
This repository contains three Bash scripts created by **Suhani** on **15/11/25**.  
They automate common system tasks:
1. **Directory Backup** – Safely back up directories with logs.
2. **System Monitoring** – Log CPU and memory usage at regular intervals.
3. **Download Automation** – Automate file downloads and keep a log.

---

##  Scripts

### 1️ Directory Backup (`backup.sh`)
**Purpose:**  
Backs up a target directory into a timestamped folder and logs the operation.

**Usage:**
```bash
./backup.sh <target_directory>
./backup.sh /home/suhani/projects
Backup successful!
Files saved in: /home/suhani/backup/directories/backup_2025-11-16_10-40-12

./sys_monitor.sh
Timestamp, CPU_Usage(%), Memory_Usage(%)
2025-11-16 11:15:01, 12.3, 45.67
2025-11-16 11:15:06, 8.7, 45.70
2025-11-16 11:15:11, 15.2, 45.72

./download.sh <target_url>
./download.sh https://example.com/file.txt
Downloading file.txt ...
Download successful: /home/suhani/downloads/file.txt
Log file (/home/suhani/downloads/download_log.txt):




