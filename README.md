## Student Details

- Name: Nikhil Verma
- Registration Number: 24BAI10373
- Course: Open Source Software  


## Chosen Software

Software: VLC Media Player  

Description:  
VLC Media Player is a free and open-source multimedia player developed by the VideoLAN project.  
It can play almost all types of audio and video formats without requiring additional codecs.  
VLC supports multiple platforms such as Linux, Windows, macOS, and mobile devices.  

It is widely used because of its simplicity, performance, and flexibility.  
Being open source, users can study, modify, and distribute the software freely.  


## Shell Scripts

### Script1: System Identity Report  
Filename: script1.sh  
- Displays system information like kernel, user, uptime, and OS  
- Uses basic shell commands and variables  

### Script2: VLC Package Inspector  
Filename: script2.sh  
- Checks if VLC is installed or not  
- Displays version, maintainer, and description  

### Script3: Directory and Permission Auditor  
Filename: script3.sh  
- Checks important Linux directories  
- Displays permissions, ownership, and size  

### Script4: Log File Analyzer  
Filename: script4.sh  
- Searches for errors in system log files  
- Uses grep and loops to count and display results  

### Script5: Open Source Manifesto Generator  
Filename: script5.sh  
Output: manifesto_nikhilVerma.txt  
- Takes user input  
- Generates a personalized open-source manifesto  


## How to Run

### Step 1: Clone the repository
git clone https://github.com/nikhilvermaislive-arch/oss-audit-24BAI10373.git

### Step 2: Navigate into folder
cd oss-audit-24BEY10099

### Step 3: Give permission
chmod +x script1.sh script2.sh script3.sh script4.sh script5.sh

### Step 4: Run scripts

./script1.sh  
./script2.sh  
./script3.sh  
./script4.sh /var/log/syslog error  
./script5.sh  


## Dependencies Installed

### System Requirements
- Linux OS (Ubuntu / WSL Ubuntu)

### Required Commands

- uname → kernel info  
- whoami → current user  
- uptime → system uptime  
- date → current date  
- grep → search logs  
- awk → process data  
- cut → extract fields  
- du → directory size  
- ls → permissions  
- dpkg → package details  

### Software Installation
sudo apt update  
sudo apt install vlc -y  

### Log Files
- /var/log/syslog (Ubuntu logs)

### Permissions
chmod +x scriptname.sh
