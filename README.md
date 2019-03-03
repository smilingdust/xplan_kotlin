# xplan_kotlin
个人业余练习的一个小应用。目的想练习一些主流开源项目的使用，搞一些自己感兴趣但是没有做过的东西，最近一年多比较忙，业余做的功能也少了，xplan借鉴了很多开源项目，所以想开源出来。  
**本项目仅做学习使用，谨慎用于实际项目，拒绝用于商业用途，数据均属于非正常渠道获取，原创公司拥有所有权利。**  
**效果预览：**  
 ![XPlan](https://github.com/JustRight815/XPlan/blob/master/screenshort/%E5%BE%AE%E4%BF%A1%E5%9B%BE%E7%89%87_20171101151455.png) 
 ![XPlan](https://github.com/JustRight815/XPlan/blob/master/screenshort/%E5%BE%AE%E4%BF%A1%E5%9B%BE%E7%89%87_20171101151511.jpg)
 ![XPlan](https://github.com/JustRight815/XPlan/blob/master/screenshort/%E5%BE%AE%E4%BF%A1%E5%9B%BE%E7%89%87_20171101151537.jpg)
 ![XPlan](https://github.com/JustRight815/XPlan/blob/master/screenshort/%E5%BE%AE%E4%BF%A1%E5%9B%BE%E7%89%87_20171101151542.png)
 ![XPlan](https://github.com/JustRight815/XPlan/blob/master/screenshort/%E5%BE%AE%E4%BF%A1%E5%9B%BE%E7%89%87_20171101151546.jpg)
 ![XPlan](https://github.com/JustRight815/XPlan/blob/master/screenshort/%E5%BE%AE%E4%BF%A1%E5%9B%BE%E7%89%87_20171101151554.jpg)
  特点：  
  1.jsoup抓取网页图片和文字信息，利用Recyclerview的瀑布流形式展示，支持下拉刷新，加载更多，快速返回    
  2.点击图片进入浏览大图模式，仿今日头条样式，支持放大缩小，上下滑动图片退出。   
  3.聊天机器人采用图灵接口，展示简单的对话信息。  
  4.支持界面滑动返回，沉浸式状态栏，动态权限处理  
  
 **项目环境**  
 android studio 、kotlin（本来是java项目，部分界面使用kotlin重写）
 
功能列表:
 1、常见功能：Android app启动秒开并避免白屏或黑屏
 2、常见功能：解决Android应用第一次安装成功后Home键切到后台再点击桌面图标应用重启
 3、图片模块：仿电商类app首页复杂布局，瀑布流展示图片。支持下拉刷新，加载更多，快速返回。
 4、图片模块：点击图片进入浏览大图模式，仿今日头条样式，支持放大缩小，上下滑动图片退出。
 5、视频模块：网络视频播放、本地视频播放
 6、头条模块：仿头条新闻
 7、仿今日头条、腾讯新闻界面滑动关闭 下层activity有缩放效果（还在试验中，谨慎用于实际项目）
 8、支持夜间模式（只适配了部分界面，没有时间）
 9、微信支付和支付宝支付封装
 10、jsoup抓取网页图片和文字信息
 11、沉浸式状态栏
 12、动态权限处理  
 13、美团toast优化方案
 16、今日头条适配屏幕方案
 14、zing和zbar结合扫描二维码
 15、X5 webviw使用，原生webview防止内存泄露和漏洞
 16、app字体不随系统字体大小改变
  
   开源项目使用：  
    Retrofit + OkHttp + Gson + glide 
    [BaseRecyclerViewAdapterHelper(ReclerView万能适配器)](https://github.com/CymChad/BaseRecyclerViewAdapterHelper)  
    [statusbarutil 沉浸式状态栏](https://github.com/laobie/StatusBarUtil)  
    [PhotoView  图片浏览](https://github.com/chrisbanes/PhotoView/tree/master)  
    [permissionsdispatcher 动态权限处理](https://github.com/permissions-dispatcher/PermissionsDispatcher)    
    [QSkinLoader  应用换肤，无需重启界面](https://github.com/qqliu10u/QSkinLoader)   
    [bga-swipebacklayout 滑动返回](https://github.com/bingoogolapple/BGASwipeBackLayout-Android)   
    [logger 日志](https://github.com/orhanobut/logger)   
    
    
  
