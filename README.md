# Compile Coins Scripts

## Instructions
Place this script file in the root directory of the coin. 
This ONLY works for coins with the depends folder in the root directory of the coin. 
Also place root directory in this directory below. 

```
/usr/local/bin
```


It MUST also be logged in as ROOT to avoid errors. 

```
sudo su root
```


The big list of Repos, there is a more but start with these.

```

```


### Linux 64 bit No GUI
```
wget https://raw.githubusercontent.com/nashsclay/Compile_Coins_Scripts/master/linux64_nogui.sh
chmod +x linux64_nogui.sh
./linux64_nogui.sh
```


### Windows 64 bit QT Wallet
```
wget https://raw.githubusercontent.com/nashsclay/Compile_Coins_Scripts/master/win64QT_compile.sh
chmod +x win64QT_compile.sh
./win64QT_compile.sh
```


### Linux 64 bit QT Wallet
```
Coming Soon
```


### Windows 32 bit QT Wallet
```
Coming Soon
```


### MacOSX QT Wallet
No strip needed after compile. This method makes the QT, daemon, cli, and tx files. Send to Mac then do chmod +x filename then run the file.

```
https://raw.githubusercontent.com/nashsclay/Compile_Coins_Scripts/master/MacOSX_allfiles_QT_compile.sh
chmod +x MacOSX_allfiles_QT_compile.sh
./MacOSX_allfiles_QT_compile.sh
```


### ARM Wallet (Raspberry Pi)
```
Coming Soon
```
