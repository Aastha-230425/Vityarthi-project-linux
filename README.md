# Vityarthi-project-linux
This repository contains five shell scripts and a comprehensive report outline covering the "Open Source Audit" capstone project for the chosen open source software: **VLC Media**
## Developer Information
- **Student Name**: Aastha Krishna
- **Registration Number**: 24BCE10672
- **Chosen Software**: VLC Media
  ## Project Shell Scripts
  1. **sys_identity.sh:** Displays basic system information such as kernel version, operating system distribution, current user, system uptime, and date. This script helps understand the environment where VLC Media Player is installed and executed.
     
  2. **vlc_package_inspector.sh:** Checks whether VLC Media Player is installed on the system using package managers (dpkg or rpm). It also retrieves package details such as version, installation status, and a brief description of the VLC package.
     
  3. **disk_auditor.sh:** Scans important directories related to VLC configuration and system storage. It calculates directory sizes and displays file permissions using Linux commands such as ls -ld, du, and awk.
     
  4.**vlc_log_analyzer.sh:** Reads and analyzes a log file line by line using a while read loop to detect occurrences of specific keywords such as error or warning. It counts matches and displays the last five relevant lines for quick troubleshooting.
  
  5.**vlc_manifesto.sh:** An interactive script that asks the user a few questions about open-source software and multimedia technology. Based on the answers, it generates a personalized Open Source Philosophy Manifesto related to VLC Media Player, which is saved as a .txt file.

## Instructions to Run
1.Clone this repository locally or open the project folder in your Linux terminal.
2.Give execution permission to all scripts:
chmod +x *.sh
3.Run any script using:
./script_name.sh

Example:

./sys_identity.sh

(Note: Script 4 (vlc_log_analyzer.sh) requires a file path argument, for example: ./vlc_log_analyzer.sh /var/log/syslog error).

## Dependencies
1.Standard Bash shell (/bin/bash)
2.VLC Media Player
3.Common Linux utilities: awk, cut, grep, tail, dpkg or rpm, du

These tools are typically available by default on most Linux distributions.

About VLC Media Player

VLC Media Player is a free and open-source multimedia player developed by the VideoLAN project. It supports a wide range of audio and video formats without requiring additional codecs and is widely used for multimedia playback, streaming, and media conversion.
