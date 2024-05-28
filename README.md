# cefsimple

基于cef_binary_119.4.3-gc76a3b9-chromium-119.0.6045.159_windows64[下载地址](https://cef-builds.spotifycdn.com/index.html#windows64:119.4.3)，修改cefsimple，用于Qt程序嵌入。
修改内容如下：
1、通过标准输入输出设备与主进程通信，在接收到主进程指令后进行相关操作；
2、禁用web页面右击菜单；
3、单页面加载，禁用弹出新的页面；
