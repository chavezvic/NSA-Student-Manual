# PowerShell Cheat Sheet

```powershell
Get-Command
Get-Help Get-Service -Full
Get-Member
Get-Service | Where-Object Status -eq "Running"
Get-Process | Sort-Object CPU -Descending | Select-Object -First 10
Enter-PSSession <HOST>
Invoke-Command -ComputerName <HOST> -ScriptBlock { hostname }
```
