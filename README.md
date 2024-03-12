# M Centres launcher 3.3 Web Edition
### This repository contains a simple guide for building M Centres 3.3  from source code; M Centres is a software to unlock [Minecraft: Bedrock Edition](https://www.microsoft.com/en-ms/p/minecraft-for-windows/9nblggh2jhxj) for free!


> ## Note: This is an old version of M Centres, don't use it. This is only for demonstracional porpuses, if you really need it you can download the newer version from [here](https://akshnav.cubebanyasz.me)
## Usage

### Requirements

  - Windows 10 or above
  - An x64 Architecture supported CPU
  - [Microsoft Visual C++ Redistributable](https://aka.ms/vs/17/release/vc_redist.x64.exe)
### Install process
 0. Download [Minecraft: Bedrock Edition Trial](https://www.microsoft.com/en-ms/p/minecraft-for-windows/9nblggh2jhxj)
 1. Download the the **latest** version from releases
 2. Extract the files
 3. Open **M-Centres 3.3.exe**
 4. Click ``Use hack without Install (beta)`` and then click ``Reload App list``
 5. Select Minecraft's AppID
 6. Click ``Remove Trial``
 

## How to compile M Centres

-  Download VS Code 2019 version 16.0.3.0 using [Chocolatey](https://chocolatey.org/)
 `choco install visualstudio2019community --version=16.0.3.0`
- Download .Net SDK in Visual Studio 2019
- Import the .snl file into Visual Studio
- Add missing DLLs from [this](https://github.com/Max-RM/mcenterdlls) repo
- Click build, and you're done

### Folder structure of the compiled program 
```
my-folder/                            # Root directory.
|- M-Centres 3.3.exe                  # Main executable
|- M-Centres 3.3.exe.config           # Config file
|- Newtonsoft.Json.dll                # Newtonsoft runtime
|- Newtonsoft.Json.xml                # Strings for Newtonsoft
```
## Authors

* **Tinedpakgamer** - *Initial work* - [M Centres](https://github.com/tinedpakgamer)
* *Cubebanyasz* - Saving this repo, so you can read this message now

## License

This project is licensed under the Copyleft - see the [LICENSE](https://copyleft.org/guide/) for details

--------------
###### Original README
---------------


# M-Centers
official m centers repository
# Notice
this is no longer being updated. But pull requests will be accepted