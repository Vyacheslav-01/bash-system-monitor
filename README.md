# bash-system-monitor
A simple Bash script to display system status: uptime, CPU load, memory, and disk usage.
# 🖥 System Status Overview

This Bash script displays basic system status information in a clear and readable format. It can be used as a mini monitoring panel or as a base for automated system logging.

## 🚀 Features

- Shows system uptime
- Displays CPU load (batch mode)
- Memory usage summary
- Disk space usage

## 📄 Used Commands

- `uptime` — shows how long the system has been running
- `top -b -n1 | grep "Cpu"` — gets CPU usage in text (batch) mode
- `free -H` — displays memory usage in a human-readable format
- `df -h` — shows disk usage with readable sizes

## ⚙️ Installation & Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/your_username/your_repository_name.git
   cd bash-system-monitor
