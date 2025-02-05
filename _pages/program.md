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
**涉及内容:** 
<span style='background-color: #f0f0f0; padding: 2px 6px; margin: 0 2px; border-radius: 3px; font-size: 0.9em;'>QT</span>
<span style='background-color: #f0f0f0; padding: 2px 6px; margin: 0 2px; border-radius: 3px; font-size: 0.9em;'>MavLink</span>
<span style='background-color: #f0f0f0; padding: 2px 6px; margin: 0 2px; border-radius: 3px; font-size: 0.9em;'>UDP</span>
<span style='background-color: #f0f0f0; padding: 2px 6px; margin: 0 2px; border-radius: 3px; font-size: 0.9em;'>FFmpeg</span>
<span style='background-color: #f0f0f0; padding: 2px 6px; margin: 0 2px; border-radius: 3px; font-size: 0.9em;'>RTSP</span>
<span style='background-color: #f0f0f0; padding: 2px 6px; margin: 0 2px; border-radius: 3px; font-size: 0.9em;'>HTML</span>
<span style='background-color: #f0f0f0; padding: 2px 6px; margin: 0 2px; border-radius: 3px; font-size: 0.9em;'>串口通讯</span>

1. ①基于QT进行界面开发以及功能实现，有登录注册系统、地图交互系统、无人机信息订阅系统、无人机航路点执行系统、无人机通讯方案系统、无人机视频接流显示系统。

2. ②通过远程串口或UDP与无人机通讯，接收发送并解码MavLink，完成对无人机当前信息实时查看。

3. ③地图模块进行交互，在地图上可以实时显示无人机当前位置，通过地图点击完成航路点规划发送。

4. ④使用RTSP进行视频流传输，解码并实时显示于软件客户端。

5. ⑤针对不同类型无人机匹配多种通讯方案，包括：固定翼、垂起固定翼、四旋翼。
