#### pswindowsservadminfundapsh
######5 Basics of Powershell
```
get-service
get-service |more
get-service|where-object Status -eq 'Stopped'|more
get-help get-service
```
update:
```
update-help
```
more detail
```New
get-help get-service -Examples
help get-service //can scroll through
```
get-command
```
get-command -Name *DNS*
```
```
get-service |get member
```
######8 Configure 1
```
Rename-Computer -NewName D1
Restart-Computer
```
set ip
```
New-NetIPAddress -IPAddress 192.168.95.20 -PrefixLength 24 -DefaultGateway 192.168.95.2 -InerfaceAlias Ethernet0
```
```
Tzutil.exe /s "Central Standard Time"
```

others
```
Get-ADObject -SearchBase "OU=,DC=,DC=" -Filter *|ft
get-printer |ft
get-smbshare -Name Demos
Get-DhcpServerv4Scope |ft
```
tbc 09 1:00
