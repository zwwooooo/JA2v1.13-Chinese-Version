## JA2 v1.13 dev 中文重构版

JA2 v1.13 Gamedata 汉化部分(中文包)，原名叫 TBS 1.13 lang zh_CN (又名 TBS Chinese(GB) patch)，原简称 113TBS，源于 tbsgame.net 论坛(简称 TBS)汉化项目，由于 TBS 关闭，目前由原 TBS 部分论坛成员爱心维护。

重构版：原来的文件结构（主要是 xml 文件带 Chinese 开头）不太适合 VFS 方式的多 MOD 组合，以前闲时做了个自用版本，基本就是把 Chinese 开头的 xml 文件改用 1.13 源文件直接汉化，由于熊窝最近发生 svn 服务器问题，部分活跃 coder 把部分资源转移到 github，而后续熊窝那边 SVN 的 Chinese_Version 目录估计不太会再更新，于是跟 kmoi 讨论后，决定使用此构建版。

dev：“JA2 1.13开发版”简称

ja2_dev_cn.exe 源码  
https://github.com/1dot13/source

dev gamedata  
https://github.com/1dot13/gamedir

**分支内容**

* JA2 v1.13 2014 stable 中文重构版（2014 stable = 2014 稳定版 = 7609 版）  
  https://github.com/zwwooooo/JA2v1.13-Gamedata-Chinese/tree/2014-stable
* JA2 v1.13 MOD：AIMNAS 汉化  
  https://github.com/zwwooooo/JA2v1.13-Chinese-Version/tree/AIMNAS_CN
