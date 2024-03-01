# Palletizing Process Package

*Note:The following content is a machine-translated version. Please refer to it with caution. The human-reviewed version will be updated later.*

**This repository provides the JAKA Palletizing Process Package along with its usage guide and example programs.**

[User Guide](https://github.com/JakaCobot/Palletizers/wiki/Palletizers-user-manual)

## Plugin Information

* Name: Palletizers
* Version: v1.8.1
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

1. Open App-Settings-System Settings-Add-ons, click the "+" button in the upper right corner to install the plugin.
2. Click the status button to run the plugin.

<div align="center"><img width="800"  src="https://github.com/JakaCobot/Palletizers/blob/main/img/安装并运行.png"/></div>

    Note: When using JAKA App version 1.7.0.x, after installing the plugin, you need to manually restart the JAkA App before it can be used normally.

3. After successful installation, you can find the palletizing instruction block in the "Extensions" instruction bar on the App programming page.

<div align="center"><img width="800"  src="https://github.com/JakaCobot/Palletizers/blob/main/img/找到指令.png"/></div>

## Example Program Usage

Download this repository, and you can find the program package in the demo directory, import the program into the JAKA App programming page.

## Version Upgrade

Compatible with palletizing process package version 1.5.3 and above, follow the upgrade steps below to retain the original stacking data:

1. Put the robot in the disabled state.
2. Close the palletizing process package.
3. Upload the new version of the palletizing process package.
4. Restart the JAKA App.
5. If you are using a mobile device such as a tablet, please clear the App cache before opening the page.

Versions below v1.5.3 of the palletizing process package cannot be upgraded in compatibility, please uninstall the old version before installing the new version.

## Issue and Bug Reporting

You can submit [issues](https://github.com/JakaCobot/Palletizers/issues) and [join discussions](https://github.com/JakaCobot/Palletizers/discussions) in our Github repository.