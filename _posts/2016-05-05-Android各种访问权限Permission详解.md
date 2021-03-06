---
layout: post
title:  "Android各种访问权限Permission详解"
date:   2016-05-05 18:00:08 +0800
categories: Android
---

转载：[Android各种访问权限Permission详解](http://www.cppblog.com/guojingjia2006/archive/2013/02/18/197911.html)

在Android的设计中，资源的访问或者网络连接，要得到这些服务都需要声明其访问权限，否则将无法正常工作。在Android中这样的权限有很多种，这里将各类访问权限一一罗列出来，供大家使用时参考之用。

 

 

android.permission.EXPAND\_STATUS\_BAR\
允许一个程序扩展收缩在状态栏,android开发网提示应该是一个类似Windows
Mobile中的托盘程序

android.permission.FACTORY\_TEST\
作为一个工厂测试程序，运行在root用户

android.permission.FLASHLIGHT\
访问闪光灯,android开发网提示HTC Dream不包含闪光灯

android.permission.FORCE\_BACK\
允许程序强行一个后退操作是否在顶层activities

android.permission.FOTA\_UPDATE\
暂时不了解这是做什么使用的，android开发网分析可能是一个预留权限.

android.permission.GET\_ACCOUNTS\
访问一个帐户列表在Accounts Service中

android.permission.GET\_PACKAGE\_SIZE\
允许一个程序获取任何package占用空间容量

android.permission.GET\_TASKS\
允许一个程序获取信息有关当前或最近运行的任务，一个缩略的任务状态，是否活动等等

android.permission.HARDWARE\_TEST\
允许访问硬件

android.permission.INJECT\_EVENTS\
允许一个程序截获用户事件如按键、触摸、轨迹球等等到一个时间流，android
开发网提醒算是hook技术吧

android.permission.INSTALL\_PACKAGES\
允许一个程序安装packages

android.permission.INTERNAL\_SYSTEM\_WINDOW\
允许打开窗口使用系统用户界面

android.permission.ACCESS\_CHECKIN\_PROPERTIES\
允许读写访问“properties”表在checkin数据库中，改值可以修改上传。

android.permission.ACCESS\_COARSE\_LOCATION\
允许一个程序访问CellID或WiFi热点来获取粗略的位置

android.permission.ACCESS\_FINE\_LOCATION\
允许一个程序访问精良位置(如GPS)

android.permission.WRITE\_CONTACTS\
允许程序写入但不读取用户联系人数据

android.permission.WRITE\_GSERVICES\
允许程序修改Google服务地图

android.permission.WRITE\_OWNER\_DATA\
允许一个程序写入但不读取所有者数据

android.permission.WRITE\_SETTINGS\
允许程序读取或写入系统设置

android.permission.WRITE\_SMS\
允许程序写短信

android.permission.WRITE\_SYNC\_SETTINGS\
允许程序写入同步设置

android.permission.ACCESS\_LOCATION\_EXTRA\_COMMANDS\
允许应用程序访问额外的位置提供命令

android.permission.ACCESS\_MOCK\_LOCATION\
允许程序创建模拟位置提供用于测试

android.permission.ACCESS\_NETWORK\_STATE\
允许程序访问有关GSM网络信息

android.permission.ACCESS\_SURFACE\_FLINGER\
允许程序使用SurfaceFlinger底层特性

android.permission.ACCESS\_WIFI\_STATE\
允许程序访问Wi-Fi网络状态信息

android.permission.ADD\_SYSTEM\_SERVICE\
允许程序发布系统级服务

android.permission.BATTERY\_STATS\
允许程序更新手机电池统计信息

android.permission.BLUETOOTH\
允许程序连接到已配对的蓝牙设备

android.permission.BLUETOOTH\_ADMIN\
允许程序发现和配对蓝牙设备

android.permission.BROADCAST\_PACKAGE\_REMOVED\
允许程序广播一个提示消息在一个应用程序包已经移除后

android.permission.BROADCAST\_STICKY\
允许一个程序广播常用intents

android.permission.CALL\_PHONE\
允许一个程序初始化一个电话拨号不需通过拨号用户界面需要用户确认

android.permission.DELETE\_CACHE\_FILES\
允许程序删除缓存文件

android.permission.DELETE\_PACKAGES\
允许一个程序删除包

android.permission.DEVICE\_POWER\
允许访问底层电源管理

android.permission.DIAGNOSTIC\
允许程序RW诊断资源

android.permission.DISABLE\_KEYGUARD\
允许程序禁用键盘锁

android.permission.DUMP\
允许程序返回状态抓取信息从系统服务

android.permission.CALL\_PRIVILEGED\
允许一个程序拨打任何号码，包含紧急号码无需通过拨号用户界面需要用户确认

android.permission.CAMERA\
请求访问使用照相设备

android.permission.CHANGE\_COMPONENT\_ENABLED\_STATE\
允许一个程序是否改变一个组件或其他的启用或禁用

android.permission.CHANGE\_CONFIGURATION\
允许一个程序修改当前设置，如本地化

android.permission.CHANGE\_NETWORK\_STATE\
允许程序改变网络连接状态

android.permission.CHANGE\_WIFI\_STATE\
允许程序改变Wi-Fi连接状态

android.permission.CLEAR\_APP\_CACHE\
允许一个程序清楚缓存从所有安装的程序在设备中

android.permission.CLEAR\_APP\_USER\_DATA\
允许一个程序清除用户设置

android.permission.CONTROL\_LOCATION\_UPDATES\
允许启用禁止位置更新提示从无线模块

android.permission.REBOOT\
请求能够重新启动设备

android.permission.RECEIVE\_BOOT\_COMPLETED\
允许一个程序接收到 ACTION\_BOOT\_COMPLETED广播在系统完成启动

android.permission.RECEIVE\_MMS\
允许一个程序监控将收到MMS彩信,记录或处理

android.permission.RECEIVE\_SMS\
允许程序监控一个将收到短信息，记录或处理

android.permission.RECEIVE\_WAP\_PUSH\
允许程序监控将收到WAP PUSH信息

android.permission.RECORD\_AUDIO\
允许程序录制音频

android.permission.REORDER\_TASKS\
允许程序改变Z轴排列任务

android.permission.RESTART\_PACKAGES\
允许程序重新启动其他程序

android.permission.SEND\_SMS\
允许程序发送SMS短信

android.permission.INTERNET\
允许程序打开网络套接字

android.permission.MANAGE\_APP\_TOKENS\
允许程序管理(创建、催后、 z- order默认向z轴推移)程序引用在窗口管理器中

android.permission.MASTER\_CLEAR目前还没有明确的解释，android开发网分析可能是清除一切数据，类似硬格机

android.permission.MODIFY\_AUDIO\_SETTINGS\
允许程序修改全局音频设置

android.permission.MODIFY\_PHONE\_STATE\
允许修改话机状态，如电源，人机接口等

android.permission.MOUNT\_UNMOUNT\_FILESYSTEMS\
允许挂载和反挂载文件系统可移动存储

android.permission.PERSISTENT\_ACTIVITY\
允许一个程序设置他的activities显示

android.permission.PROCESS\_OUTGOING\_CALLS\
允许程序监视、修改有关播出电话

android.permission.READ\_CALENDAR\
允许程序读取用户日历数据

android.permission.READ\_CONTACTS\
允许程序读取用户联系人数据

android.permission.READ\_FRAME\_BUFFER\
允许程序屏幕波或和更多常规的访问帧缓冲数据

android.permission.READ\_INPUT\_STATE\
允许程序返回当前按键状态

android.permission.READ\_LOGS\
允许程序读取底层系统日志文件

android.permission.READ\_OWNER\_DATA\
允许程序读取所有者数据

android.permission.READ\_SMS\
允许程序读取短信息

android.permission.READ\_SYNC\_SETTINGS\
允许程序读取同步设置

android.permission.READ\_SYNC\_STATS\
允许程序读取同步状态

android.permission.SET\_ACTIVITY\_WATCHER\
允许程序监控或控制activities已经启动全局系统中

android.permission.SET\_ALWAYS\_FINISH\
允许程序控制是否活动间接完成在处于后台时

android.permission.SET\_ANIMATION\_SCALE\
修改全局信息比例

android.permission.SET\_DEBUG\_APP\
配置一个程序用于调试

android.permission.SET\_ORIENTATION\
允许底层访问设置屏幕方向和实际旋转

android.permission.SET\_PREFERRED\_APPLICATIONS\
允许一个程序修改列表参数PackageManager.addPackageToPreferred()
和PackageManager.removePackageFromPreferred()方法

android.permission.SET\_PROCESS\_FOREGROUND\
允许程序当前运行程序强行到前台

android.permission.SET\_PROCESS\_LIMIT\
允许设置最大的运行进程数量

android.permission.SET\_TIME\_ZONE\
允许程序设置时间区域

android.permission.SET\_WALLPAPER\
允许程序设置壁纸

android.permission.SET\_WALLPAPER\_HINTS\
允许程序设置壁纸hits

android.permission.SIGNAL\_PERSISTENT\_PROCESSES\
允许程序请求发送信号到所有显示的进程中

android.permission.STATUS\_BAR\
允许程序打开、关闭或禁用状态栏及图标Allows an application to open,
close, or disable the status bar and its icons.

android.permission.SUBSCRIBED\_FEEDS\_READ\
允许一个程序访问订阅RSS Feed内容提供

android.permission.SUBSCRIBED\_FEEDS\_WRITE\
系统暂时保留改设置,android开发网认为未来版本会加入该功能。

android.permission.SYSTEM\_ALERT\_WINDOW\
允许一个程序打开窗口使用 TYPE\_SYSTEM\_ALERT，显示在其他所有程序的顶层

android.permission.VIBRATE\
允许访问振动设备

android.permission.WAKE\_LOCK\
允许使用PowerManager的 WakeLocks保持进程在休眠时从屏幕消失

android.permission.WRITE\_APN\_SETTINGS\
允许程序写入API设置

android.permission.WRITE\_CALENDAR\
允许一个程序写入但不读取用户日历数据

可以看出Android中对资源以及服务的访问都非常严格，另外，在程序打包成APK的时候也需要对软件进行签名。
