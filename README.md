# bilibili-video-downloader
Git练手

(I'll be glad if you can help me translate README.md into English)

# 功能
OS X 下的一个bilibili视频下载器（还不是很完善），目前是用的VLC播放器完成的即时播放
基于pyhton3的命令行工具，主要是使用了flvcd.com的一些功能来完成视频的下载地址获取，用python写了个方便的脚本而已

# 使用方法
1.
shell下运行工具(flvcdapi.py)，将bilibili的视频播放地址粘贴到shell中，回车，开始下载，同时打开VLC进行播放，就酱。

2.
(osx-clip.py)这是一个剪切板工具，识别剪切板中的http地址，并打印到shell中，可以用管道的方式和(multiThread.py 多线程下载)工具结合起来使用
eg:././osx-clip.py | ./multiThread.py
然后去复制地址链接，会自动下载

# 其他
加了一个OS X的剪切版工具（osx-clip.py），方便批量复制视频地址用。
