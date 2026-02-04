`winget install ИмяПрограммы`

## 📌Скрипт для установки: 

``` powershell
Install-Module Microsoft.WinGet.Client -Force 
Import-Module Microsoft.WinGet.Client 
Repair-WinGetPackageManager
```
