# InfoSecKW-workshop01
collection on tools used and some notes

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

### Center for Internet Security, hardening:
https://www.cisecurity.org/cis-benchmarks/
