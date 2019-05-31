# My WSL Setup for Development
Document my current setup for Windows Subsystem for Linux.

### Download & Install the WSL
- Follow the very thorough instructions [here](https://msdn.microsoft.com/en-au/commandline/wsl/install_guide)

### Install Zsh
- Run this `sudo apt-get install zsh`
- Open your bash profile `vi ~/.bashrc`
- Add this to set it to use ZSH as default:
```
if [ -t 1 ]; then
  exec zsh
fi
```

### Get your terminal looking pretty pt.2
- Install Oh My Zsh with `sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"`
  - Read docs [here](https://github.com/robbyrussell/oh-my-zsh) on how to add more plugins and change themes (I went with their out of the box 'robbyrussell').

