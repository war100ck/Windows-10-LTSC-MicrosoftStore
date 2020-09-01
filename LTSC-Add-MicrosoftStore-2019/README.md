Install:
В проводнике перейдите в папку с пакетами, из меню Файл запустите PowerShell и выполните:
dir *.appx* | sort $_.Name | %{Add-AppxPackage -Path $_.FullName}
