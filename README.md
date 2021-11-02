# Configure Win11

[My Repos](https://github.com/annebrown/?tab=repositories) > [my-conf-win11](../README.md) > README.md

# Table of Contents

[Description](#description)

[Usage](#usage) 

[Tasks](#tasks)   

      [Invoke Saved Ubuntu 20.04 Img](invoke-saved-ubuntu-20-04-img)

      [Start RDP Xfce4-session in Remote Desktop](#start-rdp-xfce4-session-in-remote-desktop)   

      [Start KDE Plasma Desktop](#start-kde-plasma-desktop)

      [Launch xfce4-terminal](#launch-xfce4-terminal)

[PowerShell](#PowerShell)       

# Description

Configures my Windows 11 dev env on a fresh OS.    Includes scripts and app conf, including Visual Studio, VSCode, AndroidStudio and PowerShell.  

See: [my-conf](https://github.com/annebrown/my-conf) for all other OSs.

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

# PowerShell

[To Do: Copy old docs here.].