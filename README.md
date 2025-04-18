# 基于STM32的智能家居系统

## 项目描述

本项目是一个基于STM32微控制器的智能家居系统设计。该系统集成了多种传感器和执行器，通过红外遥控、红外避障、光照检测、温湿度检测、火焰传感器和烟雾传感器等模块，实现了智能化的家居控制功能。系统还通过WIFI模块连接到原子云，用户可以通过云端远程控制家居设备，并将环境数据上传至云端进行实时监控。

## 功能概述

1. **密码验证**：
   - 使用红外遥控输入密码。
   - 密码正确时，绿灯亮起，系统开始工作。
   - 密码错误时，红灯亮起，系统不工作。

2. **红外避障**：
   - 当红外避障传感器检测到有汽车靠近时，自动抬杆。

3. **光照检测**：
   - 检测环境光照强度，并将数据显示在TFTLCD屏幕上。
   - 当天亮时，自动开启窗户。

4. **温湿度检测**：
   - 检测环境温度和湿度，并将数据显示在TFTLCD屏幕上。
   - 当温度过高时，自动开启风扇进行降温。

5. **火灾报警**：
   - 火焰传感器检测到火焰，或烟雾传感器检测到烟雾时，蜂鸣器报警。

6. **远程控制与数据上传**：
   - 通过WIFI模块连接到原子云，用户可以远程控制开门、开窗等操作。
   - 系统将温度、湿度、光照强度等环境数据上传至原子云，用户可以在云端实时查看。

## 资源文件内容

本仓库提供的资源文件包含了基于STM32的智能家居系统的完整设计方案，包括硬件电路设计、软件代码实现、以及相关的文档说明。用户可以根据这些资源进行系统搭建、调试和扩展。

## 使用说明

1. **硬件准备**：
   - 准备STM32开发板及相关传感器模块（红外遥控、红外避障、光照传感器、温湿度传感器、火焰传感器、烟雾传感器、蜂鸣器、TFTLCD屏幕、WIFI模块等）。
   - 按照电路设计图连接各模块。

2. **软件准备**：
   - 使用Keil或其他STM32开发工具打开项目代码。
   - 根据硬件连接情况，配置相应的引脚和参数。
   - 编译并下载代码到STM32开发板。

3. **系统调试**：
   - 启动系统，使用红外遥控输入密码进行验证。
   - 测试红外避障、光照检测、温湿度检测、火灾报警等功能是否正常工作。
   - 通过WIFI模块连接到原子云，测试远程控制和数据上传功能。

## 注意事项

- 在搭建硬件电路时，请确保各模块的电源和信号连接正确，避免短路或信号干扰。
- 在编写和调试代码时，请注意引脚配置和传感器初始化顺序，确保系统能够正常启动和运行。
- 在使用WIFI模块时，请确保网络连接稳定，以便实现远程控制和数据上传功能。

## 贡献与反馈

如果您在使用过程中遇到任何问题，或有任何改进建议，欢迎提交Issue或Pull Request。我们期待您的参与和贡献，共同完善这个智能家居系统项目。

## 下载链接
[基于STM32的智能家居系统](https://pan.quark.cn/s/dd700a06294d)

## 说明

该仓库仅用于学习交流，请勿用于商业用途。
