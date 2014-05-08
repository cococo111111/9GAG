﻿9GAG-Android (unofficial)
9GAG 安卓客户端个人版
=====================

9GAG安卓客户端，遵从Android Design

作者大三学生一枚，详见about页面，有意合作或其他事宜请联系邮箱哦。
个人Email: chyechye@foxmail.com
	
###图赏
![NineGag](https://raw.github.com/Mixiaoxiao/9Gag/master/Screenshots/device-all.jpg)
	
###几个特点：
1.完美的支持安卓4.4的TranslucentStatus与TranslucentNavigation特性，并适当给通知栏与导航栏着色使得整个界面更和谐<br />
2.个人改进的支持刷新的ListView，顶部与底部使用带进度的圆形表示拉动状态<br />
3.查看大图使用精确的坐标缩放动画，并使用渐现的高斯模糊背景衬托，图片drawable裁剪遵循“横向充满，长图顶部对齐”规则<br />
4.tab栏没有使用actionBar自带的tab功能，使用PagerSlidingTabStrip（gitHub开源项目），支持了tab指示条的跟随ViewPager滑动而滑动<br />
5.tab栏支持“QuickReturn”效果<br />
6.基本完整style化的ActionBar<br />
7.ActionBar标题字体自定义<br />
8.Toast自定义<br />
9.支持分享图片+文本，经测试微信与微博均可正常接收图片与文本信息，不排除有些应用只可获得图片或文本单一分享内容<br />
10.自定义activity切换动画与安卓4.4完全一致<br />

###新增翻译
使用有道翻译openApi，代码中的key请勿用做其他用途！！<br />
翻译结果本地数据库保存<br />
大图页的标题点击可以选择单词进行翻译<br />

###关于Mxx开头的java类
Mxx为Mixiaoxiao的缩写，大部分Mxx开头的Java为个人原创<br />

###关于gif图
使用了第三方的接口，不支持gif源地址获取<br />
但在ImageFragment.java的checkGif()方法中已经完全实现了gif的下载保存与显示功能<br />

###其他说明
修正了aFinal框架的db不支持多数据库文件同时存在同个bean的表的问题，修正的bitmap模块抛出runtime异常的问题<br />
SwipeBack与4.4的透明通知栏与导航栏不兼容，舍弃不用。<br />