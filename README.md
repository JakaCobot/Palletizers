# 码垛工艺包 

**该仓库提供了 JAKA 码垛工艺包使用指南和示例程序。**


[中文手册](https://github.com/JakaCobot/Palletizers/wiki/%E7%A0%81%E5%9E%9B%E5%B7%A5%E8%89%BA%E5%8C%85%E4%BD%BF%E7%94%A8%E6%8C%87%E5%8D%97)

[English Readme](./README_EN.md)

## 插件信息

* 名称：Palletizers
* 版本：v1.8.1
* 描述：该 AddOn 适用于使用 JAKA 机器人进行码垛任务时使用。
* 兼容性：同时支持 JAKA 控制器 1.7.0 及 1.7.1 版本。

* 系统要求（1.7.0）：
    控制器：v1.7.0.46 及以上  
    App：v1.7.0.24 及以上  
 
* 系统要求（1.7.1）：
    控制器：v1.7.1.24 以上  
    App：v1.7.1.24 及以上  
    JAKA-AddOn-Kit：v1.4 及以上 

## 安装指南

* 安装插件

1. 打开App-设置-系统设置-附加程序，点击右上角的“+”按钮，安装该插件。
2. 点击状态按钮运行插件。
   
<div align="center"><img width="800"  src="https://github.com/JakaCobot/Palletizers/blob/main/img/安装并运行.png"/></div>

    提示：使用 JAKA App 1.7.0.x 版本时，安装完成插件后，需手动重启 JAkA App 之后才能正常使用。

3. 成功之后可以在 App 编程页面的“扩展”指令栏中找到码垛指令块。
   
<div align="center"><img width="800"  src="https://github.com/JakaCobot/Palletizers/blob/main/img/找到指令.png"/></div>

## 示例程序使用方式 

下载该仓库，在 demo 目录中可以找到程序压缩包，在 JAKA App 编程页面导入程序即可。


## 版本升级

兼容码垛工艺包 v1.5.3 及以上版本直接升级，按照下面的升级步骤，您将可以保留原有的垛型数据：

1. 使机器人处于下使能状态
2. 使码垛工艺包处于关闭状态
3. 上传新版本码垛工艺包
4. 重启 JAKA App
5. 如果是平板等移动设备，请清理 App 的缓存后在打开页面。

码垛工艺包v1.5.3 以下的版本不能兼容升级，请删除原有版本后再安装新版本。


## 问题及 BUG 反馈 

您可以在我们的 Github 仓库中提交 [issue](https://github.com/JakaCobot/Palletizers/issues) 和 [参与讨论](https://github.com/JakaCobot/Palletizers/discussions)。
