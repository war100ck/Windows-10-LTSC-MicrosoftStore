# Windows-10-LTSC-MicrosoftStore
Adds the Windows store to the Windows 10 LTSC version.

### Screen
<p align="center">
<img src="https://i.imgur.com/DLK5Z0Y.jpg" alt="Your image title" width="820"/>
</p>
##In Explorer, go to the packages folder, from the File menu, start PowerShell and run:##

##В проводнике перейдите в папку с пакетами, из меню Файл запустите PowerShell и выполните:##
```
dir *.appx* | sort $_.Name | %{Add-AppxPackage -Path $_.FullName}
```
---
