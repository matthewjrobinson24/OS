# Review Day
## Forms of Persistence
### Linux *
- Cron

      /etc/crontab
      /var/spool/cron
      /etc/cron.d
________________________________________________________________________________________________________________________________________
- /etc/init.d --sysv
________________________________________________________________________________________________________________________________________
- /etc/profile
________________________________________________________________________________________________________________________________________
- /etc/enviroment
________________________________________________________________________________________________________________________________________
- /etc/inittab --Sysv
________________________________________________________________________________________________________________________________________
- /etc/rc.d/*
________________________________________________________________________________________________________________________________________
- /lib/systemd/systemd
________________________________________________________________________________________________________________________________________
- /usr/lib/systemd/system
________________________________________________________________________________________________________________________________________
- SERVICES/PROCESSES

      ps -elf
      top or htop
      systemctl status <pid>
________________________________________________________________________________________________________________________________________
# |
# |
# |
# |
### Windows *
- Autoruns
________________________________________________________________________________________________________________________________________
- SCHTASKS
________________________________________________________________________________________________________________________________________
- REGISTRY LOCATIONS

      HKLM
      HKCU
      HKU
      HKCR
      HKCC
________________________________________________________________________________________________________________________________________
- POWERSHELL PROFILE

      4
      Test-Path -Path $profile.currentUsercurrentHost
________________________________________________________________________________________________________________________________________
- SERVICES/PROCESSES

      Get-Service
      Get-Process -id <pid>
________________________________________________________________________________________________________________________________________
- Get-CIMINSTANCE

      win32_service
________________________________________________________________________________________________________________________________________
- Artifacts

      UserAssist
      Windows Background Activity Moderator (BAM)
      Recycle Bin
      Prefetch
      Jump Lists
      Recent Files
      Browser Artifacts
________________________________________________________________________________________________________________________________________
- Ports (Sus)

      44444
      55555
      34567
      76543
      98765
      54321
      56789
      12345
      12321
      45654
      67876
________________________________________________________________________________________________________________________________________
- Obfuscation

      Taking name of something legit ex. GoogleUpdate
      Abnormal for Gov. Device ex. Spotify, Steam, Netflix
      Mispellings of words
      C:\windows\system32
      C:\users\public\downloads\svchost.exe
      Start up folder
      C:\Users\Username\AppData\Roaming\Microsoft\Windows\Start Menu\Programs\Startup
________________________________________________________________________________________________________________________________________
- SysInternal tool
      
      net use * http://live.sysinternals.com
________________________________________________________________________________________________________________________________________
# Game Day

      MARO-M-007
________________________________________________________________________________________________________________________________________
      http://10.50.23.244:8000/
________________________________________________________________________________________________________________________________________
      M24007 password
________________________________________________________________________________________________________________________________________
      Windows: 10.50.22.56      (6)
      Linux: 10.50.25.238       (4)
________________________________________________________________________________________________________________________________________
## 1: Scenario:
The System is infected with malware. You received a report that there were unusual network ports open on the machine.

Task: Investigate and identify the port. The flag is the port. - ``` 23456 ```

      netstat -ano
________________________________________________________________________________________________________________________________________
## 2: Scenario:
The System is infected with malware. You have discovered the unusual open port.

Task: Determine the file that opened the ports. Identify the process that opened the port and identify where it is running from. The flag is in the same directory. - 
``` I_m1gHt_B3_B@d ```

      # look for McAfee.exe
________________________________________________________________________________________________________________________________________
## 3: Scenario:
The System is infected with malware.

Task: Search for any artifacts and investigate them. The flag is the name of the malware artifact file. - ``` SpotifySetup.exe ```

      #
________________________________________________________________________________________________________________________________________
## 4: Scenario:
The system is infected with malware

Task: Determine what would have initially caused this malware to run. The flag is found in the same location that caused the malware to kick off. Look for something out of place. - 
``` Fi1e_not_found ```

      #
________________________________________________________________________________________________________________________________________
## 5:


________________________________________________________________________________________________________________________________________
## 6:


________________________________________________________________________________________________________________________________________
## 7: Scenario:
The System is infected with malware. You receive a report that a non-standard port is open on your system

Task: Identify the port. The flag is the port number. - ``` 22222 ```

      netstat -lntu
________________________________________________________________________________________________________________________________________
## 8: Scenario:
The System is infected with malware. You have found the non-standard open port.

Task: Identify the process that opened the port and identify where it is running from. The flag is in the same file. - ``` N@uGhTy_5cR1pT ```

      cat /tmp/script.sh
________________________________________________________________________________________________________________________________________
## 9: Scenario:
The System is infected with malware.

Task: Identify and gather information on how the malware is starting. Identify the start mechanism and the flag will be located in that file. - ``` F1@g=B@d_Cr0N ```

      sudo cat /var/spool/cron/crontabs/root
________________________________________________________________________________________________________________________________________
## 10: Scenario:
The System is infected with malware. Even after your team has removed the file and rebooted the system, the malware continues to propagate.

Task: Investigate and identify how this is occurring. The flag will be in the file. - ``` B@$h_Pr0F1l3_F1@g ```

      cat /etc/profile
________________________________________________________________________________________________________________________________________
