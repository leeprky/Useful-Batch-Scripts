# Useful-Batch-Scripts
##Windows Scripts To Do With Powercord

# Requires

Git: https://git-scm.com/downloads

Node & Npm: https://nodejs.org

Discord Canary: (For Installers Only)

macOS: https://discord.com/api/download/canary?platform=osx

Windows: https://discord.com/api/download/canary?platform=win

Linux (deb): https://discord.com/api/download/canary?platform=linux

Linux (tar.gz): https://discord.com/api/download/canary?platform=linux&format=tar.gz

# Powercord Installer

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

# Powercord Essentials

```
cd %USERPROFILE%
cd powercord/src/Powercord/plugins && git clone https://github.com/redstonekasi/theme-toggler
cd ..\..\..\..\
cd powercord/src/Powercord/plugins && git clone https://github.com/ploogins/PowercordThemeDownloader
cd ..\..\..\..\
cd powercord/src/Powercord/plugins && git clone https://github.com/LandenStephenss/PowercordPluginDownloader
cd ..\..\..\..\
taskkill /IM DiscordCanary.exe /F
start %USERPROFILE%\AppData\Local\DiscordCanary\Update.exe --processStart DiscordCanary.exe
pause
```

# All My Themes Installer

```
cd %USERPROFILE%
cd powercord/src/Powercord/themes && git clone https://github.com/leeprky/Ovel
cd ..\..\..\..\
cd powercord/src/Powercord/themes && git clone https://github.com/leeprky/Evo
cd ..\..\..\..\
cd powercord/src/Powercord/themes && git clone https://github.com/leeprky/WindowsXI
cd ..\..\..\..\
cd powercord/src/Powercord/themes && git clone https://github.com/leeprky/Lode
cd ..\..\..\..\
cd powercord/src/Powercord/themes && git clone https://github.com/leeprky/Quarrel
cd ..\..\..\..\
cd powercord/src/Powercord/themes && git clone https://github.com/leeprky/Fluidcord
cd ..\..\..\..\
cd powercord/src/Powercord/themes && git clone https://github.com/leeprky/Peninsula
cd ..\..\..\..\
cd powercord/src/Powercord/themes && git clone https://github.com/leeprky/cybercordtheme-transparent
cd ..\..\..\..\
cd powercord/src/Powercord/themes && git clone https://github.com/leeprky/FullyThemedDiscord
cd ..\..\..\..\
cd powercord/src/Powercord/themes && git clone https://github.com/leeprky/BetterDefaultGlasscord
cd ..\..\..\..\
cd powercord/src/Powercord/themes && git clone https://github.com/leeprky/Slook
cd ..\..\..\..\
cd powercord/src/Powercord/themes && git clone https://github.com/leeprky/slook-remastered
cd ..\..\..\..\
cd powercord/src/Powercord/themes && git clone https://github.com/leeprky/Naive
cd ..\..\..\..\
cd powercord/src/Powercord/themes && git clone https://github.com/leeprky/cybercordtheme-cyan
cd ..\..\..\..\
cd powercord/src/Powercord/themes && git clone https://github.com/leeprky/cybercordtheme-yellow
cd ..\..\..\..\
cd powercord/src/Powercord/themes && git clone https://github.com/leeprky/cybercordtheme-lite
cd ..\..\..\..\
cd powercord/src/Powercord/themes && git clone https://github.com/leeprky/GreenpleBeGone
cd ..\..\..\..\
cd powercord/src/Powercord/themes && git clone https://github.com/leeprky/BlurpleRecolor
cd ..\..\..\..\
cd powercord/src/Powercord/themes && git clone https://github.com/leeprky/Peninsula
cd ..\..\..\..\
cd powercord/src/Powercord/themes && git clone https://github.com/leeprky/ThemeTemplate
cd ..\..\..\..\
taskkill /IM DiscordCanary.exe /F
start %USERPROFILE%\AppData\Local\DiscordCanary\Update.exe --processStart DiscordCanary.exe
pause
```
