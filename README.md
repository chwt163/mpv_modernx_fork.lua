# Mpv.net right click menu CN  && mpv osc.lua


![mpv](https://github.com/chwt163/Mpv.netRrightClickMenuCN/assets/70951194/e752e6a3-d2ea-43b7-8dac-ea6d477e5b00)


![1](https://github.com/chwt163/Mpv.netRrightClickMenuCN/assets/70951194/26be7888-003a-4222-ad11-85594cef6b41)



# 设定 mpv.net 中文右键菜单（新版 mpvnet 已经原生支持中文菜单）：

先安装 mpv.net，替换 input.conf 即可。

input.conf 一般放在以下路径，选其一：

1、程序启动目录\portable_config\ 

2、C:\Users\%USERNAME%\AppData\Roaming\mpv.net\

也可以直接从 mpv.net 的右键菜单中打开配置文件夹： Settings > Open Config Folder





# 设定 osc 主题：

mpvnet 和 mpv 的 osc 主题是通用的

# mpv.net：

1、在 mpv.net 的程序文件夹里面新建 portable_config 文件夹

2、在 portable_config 里面新建 scripts 和 script-opts 以及 fonts 三个文件夹

3、下载 modernx-fork.lua 放在 scripts 文件夹

4、下载 osc.conf 放在  script-opts 文件夹

5、下载字体放在 fonts 文件夹：

[Material-Design-Iconic-Round.ttf](https://github.com/chwt163/Mpv.netRrightClickMenuCN/raw/main/fonts/Material-Design-Iconic-Round.ttf)

[Material-Design-Iconic-Font.ttf](https://github.com/chwt163/Mpv.netRrightClickMenuCN/raw/main/fonts/Material-Design-Iconic-Font.ttf)

6、下载 mpv.conf，放在 portable_config 文件夹，或者直接编辑已有的 mpv.conf，添加内容：osc = no



# mpv：

无需 portable_config 文件夹，直接在 mpv 程序目录里面新建 scripts 和 script-opts 以及 fonts 三个文件夹，然后进行第 3、4、5、6 步骤，mpv.conf 直接放在程序目录。





