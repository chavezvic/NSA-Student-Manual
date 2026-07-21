# Playbook: Windows Service Down

```powershell
Get-Service <SERVICE>
Get-WinEvent -LogName System -MaxEvents 50
Get-WinEvent -LogName Application -MaxEvents 50
```
