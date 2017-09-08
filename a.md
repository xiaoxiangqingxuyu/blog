Linux 基础教程——命令行基础

# 1. 如何编写命令
**1）命令与程序**
 **Linux命令：**
- 用于实现某一类功能的指令或程序
- 命令的执行依赖于解释器（eg：/bin/bash）
**Linux命令的分类：**
- 内部命令：属于Shell解释器的一部分
- 外部命令：独立于Shell解释器之外的程序文件
**检查命令类型：**
- type 检查命令字类型
type name
eg： 
![](http://upload-images.jianshu.io/upload_images/7650860-4c1c8a3a0826a2bd.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
类型 含义 
builtin Shell内建命令 
file 磁盘文件，外部命令 
keyword 保留的关键字 
function Shell函数 
not found 未找到，无法识别
**2）命令行一般格式**
命令字 [选项]… [参数1] [参数2]![](http://upload-images.jianshu.io/upload_images/7650860-7210cad9fb1b8fb3.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
- 选项：调控命令的执行方式 
- 参数：命令的操作对象，如目录或文件
**3）快速编辑命令行**
**辅助操作：**
- Tab：自动补齐（命令或路径，连续按两次可列出全部可选项）
- 反斜杠“\”：强制换行
快捷键：
Alt + . ：输出上一个命令的参数
Ctrl + u：清空至行首
Ctrl + k：清空至行尾
Ctrl + l ：清空整个屏幕
Ctrl +c：废弃当前编辑的命令
# 2. 获取命令帮助
**1）help命令**
 - 内部命令： help 命令名
 - 外部命令： 一般都会提供 –help 选项
**2）使用man手册**
- Linux中一种手册页文档机制 提供命令名称，语法，用途描述，选项，作者等信息
- 大多数程序/配置文件/库函数都提供手册页
- man，格式化手册阅读工具
方向键上下，pgup，pgdn滚动及翻页
q或Q退出
按”/”向后，“？”向前查找（n，N切换搜索项）
#后记
最近开始了对Linux的学习，所以就会把这段时间的笔记，心得。进行一些整理，比较粗糙。谢谢各位。