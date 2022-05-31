# Neko Dumper

[下载地址](https://github.com/RujiaZhang/nekodumper/releases/latest/download/nekodumper.exe)

某APP的离线导出工具，用于备份内容。

本项目仅用于备份下架内容及在其他设备上浏览内容，**请勿无授权传播**。

**闷声大发财**，为了该工具的使用寿命，使用请低调。

## 前置需求
该工具需要将相关文件传送到电脑上，需要安卓设备的root权限。

## 用法

1. 将app文件夹中的内容传输到电脑中。
    - 钛备份：备份APP之后，将`/sdcard/TitaniumBackup`下的APP的.tar.gz文件传输到电脑中，在电脑中解压，选择`/data/data/com.xxx`文件夹。
    - 直接复制：用root文件管理器打开`/data/data/com.xxx`，将整个文件夹传输到电脑中。
  
2. 将*NekoDumper*可执行文件复制到第一步的文件夹中。
   
3. 运行*NekoDumper*。
   
4. 运行完成后文件夹中会出现备份的文件。

## 编译
1. 参考Rust圣经的[寻找牛刀，以便小试](https://course.rs/first-try/intro.html)章节，安装rustup与cargo。

2. 将代码下载或`git clone`到本地，命令行执行`cargo build`编译。

## License
MIT License
