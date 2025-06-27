# OneCloud ImmortalWrt 自动构建固件

## 功能

- 每周日早上 5 点构建最新版固件和插件
- 后台 IP 192.168.2.2，启用 DHCP，无密码登录
- 安装插件：OpenClash（含 Mihomo）、Nikki、Docker、TTYD、文件管理器
- 挂载剩余空间扩展 overlay 和 Docker
- 输出 img.gz（卡刷）+ sysupgrade.tar.gz（线刷）

## 刷写方式

- img.gz 用 BalenaEtcher 或 dd 写入 TF 卡卡刷
- sysupgrade.tar.gz 适用于已有 OpenWrt 的系统升级

## 登录方式

- 地址：192.168.2.2
- 用户名：root
- 密码：空
