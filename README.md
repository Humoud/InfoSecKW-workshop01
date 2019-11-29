# InfoSecKW-workshop01
collection on tools used and some notes

### Crack Map Exec:
https://github.com/byt3bl33d3r/CrackMapExec

### Powershell: turn off defender real time protection
```powershell
 Set-MpPreference -DisableRealtimeMonitoring 1
```

### CMD: Turn off defender:
```powershell
REG ADD "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows Defender" /v DisableAntiSpyware /t REG_DWORD /d 1 /f
```

### Powershell Socks Proxy:
https://github.com/p3nt4/Invoke-SocksProxy

### Center for Internet Security, hardening:
https://www.cisecurity.org/cis-benchmarks/
