# My personal powershell setup.

## Powershell Installation
```
Winget Install Microsoft.PowerShell
Winget Install JanDeDobbeleer.OhMyPosh
```


```
Set-ExecutionPolicy RemoteSigned -Force
Set-PSRepository -Name PSGallery -InstallationPolicy Trusted

Install-Module -Name Terminal-Icons -Repository PSGallery -Force
Install-Module PSReadLine -Force
Install-Module posh-git -Scope CurrentUser -Force

# Must restart before using commands below.
oh-my-posh font install [FontName]

```
