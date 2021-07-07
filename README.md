# AutomatedInstallation-DD
Linux AutomatedInstallation DD
全面兼容Centos 7x 8x 对接官方Mirror 不需要dd包

修复偶尔卡死的问题 优化多处判断逻辑

全面剔除Windows 后面出单独的版本

剔除vnc 剔除老旧Centos6 ks 配置 后面会考虑支持Centos6

新增支持aarch64系统;默认自动判断当前系统是不是aarch64重装的时候安装aarch64

自动判断当前IP地区 匹配最快的Mirror源 自动匹配时区 目前仅优化了 大陆 香港 美国 

# 自定义参数:
	 bash InstallDDL.sh -c 7.9 -v 64 默认
	 -c 7.9 Centos版本
	 -v aarch64 强制aarch64
	 -ns 强制禁用SWAP
	 -dhcp 强制静态dhcp
	 
