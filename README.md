# Skuf IDE 

## Prerequisites

Note: after every step you shall restart terminal session
#### Install SDKMan:  

```shell
curl -s "https://get.sdkman.io" | bash
```

#### Install Java of needed version:  

```
sdk install java
```

#### Install SBT:  

```
sdk install sbt
```

#### Install Coursier for scala:  
Linux:  
```
curl -fL "https://github.com/coursier/launchers/raw/master/cs-x86_64-pc-linux.gz" | gzip -d > cs
sudo mv cs /usr/bin/
```

Mac OS:  
```
brew install coursier/formulas/coursier
cs setup
```

#### Install NVM:  

```
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.7/install.sh | bash
```

#### Use last node version:  

```
nvm use 18
```


## 🛠️ Installation

#### Make a backup of your current nvim and shared folder

```shell
mv ~/.config/nvim ~/.config/nvim.bak
mv ~/.local/share/nvim ~/.local/share/nvim.bak
mv ~/.local/state/nvim ~/.local/state/nvim.bak
mv ~/.cache/nvim ~/.cache/nvim.bak
```


#### Clone the repository

```shell
git clone https://github.com/strukovsky/skuf-ide ~/.config/nvim
```

#### Start Neovim

```shell
nvim
nvim --headless +q
```


