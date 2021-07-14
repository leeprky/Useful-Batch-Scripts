# Powercord Installer

Requires: 

Git: https://git-scm.com/downloads

Node/Npm: https://nodejs.org

```
echo Installer By Leeprky#2063

cd %USERPROFILE%
git clone https://github.com/powercord-org/powercord
cd powercord
npm i
npm run plug
taskkill /IM DiscordCanary.exe /F
start %USERPROFILE%\AppData\Local\DiscordCanary\Update.exe --processStart DiscordCanary.exe
pause
```
