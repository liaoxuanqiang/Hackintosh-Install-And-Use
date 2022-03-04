# Hackintosh 安装使用
## Hackintosh 安装
### 1.下载 Mac OS 镜像
[macOS Monterey 12.x](https://github.com/liaoxuanqiang/System-use-management/blob/main/Mac%20OS)
[macOS Big Sur 11.6.x](https://github.com/liaoxuanqiang/System-use-management/blob/main/Mac%20OS)
[macOS Catalina 10.15.x](https://github.com/liaoxuanqiang/System-use-management/blob/main/Mac%20OS)
### 2.下载[Etcher](https://www.balena.io/etcher/) U盘烧录工具并安装
使用Etcher工具制作Hackintosh 安装启动盘
### 3.下载 [Intel NUC10 Hackintosh EFI](https://github.com/hackintosh-efi/intel-nuc10)
将下载的Intel NUC10 Hackintosh EFI覆盖U盘启动盘的EFI

4.修改BIOS配置
-SATA Mode Selection -> AHCI #开启AHCI高级磁盘模式
-Secure Boot -> Disabled #禁用安全启动
5.将U盘插入电脑并启动安装Mac OS系统

6.下载OpenCore EFI等工具优化Hackintosh EFI 配置
