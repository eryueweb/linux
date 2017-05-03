Linux
====
Linux command
---
1. ### 删除
   `rm -rf [url | *]`
2. ### 修改文件
    `vi [url]`  
    `i` <font color=gray size=2>进入编辑模式</font>  
    `Esc` <font color=gray size=2>退出编辑模式，进入命令行模式</font>  
    `:` <font color=gray size=2>返回最后一行</font>  
    `w [dirname]` <font color=gray size=2>以指定文件名保存</font>  
    `wq` <font color=gray size=2>保存并退出vi</font>  
    `q!` <font color=gray size=2>不存盘并强制退出vi</font>  
3. ### 查看文件
    `cat [url]`
4. ### 查找文件
    `whereis [dirname]`
5. ### 修改目录名
    `mv [url] [url]`
6. ### 查看当前目录
    `pwd`
7. ### 创建临时环境变量
    `export PATH=[url]:$PATH`
8. ### 创建永久环境变量
    `vi /etc/profile` <font color=gray size=2>修改profile文件</font>  
9. ### 查看环境变量
    `$PATH`
10. ### 传包
    <font color=gray size=2>例：</font>`scp ./a.tar root@123.56.234:/data/nodep2p`
11. ### 下载
    `wget [url]`
12. ### 安装包的流程
    * <font color=gray size=2>生成makefile</font>  
    `./configure --prefix=[安装路径（会自动生成）]`
    * <font color=gray size=2>安装</font>  
    `make`  
    `make install`
    * <font color=gray size=2>添加环境变量，配置为全局模式</font>
13. ### root模式
    `su root`
14. ### 解压
    `tar -jxvf [dirname].tar.bz2`  
    `tar -xvf [dirname].tar`  
    `xz -d [dirname].tar.xz` 
