# discord-data-package-viewer-parser
My fork of ramzialhaddad's original simple python program for browsing Discord package data. Updated to stop FileNotFoundError
# Building
Building yourself is fairly trivial. Dependencies:
- pandas
- PyQt5
- PyInstaller
Build by executing `pyinstaller --onefile --clean main.py`. A dist/ folder will be created with the build inside. If the app instantly closes when running, try executing in CMD and spotting if you are missing any dependencies
# What it can do now
Currently it reads all your direct messages and showing usernames and such.
# Comming Features
Will be showing all the chats, not only direct messages, as well as server names etc...
Shows all the different IP Adresses that were used to login and got logged in the data package.
