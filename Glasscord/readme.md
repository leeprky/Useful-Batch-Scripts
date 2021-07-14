# GlasscordInstallerHelper

# Requirements

Git: https://git-scm.com/downloads

Powercord(Discord Canary): https://powercord.dev/

May Need To Run As Administrator

------------------------------------------------

# How It Works

> Creates A Folder In `%USERPROFILE%\AppData\Local\DiscordCanary\app-1.0.37\resources\app`

> Then Opens It & Clones This Repo

> Then Moves The `Glasscord.asar` For You

> Opens Readme For You & The Index.js To Edit

------------------------------------------------

# GlasscordInstallerHelper.bat

```
taskkill /IM DiscordCanary.exe /F
rem 
set "FirstDir=%USERPROFILE%\AppData\Local\DiscordCanary\app-1.0.37\resources\app\GlasscordHelper"
set "SecondDir=%USERPROFILE%\AppData\Local\DiscordCanary\app-1.0.37\resources\app\GlasscordHelper"
rem 
if exist "%FirstDir\" (
    rem 
    mkdir "%SecondDir%"
) else (
    rem 
    mkdir "%FirstDir%"
)
cd %USERPROFILE%\AppData\Local\DiscordCanary\app-1.0.37\resources\app\GlasscordHelper
git clone https://github.com/leeprky/GlasscordInstallExample
del %USERPROFILE%\AppData\Local\DiscordCanary\app-1.0.37\resources\app\GlasscordHelper\GlasscordInstallExample\README.md /q /f
start "" "%USERPROFILE%\AppData\Local\DiscordCanary\app-1.0.37\resources\app\GlasscordHelper\GlasscordInstallExample"
move "%USERPROFILE%\AppData\Local\DiscordCanary\app-1.0.37\resources\app\GlasscordHelper\GlasscordInstallExample\glasscord.asar" "%USERPROFILE%\AppData\Local\DiscordCanary\app-1.0.37\resources\app"
start notepad "C:\Users\leepa\AppData\Local\DiscordCanary\app-1.0.37\resources\app\GlasscordHelper\GlasscordInstallExample\readme.txt"
start notepad "C:\Users\leepa\AppData\Local\DiscordCanary\app-1.0.37\resources\app\GlasscordHelper\GlasscordInstallExample\index.js"
@Echo Off
SETLOCAL EnableDelayedExpansion
for /F "tokens=1,2 delims=#" %%a in ('"prompt #$H#$E# & echo on & for %%b in (1) do     rem"') do (
  set "DEL=%%a"
)
call :colorEcho a0 "IF NO ERRORS SHOWN, CONTINUE TO README.MD"
echo.
pause
exit
:colorEcho
echo off
<nul set /p ".=%DEL%" > "%~2"
findstr /v /a:%1 /R "^$" "%~2" nul
del "%~2" > nul 2>&1i
timeout 10 /nobreak
close
```
