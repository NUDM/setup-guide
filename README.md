# Environment Setup Guide

## Writing Code
**Download one of these text editors or IDE's:**
 - [Sublime Text](https://www.sublimetext.com/)
 - [JetBrains IDE](https://www.jetbrains.com/products.html?fromMenu) - Get student license [here](https://www.jetbrains.com/shop/eform/students)
 - Or any other text editor / IDE you prefer

## Python (For Mac)
**Open Terminal from applications and enter these commands:**

*Homebrew*
```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```
*Python 3:*
```
brew install python3
```

*Virtualenv* - [tutorial on virtual environments](https://realpython.com/python-virtual-environments-a-primer/)
```
pip3 install virtualenv
```

## Databases
 1. Download [MySQL Workbench](https://dev.mysql.com/downloads/workbench/)
 2. Open application and click new connection (+ sign next to MySQL Connections)
 3. Name your connection something NUDM related (make sure you are using a standard TCP/IP connection)
 4. Use the following parameters and connect:
```
hostname: mysql.nudm.org
username: nudm_read
password: wN#zLFrvvLMnQ@%au9E+GPDLbC$Um#3
```
