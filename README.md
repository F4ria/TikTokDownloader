# TikTokDownloader

可以批量下载账号发布页或者喜欢页的视频和图集，也可以单独下载分享链接的视频和图集。

# 程序配置

|   参数   |   类型   |                      含义                       |
|:------:|:------:|:---------------------------------------------:|
|  url   | string |               账号主页分享链接，批量下载时使用                |
|  mode  | string | 批量下载类型，post 代表发布页，like 代表喜欢页<br>（需要账号喜欢页公开可见） |
| folder | string |   单独下载分享链接的资源时，使用的文件夹名称<br>（如果文件夹不存在会自动创建）    |
|  name  | string |                  文件保存时的命名规则                   |
|  time  | string |                    创建时间的格式                    |
| split  | string |                   文件命名的分隔符                    |
| music  |  bool  |                 是否下载视频和图集的音乐                  |

