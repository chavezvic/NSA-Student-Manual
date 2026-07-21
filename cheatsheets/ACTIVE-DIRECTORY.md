# Active Directory Cheat Sheet

```powershell
Get-ADUser -Filter *
Get-ADGroup -Filter *
Get-ADComputer -Filter *
New-ADUser -Name "First Last" -SamAccountName flast
Add-ADGroupMember -Identity "GG-IT-Students" -Members flast
dcdiag
repadmin /replsummary
repadmin /showrepl
```
