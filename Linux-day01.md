教师：魏明择

Email：weimz@tedu.cn

# Linux-day01

## 1、三大操作系统

### Unix：

AIX（IBM）、Sloaris（SUN）、IOS（Apple移动端）、Mac OS X（Apple）

### Windows：

window3.1、win10等

### Linux：

安卓（Android）、Ubuntu、Redhat

## 2、计算机的组成

### 硬件：

#### 处理器（CPU）：

A11（33亿晶体管）、频率（3.3GHZ）、I3、I5、I7（Intel）

#### 运行内存（RAM）：

用来存储数据  容量（字节为单位）

#### 主板（总线设备）

#### 输入输出设备：

显示屏、键盘、鼠标、触摸屏

#### 外部存储设备：

硬盘、U盘、TF卡

### 软件：

#### 操作系统

Windows、Linux、Unix、uCOSII

#### 应用软件

微信、QQ、游戏等

## 3、Vmware的使用

Ubuntu密码：tarena

### 快捷键：

CTRL+alt 释放鼠标光标

CTRL+alt+enter 全屏/退出全屏（切换）

## 4、Linux基本结构

应用软件

标准库

Linux操作系统内核

硬件

### 4-1 终端工具

#### 打开方法：

1、点击图标

2、搜索命令：终端

#### 退出终端：

1、$ exit<enter>
2、CTRL + d

### 4-2  Linux的使用

#### 4-2-1 Linux/Unix命令

命令名 [选项]   [参数]

注：[]的内容代表可选

命令示列：https://blog.csdn.net/liuwei0376/article/details/88245472

ls：     # 显示当前文件夹下的所有文件和文件夹

ls -s    # 列表显示所有文件

pwd    # 显示当前位置在哪个文件夹下

cd /    # 切换到根文件夹

cd      # 切换到用户主目录

#### 4-2-2 Linux常用命令

**clear命令**：

作用：清屏

快捷键：CTRL + L

**pwd命令**：

作用：用于显示当前的工作路径位置（当前工作文件夹）

示列

$ pwd

/home/pannengxiang/

**Linux/Unix下的路径**：

***路径：***

用来记录一个文件或文件夹的字符串，如：

/home/tarena

/home/tarena/a.txt

根（root） /

***路径分为两种：***

绝对路径：

以‘/’字符开头的路径为绝对路径（再任何时候，一个文件的绝对路径都是唯一的）

相对路径：

1）文件/文件夹名称

2）.当前文件夹

3）..上一级文件夹

4）~用户主目录

**ls命令**：

作用：显示文件或文件夹的内容

格式：ls  [选项]  [文件夹名或文件名]

常用选项：

-l 列表显示文件的详细信息

-a 显示全部文件/文件夹

**mkdir命令**

作用：创建一个或多个文件夹

格式：mkdir文件夹名1 文件夹名2...

实例：

mkdir a b c d

mkdir -p a/bb/ccc/ddd

常用选项：

-p 如果时中间的文件夹不存在，则逐及创建所以文件夹

**rmdir命令：**

作用：删除一个或多个文件夹（文件夹内必须为空）

格式：rmdir [选项]  文件夹名

常用选型：-p 如果是中间文件夹也不空，则逐级删除中间文件夹

实例：

rmdir a b c d

rmdir -p a/bb/cc/dddd

**tree命令**

作用：

**touch命令**

作用：

1、创建新的文件

2、如果文件已经存在，则更新文件的修改视觉

格式：touch 文件路径

实例：

touch newfile

touch oldfile

**rm命令（remove）**

作用：删除文件或者文件夹

格式：rm [选项] 文件/文件夹

示例：

rm a.txt b.txt 

rm c.txt

rm *.txt

rm -r a

常用选项：

-r 递归删除文件夹内的文件和文件夹

-i 删除前给出提示（y代表yes，n代表no）

-f 强制删除，不给任何提示





