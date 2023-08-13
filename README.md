
# # 功能介绍
通过py获取getHttpVideoInfo.do?pid=3...文件内的视频链接地址进行下载原视频，~~但是未实现视频合并功能~~（已实现）

------------


![(M$)YZNQIGPXF$E6X~@U0)4](https://github.com/mcmtYu/cctv_news_download/assets/68932312/8a13df81-5af9-410d-b88f-f44ad1cd4ea8)


------------


#  如何使用？
##### windows：
安装PyCharm（可选）
安装一下必须的第三方插件：

```shell
pip install requests

```
用于发送 HTTP 请求，并下载文件内容


```shell
pip install moviepy

```
用于视频处理和编辑


然后打开[cctv新闻联播官网](https://tv.cctv.com/lm/xwlb/?spm=C94212.P4YnMod9m2uD.EfOoEZcMXuiv.1 "cctv新闻联播官网")
![image](https://github.com/mcmtYu/cctv_news_download/assets/68932312/6428796a-3dc7-46b9-a222-01eb89bda9f3)


f12打开控制台，找到：
网络-Fetch/XHR，重新刷新一遍加载内容
找到以getHttpVideoInfo.do?pid=3...文件开头的文件
![image](https://github.com/mcmtYu/cctv_news_download/assets/68932312/06721f53-2005-4637-bea5-86fe3df17c72)


把该文件的链接复制下来，下载mian、search、merge三个py文件后放在同一目录，PyCharm运行mian.py文件粘贴链接开始下载

![image](https://github.com/mcmtYu/cctv_news_download/assets/68932312/e5621fc2-675d-40c6-97ce-e0d9c8df2293)

合并后的视频保存在根目录，merged.mp4

结束
##### linux
在写了。。。

------------

提一嘴，下载视频速度取决于设备网速，合并视频速度取决cpu
![image](https://github.com/mcmtYu/cctv_news_download/assets/68932312/f7f10ccd-50ee-4854-ba0f-e246e2a3a9d5)

![23280591](https://github.com/mcmtYu/cctv_news_download/assets/68932312/9a785d9b-624a-4354-8046-c3f7e9518a2c)



