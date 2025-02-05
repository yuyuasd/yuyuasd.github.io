---
layout: archive
title: "项目<br><span style='color: #666666; font-size: 0.8em;'>Program</span>"
permalink: /program/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

研究生项目<br><span style='color: #666666; font-size: 0.8em;'>Graduate Projects</span>
======
### 基于MavLink的无人机实机远程控制地面站系统 <span style='color: #666666; font-size: 0.8em;'>(独立完成)[企业横向]</span>
本项目在于实现设计一款可以远程控制多种类型无人机并进行数据的地面站，已批量生产交付
**涉及内容:** 
<span style='background-color: #f0f0f0; padding: 2px 6px; margin: 0 2px; border-radius: 3px; font-size: 0.9em;'>QT</span>
<span style='background-color: #f0f0f0; padding: 2px 6px; margin: 0 2px; border-radius: 3px; font-size: 0.9em;'>MavLink</span>
<span style='background-color: #f0f0f0; padding: 2px 6px; margin: 0 2px; border-radius: 3px; font-size: 0.9em;'>UDP</span>
<span style='background-color: #f0f0f0; padding: 2px 6px; margin: 0 2px; border-radius: 3px; font-size: 0.9em;'>FFmpeg</span>
<span style='background-color: #f0f0f0; padding: 2px 6px; margin: 0 2px; border-radius: 3px; font-size: 0.9em;'>RTSP</span>
<span style='background-color: #f0f0f0; padding: 2px 6px; margin: 0 2px; border-radius: 3px; font-size: 0.9em;'>HTML</span>
<span style='background-color: #f0f0f0; padding: 2px 6px; margin: 0 2px; border-radius: 3px; font-size: 0.9em;'>串口通讯</span>

1. 基于QT进行界面开发以及功能实现，有登录注册系统、地图交互系统、无人机信息订阅系统、无人机航路点执行系统、无人机通讯方案系统、无人机视频接流显示系统。
2. 通过远程串口或UDP与无人机通讯，接收发送并解码MavLink，完成对无人机当前信息实时查看。
3. 地图模块进行交互，在地图上可以实时显示无人机当前位置，通过地图点击完成航路点规划发送。
4. 使用RTSP进行视频流传输，解码并实时显示于软件客户端。
5. 针对不同类型无人机匹配多种通讯方案，包括：固定翼、垂起固定翼、四旋翼。

<div style="border-bottom: 2px solid #FFB6C1; margin: 20px 0;"></div>

### 某部队无人机仿真器控制系统 <span style='color: #666666; font-size: 0.8em;'>(独立开发)[企业横向]</span>
本项目在于实现一款无人机模拟器可以对多种类型无人机控制进行仿真，已批量生产交付。
**涉及内容:** 
<span style='background-color: #f0f0f0; padding: 2px 6px; margin: 0 2px; border-radius: 3px; font-size: 0.9em;'>QT</span>
<span style='background-color: #f0f0f0; padding: 2px 6px; margin: 0 2px; border-radius: 3px; font-size: 0.9em;'>FlightGear</span>
<span style='background-color: #f0f0f0; padding: 2px 6px; margin: 0 2px; border-radius: 3px; font-size: 0.9em;'>TCP</span>
<span style='background-color: #f0f0f0; padding: 2px 6px; margin: 0 2px; border-radius: 3px; font-size: 0.9em;'>Sbus</span>
<span style='background-color: #f0f0f0; padding: 2px 6px; margin: 0 2px; border-radius: 3px; font-size: 0.9em;'>AC3D</span>
<span style='background-color: #f0f0f0; padding: 2px 6px; margin: 0 2px; border-radius: 3px; font-size: 0.9em;'>Ubuntu</span>
<span style='background-color: #f0f0f0; padding: 2px 6px; margin: 0 2px; border-radius: 3px; font-size: 0.9em;'>Ardupilot</span>

1. 基于QT进行界面开发以及功能实现，有登陆注册系统、地图交互系统、无人机信息订阅系统、无人机航路点执行系统、无人机通讯方案系统。
2. 通过TCP与FlightGear中的仿真无人机进行通讯，接收发送并解码MavLink信息，完成对无人机的当前信息实时查看。
3. 地图模块进行交互，地图上实时显示无人机当前位置，通过地图点击完成航路点规划发送。
4. 串口接入遥控器并对其Sbus信号进行处理，并将通道信息进行传递给仿真无人机，完成上/解锁、模式切换及遥控器控制等操作。
5. 自定义无人机模型转换并接入FlightGear仿真器中，实现在该仿真器中显示自定义无人机模型以及控制方法（适应且不限于：固定翼、垂起固定翼、四旋翼）。
