# TERMUX-THEME
![alt text](https://github.com/Tanmyname/Termux-Theme/blob/main/x1.png?raw=true) 
## INSTALASION
**STEP 1**
```
cd ~ && rm -rf .bashrc
```
**STEP 2**
```
pkg update && pkg upgrade && pkg install figlet && pkg install neofetch && pkg install git && git clone https://github.com/Tanmyname/Termux-Theme.git
```
**STEP 3**
```
cd Termux-Theme
```
**STEP 4**

Akses file .bashrc dan ganti nama Creator 
```
nano .bashrc
```
Setelah selesai mengedit:
Tekan Ctrl + O untuk menyimpan file.
Tekan Enter untuk mengonfirmasi nama file yang akan disimpan.
Tekan Ctrl + X untuk keluar dari nano.

**STEP 5**
```
cp -r .bashrc $HOME
```
**STEP 6**
```
source ~/.bashrc

```
