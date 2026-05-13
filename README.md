Linux System Health Monitor

A Python utility designed to monitor critical system resources on Linux servers. It tracks CPU, RAM, Disk usage, and Load Average, providing both console feedback and persistent logging.

Features
-Real-time Monitoring: Captures instant hardware utilization.
-Persistent Logging: Saves all data to `system_health.log` for future analysis.
-Smart Alerting: Triggers warnings when system resources exceed predefined thresholds.
-Linux Optimized: Utilizes native OS load average metrics and Shebang for CLI execution.

Prerequisites
- Python 3.x
- `psutil` library

Install dependencies:
```bash
pip install psutil
