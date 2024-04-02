> [!NOTE]
> ONLY WORKS ON TERMUX

## Description
**APF(Admin Panel Finder) is a tool designed to help developers and security researchers discover potential administrative interfaces for websites. It automates the process of scanning a target domain for commonly used paths and filenames that are associated with backend administration panels.**

## Features
- **Interactive command-line interface with inquirer**
- **Automatic installation of dependencies and packages**
- **Support for different search methods (Path Segment, Sub Domain)**
- **Help and feedback options**

## Installation
```bash
cd $HOME
pkg update
pkg upgrade
pkg install git nodejs
git clone https://github.com/Kairu-bit/AdminPanelFinder
cd AdminPanelFinder
node AdminPanelFinder.mjs
```

## Disclaimer
#### This tool is for educational and ethical purposes only. Do not use it for illegal activities. The author is not responsible for any misuse.

## Credits
- **Developer: Kairu**
- **Dependencies: inquirer, user-agents, figlet, axios**

