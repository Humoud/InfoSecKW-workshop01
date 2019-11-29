# InfoSecKW-workshop01
collection on tools used and some notes


### SysInternals PSExec
https://docs.microsoft.com/en-us/sysinternals/downloads/psexec

PsExec64.exe \\IP -u username -p password cmd
PsExec64.exe \\IP -s -u username -p password cmd

### Metasploit Commands/Modules
SMB Login:
```
use smb_login
```

Display scanned hosts:
```
hosts
```

Display valid credentails
```
creds
```

### Crack Map Exec:
https://github.com/byt3bl33d3r/CrackMapExec

### Powershell: Turn Off Defender Real Time Protection
```powershell
 Set-MpPreference -DisableRealtimeMonitoring 1
```

### Powershell: Turn On Defender Real Time Protection
```powershell
 Set-MpPreference -DisableRealtimeMonitoring 0
```

### CMD: Turn off defender(requires a reboot to take affect):
```powershell
REG ADD "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows Defender" /v DisableAntiSpyware /t REG_DWORD /d 1 /f
```

### Powershell Socks Proxy:
https://github.com/p3nt4/Invoke-SocksProxy
```powershell
Import-Module .\Invoke-SocksProxy.psm1
Invoke-SocksProxy -bindPort 1080
```

### Center for Internet Security, hardening:
https://www.cisecurity.org/cis-benchmarks/
