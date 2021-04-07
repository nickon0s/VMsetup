# VMSetup

```
Set-ExecutionPolicy -ExecutionPolicy Unrestricted -Force
. { Invoke-WebRequest -useb https://boxstarter.org/bootstrapper.ps1 } | iex; Get-Boxstarter -Force
$Cred = Get-Credential $env:USERNAME
Install-BoxstarterPackage -PackageName https://raw.githubusercontent.com/nickon0s/VMSetup/master/setup.choco -Credential $Cred
```
