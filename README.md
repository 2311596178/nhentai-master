nhentai-master
===============
The main code for this project comes from[tumblr-crawler](https://github.com/dixudx/tumblr-crawler).  
That project was used to easily get pictures and videos from tumblr, and I modified it into this book downloader.


This is a [Python](https://www.python.org) script that you can easily download the photos from nhentai.net

## 中文版教程请[移步这里](./README_CN.md)


### Use sites.txt

Find a text editor and open the file `sites.txt`, add the sites you want to download into the file, separated by comma/space/tab/CR, no `https://nhentai.net/g/`. For example, if you want to download `https://nhentai.net/g/263184/`,`https://nhentai.net/g/263183/`, compose the file like this:

```
263184
263183
```

And then save the file, and run `python nhentai-master.py`  
or just click `python nhentai-master.exe`


### Use sites_url.txt

When you search for Akane shinjou and Rikka takarada and need to download all search results, copy your web address and write to a file, for example:

```
https://nhentai.net/search/?q=akane+shinjou++rikka+takarada
```

And then save the file, and run `python nhentai-master.py`  
or just click `python nhentai-master.exe`