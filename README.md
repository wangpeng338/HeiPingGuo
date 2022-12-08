# HeiPingGuo

#0.基本配置
#  Thinkpad T430
#  u盘-16G
#1.准备
  镜像
  transmac 或 etcher
  EFI
  diskgenius 替换EFI
2.安装
  实用工具-硬盘工具  格式化-guid
  安装macos
    副本损坏错误解决：实用工具-终端-date XXXXX命令
4.配置
  替换硬盘EFI：打开终端-list硬盘-mount disk0 的EFI -mount u盘的EFI - open . 打开 - 替换EFI
  配置无线网卡：安装heliport.dmg并设置开机启动-下载itlwm.kext 放入 other 文件夹   
5.优化
  下载官方macos
  优化EFI
  macos下制作启动盘
