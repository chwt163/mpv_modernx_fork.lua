# mpv.net-Right-click-menu-CN  && mpv osc.lua


![mpvnet](https://user-images.githubusercontent.com/70951194/148356351-5a9f0adb-0c1b-4399-bbb5-2cf9f36af2e9.png)





本项目仅是 mpv.net 的右键菜单中文定制，不包含 mpv.net 主程序。部分内容参考了 mpv.net_CM 项目。






*************************** 设定 mpv.net 中文右键菜单：***************************


先安装 mpv.net，替换 input.conf 即可。

input.conf 一般放在以下路径：

1、程序启动目录\portable_config\ 

2、C:\Users\%USERNAME%\AppData\Roaming\mpv.net\

或者直接从右键菜单中打开： Settings > Open Config Folder





****************************  设定 osc 主题： ***************************



1、在 mpv.net 的程序文件夹里面新建 portable_config 文件夹

2、在 portable_config 里面新建 scripts 和 script-opts 两个文件夹

3、下载 osc.lua 文件放置于 scripts 文件夹

4、下载 osc.conf 文件放置于  script-opts 两个文件夹

5、编辑 mpv.conf 文件，添加一行：osc=no 

如果是原版 mpv，则无需新建 portable_config 文件夹，直接新建 scripts 和 script-opts 两个文件夹即可
