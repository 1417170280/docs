# 快速开始

工一云电脑连接的方式包含APP、浏览器、订阅、定制程序等多种连接方式。
### 使用方法
1. 根据下表查找对应设备、系统的推荐连接方式；  
2. 选择其中一种推荐连接方式，具体步骤参考下面对应的连接方式；

### 推荐连接方式

最常用的连接方式是APP和浏览器，支持APP的首先推荐APP进行连接，其次是浏览器；临时性一次性使用推荐浏览器；具体推荐的连接方式如下：

<!-- <div align="center">各设备推荐的连接方式表</div> -->
<figcaption>各设备推荐的连接方式表</figcaption>

|操作系统       |电脑[1]                          |平板      |手机|智能电视|智能投影|单片机  |零终端|瘦终端|
|---------------|--------------------------------|----------|----|-------|-------|-------|---------|-------|
|Windows        |ALL[2]                           |ALL[2]   |   |       |       |          |       |       |
|Andriod        |                                |APP, 浏览器|APP|APP    |APP    |        |       |       |
|iOS            |                                |          |APP|        |       |        |       |       |
|iPadOS         |                                |APP, 浏览器|   |       |       |        |       |       |
|macOS          |APP, 浏览器                      |          |   |       |       |        |       |       |
|ChromeOS       |                                |APP, 浏览器|APP|        |       |        |       |       |
|HarmonyOS      |                                |APP, 浏览器|APP|        |       |        |       |       |
|MIUI OS       |                                |APP, 浏览器|APP|        |       |        |       |       |
|MIUI TV       |                                |           |   |APP     |APP       |        |       |     |
|WinPhoneOS     |                                |          |APP|         |       |        |       |       |
|RaspBerryOS    |                                |          |   |         |       |定制程序|       |       |
|ThinOS         |                                |           |  |         |       |       |定制程序|定制程序|
|Linux Desktop  |浏览器                          |浏览器     |   |         |       |       |       |       |
|Linux Server   |定制程序                        |           |  |         |       |定制程序|定制程序|定制程序|

:::tip 提示
电脑[1]：包含台式、一体机、笔记本、微型电脑、虚拟机；    
ALL[2]：代表APP, 浏览器, 订阅, 定制程序所有连接方式；
:::
<!-- * Windows+台式/笔记本/微型电脑：浏览器、IE浏览器、订阅
* Andriod/HarmonyOS/iOS+手机：APP客户端
* Andriod/HarmonyOS/iPadOS/macOS/ChromeOS+平板/一体机/笔记本：APP客户端、浏览器
* Linux Desktop(RaspBerryOS, Ubuntu, Debian, Centos, Redhat...)+单片机/虚拟机/台式/笔记本/微型电脑：浏览器
* Linux Server(RaspBerryOS, Ubuntu, Debian, Centos, Redhat...)+单片机/虚拟机/台式/笔记本/微型电脑：定制程序
* ThinOS(Dell, HP...)+瘦客户端：定制程序 -->

## 连接方式1: APP
适合支持安装APP客户端的系统。   
不同终端系统的APP客户端不同，但操作大同小异，本示例以Andriod手机为例。首先根据系统点击以下对应的链接进行下载安装；
1. [下载APP](/download)，安装APP后打开应用，点击右上角的加号，选择“添加工作区”，外网输入`https://ccg.cec.cc:88`，内网输入`https://cc.cec.cc`，用户账户点击下拉选择“添加用户账户”，输入个人账号`demo@cec.cc`和个人密码并点击保存；
2. 然后点击右上角的“下一步”，等待加载一两秒钟，点击“工作区”，此时会显示所有的应用程序和桌面资源；
3. 点击桌面或应用会弹出一个连接选项框，点击“连接”；
4. 进入桌面或应用后，顶部会出现一个鼠标键盘选项，移动端的鼠标操作分触屏模式和鼠标模式，根据习惯选择对应的模式即可。

:::warning 注意  
APP方式不支持Win7；       
APP方式（Win10 21H2及以上）才支持本地电脑与云电脑的复制粘贴；   
:::

## 连接方式2: 浏览器
适用于所有安装有浏览器的桌面系统。  
支持IE浏览器和H5浏览器，IE浏览器逐步淘汰，这里仅介绍H5浏览器使用，目前主流的浏览器都支持H5：360、Edge、Opera、Chrome、Safari、Firefox浏览器等。
1. H5浏览器只需输入`https://cc.cec.cc`，输入用户名和密码进行登录；  
2. 登陆到资源页面可就以访问远程云应用和云电脑了，部分应用不能支持，可以采用登陆桌面方式进行访问；
3. 点击进入云应用或云电脑，图为H5浏览器的嵌入式访问效果。

:::warning 注意  
用Shift键切换中英文。如果云电脑不支持中文，需要点击右上角“设置”按钮，启用输入法编辑器“开”，回到应用或桌面；  
:::

## 连接方式3: 订阅
仅适用于windows系统。  
1. 控制面板打开RemoteApp与桌面连接；
2. 按照向导输入URL地址，外网输入`https://ccg.cec.cc:88`，内网输入`https://cc.cec.cc`；
3. 最后就可在开始程序菜单直接访问远程应用和桌面。

:::warning 注意  
支持调用云应用访问本地文件；  
支持直接远程打印和本地磁盘访问，打印店远程打印不要保存密码；  
打开第一个云应用或云电脑时需要输入密码。技巧：保持至少一个不关闭，后续打开默认免密；  
:::


<!-- ## 连接方式4: IE浏览器
适用于具有IE浏览器的windows系统。  
Windows终端可以通过IE浏览器连接，实际是系统自带了“远程桌面连接”APP客户端工具，通过浏览器调用工具打开远程应用或桌面。  
注意：WinXP和Win7在非局域网环境下并不支持IE浏览器方式连接，请参照H5浏览器。

1. 打开IE浏览器，地址栏输入`https://cc.cec.cc`，输入用户名和密码进行登录；
2. 首次登录会提示保存密码，点击“是”，方便下次登陆；
3. 首次登录还会提示是否运行加载项，点击“允许”，可以实现更佳访问云应用和云桌面体验；
4. 非同域中电脑首次打开会提示信任发布者提示，勾选“不再询问我是否从此发布者进行远程连接”，可获得更佳的单点访问体验。 -->

## 连接方式4: 定制程序
适用于非桌面系统或者thinos，一般为定制开发，普通用户无需关注。

