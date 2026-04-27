Runbook: sysinfo.sh
Author: Matt Owens
Date: April 27, 2025
Version: 1.0

What is this?
A lightweight bash script that generates a quick system report. Useful for getting a snapshot of a machine's current state without installing any additional tools.

Requirements

Linux (Ubuntu)
Bash
Git (for installation)


Installation
bashgit clone https://github.com/OwensMatthew/sysinfo.git
cd sysinfo
chmod +x sysinfo.sh

How to Run
bash./sysinfo.sh

Output Breakdown
SectionWhat it showsSystem InfoDate, username, hostname, uptimeDisk UsageStorage space used and availableMemory UsageRAM used and availableNetworkLocal IP addressOS InfoOperating system and kernel version

Notes

No external dependencies required
All data is read only, nothing is modified on the system
Counter resets if the machine restarts
