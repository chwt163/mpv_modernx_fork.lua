# Mpv.net right click menu CN  && mpv osc.lua


![无标题](https://user-images.githubusercontent.com/70951194/159644297-7f7891d5-cb50-4e35-8a27-e4f8d1c31368.png)







# 设定 mpv.net 中文右键菜单：

先安装 mpv.net，替换 input.conf 即可。

input.conf 一般放在以下路径，选其一：

1、程序启动目录\portable_config\ 

2、C:\Users\%USERNAME%\AppData\Roaming\mpv.net\

也可以直接从 mpv.net 的右键菜单中打开配置文件夹： Settings > Open Config Folder

* 部分菜单内容参考了 mpv.net_CM 项目





# 设定 osc 主题：

mpvnet 和 mpv 的 osc 主题是通用的

mpv.net：

1、在 mpv.net 的程序文件夹里面新建 portable_config 文件夹

2、在 portable_config 里面新建 scripts 和 script-opts 两个文件夹

3、下载 osc.lua 放在 scripts 文件夹

4、下载 osc.conf 放在  script-opts 文件夹

5、下载 mpv.conf，放在 portable_config 文件夹，或者直接编辑已有的 mpv.conf，添加内容：osc = no



mpv：

无需 portable_config 文件夹，直接第 2 3 4 步骤，mpv.conf 放程序目录




# 打包好的懒人版，解压即可：

https://github.com/chwt163/Mpv.netRrightClickMenuCN/releases

