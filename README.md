# 2D-Platform-Controller
The Controller Follow the Celeste


[Unity完美还原《蔚蓝》手感](https://www.bilibili.com/video/BV1zg4y137yd/?vd_source=0ae523ea1eeb53b40a8fbc5b9a712992)

2019年，在Up主卡姐的翻译视频下https://www.bilibili.com/video/BV1M441197sr看到了介绍《Celeste》手感的视频，受益匪浅，决定一定要还原出它的手感，并分享给大家。
三年后，随着自己Unity水平的不断精进，终于还原出了《Celeste》的控制器实现。

Demo链接：https://pan.baidu.com/s/1rwS3-fPZfTenwzzlfUgUlQ 
提取码：cff1 

源码分享地址：https://github.com/david-reborn/2D-Platform-Controller。

主要功能包括：
Controller部分通过接口和Unity进行隔离，方便进行移植和功能自定义。
支持50多个参数的设置，用于定制属于你自己的角色操控器。
基础的人物状态机：包括Normal，Climb，Dash。
支持基于Raycast的碰撞检测功能。
支持移动，跳跃，攀爬，冲刺功能，支持各种角色动效。
Unity标准输入，自定义输入模块，支持按键缓冲。
支持土狼时间，
支持跳跃边缘校正，
支持冲刺边缘校正，
支持类似Celeste的墙跳（Wall Jump），冲刺跳（Super Jump），蹲跳（Duck Super Jump）
支持Dust粒子效果和Ripple特效。
支持顿帧效果。
支持摄像机震屏，跟随，范围锁定功能。
