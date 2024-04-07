# Kevin Vidomski's Powershell Functions

## The Path

When developing Powershell Modules it's useful to add
your working directory to `$env:PSModulePath`.

e.g.

```pwsh
$env:PSModulePath += "M:\projects\powershell_profile\modules";
```

```cmd
F:\Users\kevinv\Documents\PowerShell\Modules;
C:\Program Files\PowerShell\Modules;
c:\program files\powershell\7\Modules;
C:\Users\kevinv\scoop\modules;
C:\Users\kevinv\Documents\WindowsPowerShell\Modules;
f:\development\Google\Cloud SDK\google-cloud-sdk\platform\PowerShell;
F:\Users\kevinv\AppData\Local\Google\Cloud SDK\google-cloud-sdk\platform\PowerShell;
C:\Program Files\WindowsPowerShell\Modules;
C:\WINDOWS\system32\WindowsPowerShell\v1.0\Modules;
C:\Program Files (x86)\Microsoft SQL Server\140\Tools\PowerShell\Modules\;
F:\Program Files (x86)\Google\Cloud SDK\google-cloud-sdk\platform\PowerShell;
c:\Users\kevinv\.vscode\extensions\ms-vscode.powershell-2024.0.0\modules;
M:\projects\powershell_profile\modules;
```
