# Adkill and Media Download

扩展功能：去视频广告、视频音频下载、正常显示反盗链图片、屏蔽google搜索结果的跳转。

去视频广告：把几个国内大的视频网站的都包含进去了，大部分来自ChinaList，去优酷广告采用的是OpenGG的播放器，并提供三个播放器地址以供选择，在此感谢OpenGG的作者鲁夫以及YoukuAntiADs作者Harv.c和kawaiiushio。

视频音频下载：可以探测网站中视频、音频及flash文件的真实地址。同时提供一个播放器供下载前预览视频、音频(不过swf和wma文件可能无法预览)，播放器来自Firefox上的插件NetVideoHunter插件。

正常显示反盗链图片：功能完全照搬referer changer，我增加了一个去除referer的功能，感谢作者dindog。

屏蔽google搜索结果的跳转：我采用的是直接修改请求url的方法，所以搜索结果页面上链接的地址不会变，但点击后会直接打开结果页而不会经过google的重定向页面。

Forked from：https://code.google.com/archive/p/adkill-and-media-download/

安装方法：打开chrome扩展程序页，然后把扩展拖入安装即可。
