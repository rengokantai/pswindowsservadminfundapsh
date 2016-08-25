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
```
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
