






```
winget install --id Obsidian.Obsidian
winget install --id Syncthing.Syncthing

winget install --id 7zip.7zip
winget install --id Foxit.FoxitReader
winget install --id AIMP.AIMP
winget install --id SoftDeluxe.FreeDownloadManager
winget install --id CodecGuide.K-LiteCodecPack.Full

winget install --id TheDocumentFoundation.LibreOffice
winget install WhatsApp.WhatsApp

winget install --id Python.Python.3.14
winget install --id Microsoft.VisualStudioCode
winget install --id Microsoft.VisualStudioCode.Insiders
winget install --id GitHub.GitHubDesktop

winget install CommunicationPlatform.MAX
winget install zed.rainxch.githubstore









```


**Чтобы использовать другой репозиторий в Winget, нужно** **обратиться к подкоманде winget source**. Для начала следует просмотреть список существующих репозиториев с помощью команды winget source list. [2](https://serverspace.ru/support/help/chto-takoe-winget-i-kak-s-nim-rabotat/)

**Чтобы добавить новый репозиторий**, нужно использовать команду: winget source add -n [name] -a [url] -t [type]. Для удаления репозитория используется аналогичная команда, но с подкомандой remove. [2](https://serverspace.ru/support/help/chto-takoe-winget-i-kak-s-nim-rabotat/)

**Чтобы добавить корпоративный репозиторий** для множества сотрудников, нужно обратиться к конфигурационному файлу по пути %LOCALAPPDATA%\Microsoft\WinGet\Settings\settings.json и добавить необходимые источники. После этого сохранить и репозитории будут готовы к использованию.


[microsoft/winget-cli: WinGet is the Windows Package Manager. This project includes a CLI (Command Line Interface), PowerShell modules, and a COM (Component Object Model) API (Application Programming Interface).](https://github.com/microsoft/winget-cli)
