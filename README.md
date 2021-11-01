# Configure Win11

[My Repos](https://github.com/annebrown/?tab=repositories) > [my-conf-win11](../README.md) > README.md

# Table of Contents

[Description](#description)

[Usage](#usage) 

[Scripts](#scripts)   

       [Start RDP Xfce4-session in Remote Desktop](#start-rdp-xfce4-session-in-remote-desktop)   

       [Start KDE Plasma Desktop](#start-kde-plasma-desktop)

       [Launch xfce4-terminal](#launch-xfce4-terminal)

[PowerShell](#PowerShell)       

# Description

Configures my Windows 11 dev env on a fresh OS.    Includes app profiles, startup scripts, scripts to start desktop sessions and indivudual apps.  Also configures dev apps conf, including Visual Studio, VSCode, PowerShell.  

See: [my-conf](https://github.com/annebrown/my-conf) for all other OSs.

# Usage

1. Clone Repo: [git@github.com:annebrown/my-conf-win11.git](https://github.com/annebrown/bash-conf.git) to $MY_WIN__REPOS/my-conf-win11

2. Link files:

```bash
[~] $ ln -s $MY_REPOS/my-conf/bash/bash_aliases .bash_aliases     
```

See Also : $MY_REPOS/my-conf/vim/README.md

```bash
[~] $ ln -s $MY_REPOS/my-conf/vim .vim
[~] $ ln -s $MY_REPOS/my-conf/vimrc .vimrc
[~] $ ln -s $MY_REPOS/my-conf/vrapperrc .vrapperrc
```

2. Prepare service and app startup scripts.  Run:
   
   [To Do: Finish editing scripts and push to dynamic branch.]

```bash
prep_startup_scripts   
```

# Scripts

## Start RDP Xfce4-session in Remote Desktop

1. Clone Repo: [git@github.com:annebrown/my-conf-win11.git](https://github.com/annebrown/bash-conf.git) to $MY_WIN__REPOS/my-conf-win11  

2. Start xfce4-session and start rdp service:
   
   Either use bash alias (configured in [bash](../bash/README.md)):

```bash
$ desktop
```

or directly:

```bash
$ $MY_REPOS/my-conf/win11/wsl/desktop.sh   
```

2. Launch Windows Remote Desktop RDP profile:

```bat
PS> \\wsl$\Ubuntu-20.04\$MY_WIN_REPOS\my-conf-win11\rdp\start-rdp-desktop.rdp
```

## Start KDE Plasma Desktop

```powershell
$MY_WIN_REPOS/my-conf-win11/wsl2/plasma-desktop.bat
```

## Launch xfce4-terminal

```batch
PS> $MY_WIN_REPOS\my-conf-win11\wsl2\xterm.bat
```

# PowerShell

[To Do: Copy old docs here.]