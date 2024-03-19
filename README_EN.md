# Palletizing Process Package

*Note:The following content is a machine-translated version. Please refer to it with caution. The human-reviewed version will be updated later.*

**This repository provides the JAKA Palletizing Process Package along with its usage guide and example programs.**

[User Guide](https://github.com/JakaCobot/Palletizers/wiki/Palletizers-user-manual)

## Plugin Information

* Name: Palletizers
* Version: v1.8.2
* Description: This AddOn is used for palletizing tasks with JAKA robots.
* Compatibility: Supports JAKA controllers versions 1.7.0 and 1.7.1 simultaneously.

* System Requirements (1.7.0):
    Controller: v1.7.0.46 and above  
    App: v1.7.0.24 and above  

* System Requirements (1.7.1):
    Controller: v1.7.1.24 and above  
    App: v1.7.1.24 and above  
    JAKA-AddOn-Kit: v1.4 and above  


## Installation Guide

* Installing the Plugin

1. In JAKA App, open “Settings” - “System Settings” - “Addon”. Click the “+” button and select the compressed file of the palletizing process package to upload.
   
<div align="center"><img width="800"  src="https://github.com/JakaCobot/Palletizers/blob/main/img/en/安装.png"/></div>

2. Click the run button to start the palletizing service.Only when the palletizing service is running can the palletizing configuration web page be entered and the program be saved.

<div align="center"><img width="800"  src="https://github.com/JakaCobot/Palletizers/blob/main/img/en/运行.png"/></div>

    Note: When using JAKA App version 1.7.0.x, after installing the plugin, you need to manually restart the JAkA App before it can be used normally.

3. The palletizing instruction blocks can be found in the “Extended” instruction bar on the app “programming” interface when the AddOn package is successfully uploaded. 

<div align="center"><img width="800"  src="https://github.com/JakaCobot/Palletizers/blob/main/img/en/找到指令.png"/></div>

### Basic instruction block

Support palletizing and unpalletizing function, while insertion of custom instruction blocks is not supported.

<div align="center"><img width="800"  src="https://github.com/JakaCobot/Palletizers/blob/main/img/en/基础指令.png"/></div>

### Extension instruction block

Support the insertion of native instruction blocks in specified sections by the user to achieve customized control. Examples include non-IO signal controlled gripper, control of lift axis operations, etc. The enable function is the trigger for auto pick and place, more information please check the advanced part .

<div align="center"><img width="800"  src="https://github.com/JakaCobot/Palletizers/blob/main/img/en/扩展指令展示.png"/></div>

## Example Program Usage

Download this repository, and you can find the program package in the demo directory, import the program into the JAKA App programming page.

## Version Upgrade

Compatible with palletizing process package version 1.5.3 and above, follow the upgrade steps below to retain the original stacking data:

1. Put the robot in the disabled state.
2. Close the palletizing process package.
3. Upload the new version of the palletizing process package.
4. Restart the JAKA App.If you are using a mobile device such as a tablet, please clear the App cache (In application settings) before opening the page.
5. If so, replace the old version of the palletizing instruction block used in the program.

Versions below v1.5.3 of the palletizing process package cannot be upgraded in compatibility, please uninstall the old version before installing the new version.


## Pallet instruction or palletizing instruction

Pallet instruction is the built-in App instruction that can be found in the “control” instruction block of the programming page on JAKA Zu App; Palletizing instructions are the custom instructions that can be found in the “Extension” instruction block after importing the palletizing AddOn.

The built-in pallet instructions within the App are perfect for two-dimensional tasks with evenly spaced placement, requiring no additional setup of coordinates, allowing for swift task completion. However, when facing three-dimensional scenarios that demand complex arrangement forms, palletizing instructions are a preferable choice. Additionally, palletizing instructions offer some additional functionalities tailored for stacking scenes, such as signal management and pallet type management.

|    \  |  Pallet instructions  |  Palletizing instructions  | 
|  ----  | ----  | ----  | 
|  TCP establishment  | Unnecessary  | Necessary  |
|  Pallet coordinate system  | Unnecessary  | Necessary  |   
|  Complex pallet  | Multiple instructions  | One instruction  |   
|  Automatic load switching  | Not support  | Support  |   
|  Signal monitoring  | Not support  | Support  |   
|  Pallet type switching  | Not support  | Support  |   


## Issue and Bug Reporting

You can submit [issues](https://github.com/JakaCobot/Palletizers/issues) and [join discussions](https://github.com/JakaCobot/Palletizers/discussions) in our Github repository.
