## PuTTY Skills
#### 1. 注销登录,使用 exit 命令或者 ctrl+d 快捷操作
如果直接关掉窗口，其实你的登录还在服务器上，这会占用系统的资源。可用命令 w 或者 who 命令查看哪个小可爱没有注销登录哦。  
所以输入 exit 命令退出，或者用快捷键 Ctrl+d 注销登录。  
![](https://s3.bmp.ovh/imgs/2022/01/ef2c276050692231.png)  

#### 2.屏幕输出太快了，暂停一下
平时在跑job的时候，有时候看log需要用到。  
Ctrl+S ，可以暂停终端，Ctrl+Q 恢复。

#### 3.翻页
Shift+PageUp/PageDown 一页一页地翻，Ctrl+PageUp/PageDown 则是一行一行地挪。

#### 4.修改主题色Theme
黑乎乎窗口，看着有点古板。暂时还没设置到，mark在这里
1）win +R，regedit
2）找到路径：计算机\HKEY_CURRENT_USER\Software\SimonTatham\PuTTY\Sessions
后面不会set……
github 主题设置参考: [link](https://github.com/AlexAkulov/putty-color-themes)
