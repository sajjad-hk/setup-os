# setup-os

## make usb boot from .iso with: https://www.balena.io/etcher/

## openSuse

### git

zypper in git

### nvm

curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.34.0/install.sh | bash
source ~/.bashrc
From: https://github.com/SUSE/doc-susemanager/wiki/install-nvm

### VS Code

sudo rpm --import https://packages.microsoft.com/keys/microsoft.asc
sudo sh -c 'echo -e "[code]\nname=Visual Studio Code\nbaseurl=https://packages.microsoft.com/yumrepos/vscode\nenabled=1\ntype=rpm-md\ngpgcheck=1\ngpgkey=https://packages.microsoft.com/keys/microsoft.asc" > /etc/zypp/repos.d/vscode.repo'

sudo zypper refresh
sudo zypper install code
From: https://code.visualstudio.com/docs/setup/linux

