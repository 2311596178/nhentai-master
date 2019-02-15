nhentai-master
===============

这个项目主要代码来自于[tumblr-crawler](https://github.com/dixudx/tumblr-crawler).  
那个项目用于便捷获取tumblr中的图片和视频，我把它修改成了这个本子下载器


这是一个[Python](https://www.python.org)的脚本,配置运行后下载nhentai中的本子
或者可以直接使用编译好的.exe文件

## 配置和运行

有两种方式来指定你要下载的站点,一是编辑`sites.txt`,二是指定命令行参数.

### 第一种方法:编辑sites.txt文件

打开文件`sites.txt`,把你想要下载的nhentai页面写进去,以逗号/空格/tab/表格鍵/回车符分隔,可以多行,不需要`https://nhentai.net/g/`.例如,如果你要下载`https://nhentai.net/g/263184/`,`https://nhentai.net/g/263183/`,这个文件应该是这样的:

```
263184
263183
```

然后保存文件,在终端(terminal)里面运行`python nhentai-master.py`  
或者直接点击运行nhentai-master.exe


### 第二种方法:编辑sites_url.txt文件
当你搜索akane shinjou和rikka takarada并且需要下载所有的搜索结果时，复制你的网页地址并写入文件，例如：

```
https://nhentai.net/search/?q=akane+shinjou++rikka+takarada
```

然后保存文件,在终端(terminal)里面运行`python nhentai-master.py`  
或者直接点击运行nhentai-master.exe




