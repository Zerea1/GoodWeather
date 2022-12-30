![Good Weather](https://github.com/lilongweidev/GoodWeather/blob/master/download/icon_good_weather.png)<br>
<br>
## APP介绍与使用

&emsp;&emsp;本项目没有自己搭建后台，所以自然不会有什么服务器数据库，数据来源于和风天气API，不了解的可以看看我的博客文章，也可以先通过二维码或者下载链接去下载APK体验，使用过程中有问题可以在GitHub上提出，或者在博客中评论。我会在第一时间回复，感谢您的阅读，山高水长，后会有期 ~
   将项目导入到Android Studio 有如下两种方式：
1. 复制 https://github.com/lilongweidev/GoodWeather.git 在AS的导航栏中 VSC → Checkout from Version Control → Git .然后会弹出一个克隆项目的弹窗，粘贴刚才复制的地址，点击弹窗的Clone按钮就可以克隆GitHub上的项目到自己的AS中了。不过这个时候是比较看你的网速的，项目中的很多内容与你本地环境不同，所以需要下载和配置才行。
2. 点击绿色的Code按钮，点击Download ZIP，直接下载压缩包到电脑本地，然后解压，通过AS 的导航栏 File → Open 找到刚才解压之后的文件，然后就是同步和配置即可。

## 答疑

&emsp;&emsp;在Clone源码到本地Android Studio中DeBug运行时，进入地图页面时，发现没有定位或者是无反应，请检查Run下面的日志信息，看有无 "鉴权错误信息" 等字样，如果有的话则说明你需要使用自己项目生成的开发版SHA1,替换掉平台上的应用配置信息，当你看到这个源码之前，你肯定是从博客过来的，那么你可以点击[Android 天气APP（一）开发准备](https://blog.csdn.net/qq_38436214/article/details/105204552)进行百度开发者的账号注册并配置应用，文章里已经讲得很详细了，至于鉴权错误信息的处理你可以通过[Android 百度地图SDK 自动定位、标记定位](https://blog.csdn.net/qq_38436214/article/details/107604267)这篇文章，点击目录“疑问解决”来查看解决方案，祝您使用愉快。

&emsp;&emsp;Windows中GitHub图片显示异常解决方法：打开hosts文件所在目录，C:\Windows\System32\drivers\etc\hosts，默认我们对hosts文件是没有修改权限的，需要开启修改权限，开启修改权限后，用随便用一个编辑器打开，添加的内容请参考这个[hosts](https://github.com/lilongweidev/GoodWeather/blob/master/hosts)文件中最后的部分，对比你的本地进行添加即可。（注意这个开始和结束的标识）

## APP功能描述

&emsp;&emsp;15天天气预报、空气质量、生活建议、出行建议、灾害预警、分钟级降水、城市切换、城市搜索、常用城市、世界国家/地区的城市、壁纸切换、壁纸下载、地图天气、地图搜索定位、每日提醒、语音播报、语音搜索、快捷切换常用城市、应用自动更新、错误监控


## 运行效果图

<div style="width: 100%;
    display: flex;
    justify-content: flex-start;
    align-items: flex-start;
    flex-wrap: wrap;">
<img title="演示GIF" src="https://github.com/lilongweidev/GoodWeather/blob/master/download/demo.gif" width = "25%" height = "480" alt="演示GIF"/>
<img title="每日提醒GIF" src="https://github.com/lilongweidev/GoodWeather/blob/master/download/everyday_tip.gif" width = "25%" height = "480" alt="每日GIF"/>
<img title="分钟级降水GIF" src="https://github.com/lilongweidev/GoodWeather/blob/master/download/precipitation.gif" width = "25%" height = "480" alt="分钟级降水GIF"/>
<img title="壁纸切换GIF" src="https://github.com/lilongweidev/GoodWeather/blob/master/download/wallpaper.gif" width = "25%" height = "480" alt="壁纸切换GIF"/>
<img title="地图搜索定位GIF" src="https://github.com/lilongweidev/GoodWeather/blob/master/download/map_search.gif" width = "25%" height = "480" alt="地图搜索定位GIF"/>
<img title="自动更新GIF" src="https://github.com/lilongweidev/GoodWeather/blob/master/download/auto_update.gif" width = "25%" height = "480" alt="自动更新GIF"/>
<img title="地图天气GIF" src="https://github.com/lilongweidev/GoodWeather/blob/master/download/map_weather.gif" width = "25%" height = "480" alt="地图天气GIF"/>
<img title="灾害预警GIF" src="https://github.com/lilongweidev/GoodWeather/blob/master/download/warn.gif" width = "25%" height = "480" alt="灾害预警GIF"/>
<img title="更多天气预报GIF" src="https://github.com/lilongweidev/GoodWeather/blob/master/download/more_daily.gif" width = "25%" height = "480" alt="更多天气预报GIF"/>
<img title="更多空气质量GIF" src="https://github.com/lilongweidev/GoodWeather/blob/master/download/more_air.gif" width = "25%" height = "480" alt="更多空气质量GIF"/>
<img title="更多生活指数GIF" src="https://github.com/lilongweidev/GoodWeather/blob/master/download/more_lifestyle.gif" width = "25%" height = "480" alt="更多生活指数GIF"/>
<img title="世界城市GIF" src="https://github.com/lilongweidev/GoodWeather/blob/master/download/world_city.gif" width = "25%" height = "480" alt="世界城市GIF"/>
<img title="常用城市GIF" src="https://github.com/lilongweidev/GoodWeather/blob/master/download/commonly_city.gif" width = "25%" height = "480" alt="常用城市GIF"/>
</div>


GIF看不了的，打开下面的视频地址进行观看<br>
[APP演示视频地址](http://m.v.qq.com/play.html?cid=&vid=m3139pttqgo&vuid24=xHi7q3LxeNTsapddk3QYFg%3D%3D&url_from=share&second_share=0&share_from=copy)<br>

## 网址下载

点击下载[好天气APP](http://d.maps9.com/h4sg)<br>

## 扫码下载
![下载图片](https://github.com/lilongweidev/GoodWeather/blob/master/download/code.png)<br>

## 天气APP 博客专栏
[天气APP](https://blog.csdn.net/qq_38436214/category_9880722.html)<br>

## 版本说明
### V 2.9 (最新版本)
* 新版AS正常编译、更新项目版本依赖、去掉ButterKnife，使用ViewBinding<br>
### V 2.8
* 增加友盟+性能监控SDK<br>
### V 2.7 
* 修复UI显示问题、资源图片处理、优化网络请求框架<br>
### V 2.6 
* 优化用户体验，新增快捷切换城市、语音播报、语音搜索功能<br>
### V 2.5
* 分钟级降水、每日提醒<br>
### V 2.4 
* 新版壁纸管理、支持网络图片下载、优化页面UI<br>
### V 2.3 
* 新增地图逐小时天气、日出日落、月升月落、地图搜索定位<br>
### V 2.2
* 新增应用自动更新<br>
### V 2.1
* 新增地图天气<br>
### V 2.0
* 新增灾害预警功能，主页面UI优化<br>
### V 1.9
* 新增更多天气预报、空气质量、生活建议的数据、优化主页UI <br>
### V 1.8
* 更新和风天气V7版API,删除热门城市、新增全球城市。启动页优化，黑白屏处理<br>
### V 1.7
* 增加常用城市列表<br>
### V 1.6 
* 增加国内热门城市<br>
### V 1.5
* 增加海外热门城市、新的天气UI效果<br>
### V 1.4
* 增加搜索城市功能、历史搜索记录<br>
### V 1.3
* 修复相关异常BUG,增加天气详情数据<br>
### V 1.2
* 增加用户体验，允许自己修改背景<br>
### V 1.1
* 七天天气预报、逐小时天气预报、界面UI优化<br>
### V 1.0
* 初始版本、三天天气预报、空气质量、城市切换、生活指数<br>
