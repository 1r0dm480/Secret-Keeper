# Secret Keeper - Python File Encryptor 
<img src="https://img.shields.io/aur/license/yaourt.svg"> <img src="https://img.shields.io/badge/python-3.x-brightgreen.svg"> <img src="https://img.shields.io/badge/release-v1.0-red.svg"> 

Secret Keeper is a file encryptor written in python which encrypt your files using Advanced Encryption Standard (AES). <a href="https://en.wikipedia.org/wiki/Block_cipher_mode_of_operation#Cipher_Block_Chaining_(CBC)" target="_blank"><span style="color: blue">CBC Mode</span></a> is used when creating the AES cipher wherein each block is chained to the previous block in the stream. 

![123](https://user-images.githubusercontent.com/35377569/48672510-c9cd6580-eb5c-11e8-9f2e-1712c484a23b.jpg)

### Features
- [x] Secret Keeper has the ability to generate a random encryption key base on the user input. 
- [x] Secret Keeper can successfully encrypt and decrypt .txt and .docx file types.


### How to Install and Run in Linux
[1] Enter the following command in the terminal to download it.

`git clone https://github.com/Sameera-Madhushan/Secret-Keeper`

[2] After downloading the program, enter the following command to navigate to the Digger directory and listing the contents

`cd Secret-Keeper && ls`

[3] Install dependencies 

`pip3 install -r requirements.txt`

[4] Now run the script with following command.

`python3 Secret-Keeper.py`


### How to Install and Run in Windows
[1] Download and run Python 2.7.x and Python 3.7 setup file from <a href="https://python.org" target="_blank"><span style="color: blue">Python.org</span></a>
  - In Install Python 3.7, enable Add Python 3.6 to PATH
  
[2] Download and run Git setup file from <a href="https://git-scm.com/" target="_blank"><span style="color: blue">Git-scm.com</span></a>, choose Use Git from Windows Command Propmt.

[3] Afther that, Run Command Propmt and enter these commands:

```
git clone https://github.com/Sameera-Madhushan/Secret-Keeper
cd Secret-Keeper
pip3 install -r requirements.txt
python3 Secret-Keeper.py
```

### Worthy of Attention 
1. Encryption of image files, audio files & video files using secret keeper may results corrupted outputs. Please make sure to have a backup before trying to encrypt above mentioned file types. (No issue with .txt and .docx file types) Please help me to fix this.

2. Please make sure to remember the encryption key you enter. If you lose it you’ll no longer be able to decrypt your files. If anyone else gains access to it, they’ll be able to decrypt all of your files.

