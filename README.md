Install Ubuntu on Windows
========================
First, turn on the windows feature of `Windows Subsystem for Linux`. Search `Turn Windows features on or off` and tick on `Windows Subsystem for Linux` to allow the permission. 

<p align="center">  
<img src="https://github.com/CraverBoyyy/Mathematica-Installation/assets/109847168/c8d18143-35b0-4778-8f4e-0d277852f8e4" width="300px" height="300px"  align="center" >
</p>

You need to download the `Windows Terminal` software from Microsoft Store. After installing windows terminal, open `Terminal` using `Run as administrator`.
```Linux
wsl --install
restart-computer
```
After restart your computer, open `Ubuntu` by `Terminal` or search on start menu. \
The Ubuntu terminal have been displayed and you need to set username and password for Ubuntu account. And then script the following commands for fisrt setting on Ubuntu.
  ```Linux
  sudo apt update && sudo apt upgrade
  sudo apt-get install libegl1
  sudo apt-get install libasound2
  ```
For more infomation: [https://ubuntu.com/tutorials/install-ubuntu-on-wsl2-on-windows-10#1-overview](https://ubuntu.com/tutorials/install-ubuntu-on-wsl2-on-windows-10#1-overview)
