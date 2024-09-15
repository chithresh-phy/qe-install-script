## Scripts to compile and install Multiple Versions of QuantumEspresso (including the latest version) for parallel computing from source

**This Script can install Quantum Espresso versions: 7.3.1 (Latest), 7.2!**

##### Installing and Running
```bash
sudo apt install wget
wget https://raw.githubusercontent.com/chithresh-phy/qe-install-script/main/qe-install -P ~/Downloads
cd Downloads
chmod +x qe-install
./qe-install
```

> [!NOTE]
> In order to check your Distro/Version (like Ubuntu 22.04 LTS)
> open your Terminal and type:
> ```bash
> cat /etc/os-release
> ```

> [!IMPORTANT]  
> This script works only for
>>         - Ubuntu 24.04 LTS
>>         - Debian 12
>>         - Ubuntu 22.04 LTS
>>         - Ubuntu 20.04 LTS
>>         and distros which is based on it!
