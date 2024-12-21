## Script to compile and install Multiple Versions of QuantumEspresso (including the latest version) for parallel computing from source

##### **This Script can install Quantum Espresso versions: 7.4 (Latest), 7.3.1, 7.2!**
##### _**This Script was Tested and is Known to Work in Ubuntu 24.04 LTS, Ubuntu 22.04 LTS, Debian 12 and WSL (Ubuntu 22.04 LTS)**_

> [!CREDITS]
> This Script is loosely based on this guide --> "https://pranabdas.github.io/espresso/setup/install"

### Installing and Running
open your Terminal and run:
```bash
sudo apt install wget
wget https://raw.githubusercontent.com/chithresh-phy/qe-install-script/main/qe-install -P ~/Downloads
cd Downloads
chmod +x qe-install
./qe-install
```

> [!NOTE]
> **You need to be connected to the Internet while running this script because some dependencies required for compiling will be pulled from github!**

> [!IMPORTANT]  
> This script will work only on
>>         - Ubuntu 24.04 LTS
>>         - Debian 12
>>         - Ubuntu 22.04 LTS
>>         - Ubuntu 20.04 LTS
>>         and distros which are based on it!
> In order to check your Distro/Version (like Ubuntu 22.04 LTS), open your Terminal and run:
> ```bash
> cat /etc/os-release
> ```
