## JA2 v1.13（开发版）TBS 汉化版 - 重构版

JA2 v1.13 Gamedata TBS 汉化版 - TBS 1.13 lang zh_CN (又名 TBS Chinese(GB) patch)，简称 113TBS，源于 tbsgame.net 论坛(简称 TBS)汉化项目，由于 TBS 关闭，目前由原 TBS 部分论坛成员爱心维护。

重构版：原来的文件结构（主要是 xml 文件带 Chinese 开头）不太适合 VFS 方式的多 MOD 组合，以前闲时做了个自用版本，基本就是把 Chinese 开头的 xml 文件改用 1.13 源文件直接汉化，由于熊窝最近发生 svn 服务器问题，部分活跃 coder 把部分资源转移到 github，而后续熊窝那边 SVN 的 Chinese_Version 目录估计不太会再更新，于是跟 kmoi 讨论后，决定使用此文件新明命重构版。

dev：“JA2 1.13开发版”简称

日志例子说明：  
6097fd8+7aa0e18, 4ee5e9c: v1  
6097fd8+7aa0e18为1.13开发版gamedir版本+源码版本，4ee5e9c为gamedir-languages版本，v1此版本修改标识  

ja2_dev_cn.exe 源码  
https://github.com/1dot13/source

dev gamedata  
https://github.com/1dot13/gamedir

dev gamedata languages  
https://github.com/1dot13/gamedir-languages



**分支内容**

开发版
* JA2 v1.13 MOD：AIMNAS 不完全汉化  
  https://github.com/zwwooooo/JA2v1.13-Chinese-Version/tree/AIMNAS_zh-CN_Patch

2014/7609 稳定版（2014 stable = 2014 稳定版 = 7609 版）  
* JA2 v1.13 2014/7609 中文重构版  
  https://github.com/zwwooooo/JA2v1.13-Chinese-Version/tree/113TBS_2014
* JA2 v1.13 2014/7609 MOD：IoV Revised 重构版  
  https://github.com/zwwooooo/JA2v1.13-Chinese-Version/tree/IoV_Revised_2014
* JA2 v1.13 2014/7609 MOD：SDO（Stock Data Overhaul）汉化包  
  https://github.com/zwwooooo/JA2v1.13-Chinese-Version/tree/SDO_2014_ChsPatch
* JA2 v1.13 2014/7609 MOD：VR（Vengeance Reloaded）汉化包  
  https://github.com/zwwooooo/JA2v1.13-Chinese-Version/tree/VR_2014_ChsPatch
* JA2 v1.13 2014/7609 MOD：TypeP 汉化包  
  https://github.com/zwwooooo/JA2v1.13-Chinese-Version/tree/TypeP_2014_ChsPatch 
