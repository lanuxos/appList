[# choco administrative powershell install script](https://chocolatey.org/install)
```
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
```
# choco basic packages
choco install 7zip.install cpu-z.install crystaldiskinfo curl docker-desktop everything ffmpeg filezilla firefox foobar2000 git-fork git.install golang googlechrome googledrive greenshot io-unlocker itunes k-litecodecpackfull launchy lockhunter microsoft-windows-terminal nodejs.install notepadplusplus ntop.portable onedrive pgAdmin4 postman putty.install python qbittorent revo-uninstall
choco install rufus sqlitebrowser sublimetext3 tailscale teamviewer telegram virtualbox visualstudio2019community vlc vscode wechat whatsapp windirstat winrar wsl -y


# choco alternative basic packave
choco install airdroid -y
choco install allway-sync -y
choco install ditto -y
choco install innosetup -y
choco install keepassxc -y
choco install mousewithoutborders -y
choco install nmap -y
choco install openvpn -y
choco install procexp -y
choco install procman -y
choco install rambox
choco install sumatrapdf.install -y
choco install teracopy -y
choco install thonny -y
choco install tor-browser -y
choco install unifiedremote -y
choco install wireshark -y
choco install youtube-dl -y

# other source
microsoft office suit
adobe photoshop
adobe illustrator
adobe ligthroom
lao script
foxit pdf
cisco packet tracer
