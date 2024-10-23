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

      BAM
      Prefetch
      Userassist
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














