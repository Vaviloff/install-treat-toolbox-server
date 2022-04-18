## Install Treat Toolbox on a remote server

WIP

```sh
apt-get update
apt-get install openjdk-11-jdk zsh -y

chsh -s $(which zsh)
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)" "" --unattended

curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | zsh
nvm install 14
```
