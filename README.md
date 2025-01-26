VR（Vengeance Reloaded）汉化包

- 汉化包是基于 sevenfm 的网盘 http://yadi.sk/d/Fj_B0WEKNjRQJ 里面的 SCI 目录下的 Vengeance_Reloaded_Jan_2025_English_Full.7z（2025.01.01）制作的，另外加了些俄文版（VengeanceReloaded_ru.7z）里面的 Data-VR 目录的内容。

Vengeance Reloaded 简介

- 这是继 Arulco 第一场战役之后的 JA2 非官方续集
- Hawkeye 在熊窝的发布贴 http://thepit.ja-galaxy-forum.com/index.php?t=msg&th=23256&start=0&

目录说明

- Data-VR：sevenfm 的 VengeanceReloaded_ru.7z 里面的额外 VR 文件
- Data-VR_ChsPatch：针对 Data-Vengeance、Data-PCM、Data-VR 的中文补丁
- \_\_Translation_Work_Folder：这是翻译工作目录，直接放这里，方便后期更新和跟踪

玩法

1. 先安装 Ja2 1.12 原版，例如安装到 D:\ja2
2. 把 Vengeance_Reloaded_Jan_2025_English_Full.7z 解压并覆盖到 D:\ja2
3. 把这里的 Data-VR 和 Data-VR_2014_ChsPatch 用 SVN 方式还是直接下载方式，放到  D:\ja2
4. 把 TBS 2014 汉化包（ https://github.com/zwwooooo/JA2v1.13-Chinese-Version/tree/113TBS_2014 ）也放到  D:\ja2
5. 参考 vfs_config.Vengeance_CN.ini 或者直接用
6. ja2.ini 里面的 VFS_CONFIG_INI 改成 vfs_config.Vengeance_CN.ini；另外 MERGE_INI_FILES 改成 Ja2_Options.ini, Mod_Settings.ini, CTHConstants.ini, APBPConstants.ini, Skills_Settings.INI, Item_Settings.ini, Taunts_Settings.INI, Helicopter_Settings.INI, Morale_Settings.INI, Creatures_Settings.INI, IntroVideos.ini
7. 使用 sevenfm 最新的 AI ja2.exe（目前是 ja2_2014_AI_cn_3019_VR.exe：https://zww.me 找）来玩
