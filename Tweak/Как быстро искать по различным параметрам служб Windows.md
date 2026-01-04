---
url:
  - https://t.me/sterkin_ru/1742
---

 Get-Service  - для получения сведений о службах
```powershell
Get-Service | Out-GridView
```

По умолчанию выводится всего три параметра служб: имя, отображаемое имя и статус. Все доступные параметры можно отобразить так:

```powershell
Get-Service | Select-Object * | Out-GridView
```



