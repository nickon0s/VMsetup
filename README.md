# VMSetup

```
$Cred = Get-Credential $env:USERNAME
Set-ExecutionPolicy -ExecutionPolicy Unrestricted -Force
. { Invoke-WebRequest -useb https://boxstarter.org/bootstrapper.ps1 } | iex; Get-Boxstarter -Force
refreshenv
Install-BoxstarterPackage -PackageName https://raw.githubusercontent.com/nickon0s/VMSetup/master/setup.choco -Credential $Cred

```

Credits to:
https://github.com/ZeroPointSecurity/RTOVMSetup
https://gist.github.com/ghostinthewires/033276015ba9d58d1f162e7fd47cdbd3
https://gist.github.com/yankcrime/353339aa599e4843828ce23b6bc423e7
