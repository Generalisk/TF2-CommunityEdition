<div align="center">
  
  [![Commit Activity](https://img.shields.io/github/commit-activity/w/Generalisk/TF2-CommunityEdition)](https://github.com/Generalisk/TF2-CommunityEdition)
  [![Commit Activity](https://img.shields.io/github/commit-activity/m/Generalisk/TF2-CommunityEdition)](https://github.com/Generalisk/TF2-CommunityEdition)
  [![Commit Activity](https://img.shields.io/github/commit-activity/y/Generalisk/TF2-CommunityEdition)](https://github.com/Generalisk/TF2-CommunityEdition)
  [![Commit Activity](https://img.shields.io/github/commit-activity/t/Generalisk/TF2-CommunityEdition)](https://github.com/Generalisk/TF2-CommunityEdition)
  
  [![Version](https://img.shields.io/github/v/release/Generalisk/TF2-CommunityEdition)](https://github.com/Generalisk/TF2-CommunityEdition/releases/latest)
  [![Release Date](https://img.shields.io/github/release-date/Generalisk/TF2-CommunityEdition)](https://github.com/Generalisk/TF2-CommunityEdition/releases/latest)
  [![Commits since Latest Release](https://img.shields.io/github/commits-since/Generalisk/TF2-CommunityEdition/latest)](https://github.com/Generalisk/TF2-CommunityEdition/releases/latest)
  
  <!--[![License](https://img.shields.io/github/license/Generalisk/TF2-CommunityEdition)](https://github.com/Generalisk/TF2-CommunityEdition/blob/main/LICENSE)-->
  [![Issues](https://img.shields.io/github/issues/Generalisk/TF2-CommunityEdition)](https://github.com/Generalisk/TF2-CommunityEdition/issues)
  [![File Size](https://img.shields.io/github/repo-size/Generalisk/TF2-CommunityEdition)](https://github.com/Generalisk/TF2-CommunityEdition)
  [![Last Commit](https://img.shields.io/github/last-commit/Generalisk/TF2-CommunityEdition)](https://github.com/Generalisk/TF2-CommunityEdition)
  
  [![Repo Stars](https://img.shields.io/github/stars/Generalisk/TF2-CommunityEdition)](https://github.com/Generalisk/TF2-CommunityEdition)
  [![Discord Server](https://img.shields.io/discord/1343991748019359795)](https://discord.gg/nZBsxVyxhY)
</div>

<div align="center">
  
  ![TF2 Community Edition Logo](https://raw.githubusercontent.com/Generalisk/TF2-CommunityEdition/refs/heads/master/.github/images/tf2ce_logo.png)
</div>

TF2: Community Edition is, as the name implies, A version of TF2 which is ran by the community. This project is meant to be A open source effort so anyone (including you) can make your own updates, ranging from simple bug fixes to new features to even new content such as maps & weapons.

# Contents
- [Requirements](#requirements)
  - [For Windows Users](#for-windows-users)
  - [For Linux Users](#for-linux-users)
- [Installing the Repo](#installing-the-repo)
  - [Method 1](#method-1)
  - [Method 2](#method-2)
  - [Method 3](#method-3)
- [Compiling](#compiling)
  - [Windows](#windows)
  - [Linux](#linux)
- [Licensing](#licensing)
- [Credits](#credits)
- [Contributing](#contributing)
- [Useful Resources](#useful-resources)

# Requirements
- [Steam](https://cdn.fastly.steamstatic.com/client/installer/SteamSetup.exe)
- [Source SDK 2013 Multiplayer](steam://install/243750) via [Steam](https://cdn.fastly.steamstatic.com/client/installer/SteamSetup.exe)
- [Python](https://www.python.org/downloads)
## For Windows Users
- [Visual Studio Community 2022](https://visualstudio.microsoft.com/vs/community/)
## For Linux Users
- [podman](https://podman.io/)

# Installing the Repo
There are multiple ways to set this repo up on your computer:
## Method 1
- At the top of the Repos' home page, click on the green button labeled `Code`.
- At the bottom of the panel that just popped up, click on the button labaled `Download ZIP`.
- Once the zip file has finished downloading, extract the contents wherever you want.

![Github Screenshot](https://raw.githubusercontent.com/Generalisk/TF2-CommunityEdition/refs/heads/master/.github/images/setup-github.png)
- *Please note that you will not be able to push commits/pull requests through directly if you use this method.*
## Method 2
### This method requires [Git](https://git-scm.com/downloads) to be installed!
- Enter this command inside your Powershell/Terminal at the directory of your choice:
  ```
  git clone https://github.com/Generalisk/TF2-CommunityEdition.git
  ```
## Method 3
### This method requires [Github Desktop](https://desktop.github.com/) to be installed!
- Open your repository list and click on `Add > Clone repository...`
- Go to the URL tab.
- Enter `Generalisk/TF2-CommunityEdition` into the box and set the local path to wherever you want.

![Github Desktop Screenshot](https://raw.githubusercontent.com/Generalisk/TF2-CommunityEdition/refs/heads/master/.github/images/setup-github-desktop.png)

# Compiling
## Windows
- Inside the `src` directory, run:
  ```
  createallprojects.bat
  ```
- Open `everything.sln` inside of Visual Studio.
- Set the build mode to `Release`.
  - Building the project in `Debug` mode is very unstable and is highly unrecommended.
  
![Visual Studio Screenshot](https://raw.githubusercontent.com/Generalisk/TF2-CommunityEdition/refs/heads/master/.github/images/compilation-vs.png)
- Go to `Build > Build Solution` in the top menu bar or press `Ctrl+Shift+B`.
- **(Optional)** Click on the `Local Windows Debugger` button which is accompanied by A green play button to begin Debugging inside of Visual Studio.
- *For additional help, check [this YouTube tutorial](https://youtu.be/7CG3kLdQSRY&t=327s).*
## Linux
- Inside the `src` directory, run:
  ```
  ./buildallprojects
  ```
- *For additional help, check [this YouTube tutorial](https://youtu.be/7CG3kLdQSRY&t=356s).*

# Licensing
This project is licenced under the `Source 1 SDK License`, more info can be found [here](LICENSE).

This project also utilizes code from Third Party Sources, more info can be found [here](game/thirdpartylegalnotices.txt).

# Credits
- Source SDK by [Valve Software](https://github.com/ValveSoftware)
- [List of Contributors](.github/CONTRIBUTORS.md)

# Contributing
Before you go and make A pull request, please make sure that your request follows our [Contributor Guidelines](.github/CONTRIBUTING.md).

# Useful Resources
- [Valve Developer Wiki](https://developer.valvesoftware.com/wiki/Setting_up_Source_SDK_Base_2013_Multiplayer)
