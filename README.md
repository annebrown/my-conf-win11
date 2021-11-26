# Configure Win11

[My Repos](https://github.com/annebrown/?tab=repositories) > my-conf-win11 > README.md

# Table of Contents

[Description](#description)

[Usage](#usage) 

[Tasks](#tasks)   

      [Invoke Saved Ubuntu 20.04 Img](invoke-saved-ubuntu-20-04-img)

      [Start RDP Xfce4-session in Remote Desktop](#start-rdp-xfce4-session-in-remote-desktop)   

      [Start KDE Plasma Desktop](#start-kde-plasma-desktop)

      [Launch xfce4-terminal](#launch-xfce4-terminal)

 [Apps](#apps)

    [Windows Terminal](#windows-terminal)

    [PowerShell](#powershell)

    [Firefox Developer](#firefox-developer)  

        [Addons](#addons)

            [Dark Reader](#dark-reader)

            [Web Developer](#web-developer)

            [ColorZilla](#colorzilla)

            [Firefox Multi-Account Containers](#firefox-multi-account-containers)

       [

# Description

Configures my Windows 11 dev env on a fresh OS.    Includes pre-configured Ubuntu Images, scripts and app conf, including Visual Studio, VSCode, AndroidStudio and PowerShell.  Refer to:  [My Vim Config](https://github.com/annebrown/my-conf/vim/README.md) for vim conf for apps.

See: [my-conf](https://github.com/annebrown/my-conf) for other OSs.

# Usage

Clone Repo: [git@github.com:annebrown/my-conf-win11.git](https://github.com/annebrown/bash-conf.git) to $MY_WIN__REPOS/my-conf-win11

Assumes WSL2 has been configured on the host (See: )

# Tasks

## Invoke Saved Ubuntu 20.04 Img

```powershell
PS> $MY_WIN_REPOS/my-conf-win11/bat/Start-Ubuntu-10.04-plasma-desktop.bat
```

## Start RDP Xfce4-session in Remote Desktop

1. Start xfce4-session and start rdp service in wsl:

```bash
$ $MY_WIN_REPOS/my-conf-win11/sh/desktop.sh   
```

2. Launch Windows Remote Desktop RDP profile:

```bat
PS> $MY_WIN_REPOS\my-conf-win11\rdp\start-rdp-desktop.rdp
```

## Start KDE Plasma Desktop

```powershell
PS> $MY_WIN_REPOS/my-conf-win11/bat/plasma-desktop.bat
```

## Launch xfce4-terminal

```batch
PS> $MY_WIN_REPOS\my-conf-win11\bat\xterm.bat
```

# # Apps

## Windows Terminal

C:\Users\anne\AppData\Local\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState\settings.json

## PowerShell

[Note: Add old docs here.]

## Firefox Developer

Restore from my private repo

### Addons

### Dark Reader

Optimizes battery usage. Toggles light/dark mode for every site.  Includes fine tuning and whitelists.  

### Web Developer

Indispensible web dev tools, including a nice web page color summary.

### ColorZilla

Useful for app, web and graphic design.   Fast access to color data without opening a graphics app.  Zoom to any level.    Includes a history of selected colors and a handy palette viewer, 

### Firefox Multi-Account Containers

Cookies are separated by container, allowing you to test with multiple identities or accounts, simultaneously.  Useful for testing at different authorization levels.  Also separates social identity from tracking scripts.  Allows tab grouping without taking up additional screen space with a sidebar.

### 