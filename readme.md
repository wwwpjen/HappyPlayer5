# 简介 #
乐乐音乐6.0主要是基于ijkplayer框架开发的Android音乐播放器，它支持多种音频格式和动感歌词，界面高仿酷狗。

# 开发环境 #
- android studio 3.1.4（正式版）
- gradle-4.4
- 小米2s手机
- android 5.0系统以上

# 音频格式 #
目前用ijkplayer来测试如下音频格式，均可正常播放：aac，amr，ape，flac，m4r，mmf，mp2，mp3，ogg，wav，wma，wv

# 歌词格式 #
- lrc：普通歌词
- krc：酷狗歌词
- ksc：卡拉OK歌词
- hrc：happy lyrics歌词，乐乐音乐自定义的动感歌词格式，可准确到歌词每个字。

# 项目中抽出来的开源控件 #

- [SwipeBackLayout（右滑动关闭界面）](https://github.com/zhangliangming/SwipeBackLayout.git)
- [RotateLayout（旋转界面）](https://github.com/zhangliangming/RotateLayout.git)
- [SeekBar（进度条）](https://github.com/zhangliangming/SeekBar.git)
- [HPLyrics（动感歌词解析和歌词显示库）](https://github.com/zhangliangming/HPLyrics.git)
- [HPAudio（音频解析库）](https://github.com/zhangliangming/HPAudio.git)
- [Android仿酷狗SlidingMenuLayout界面实现](https://github.com/zhangliangming/SlidingMenuLayout.git)
- [ijkplayer依赖包（支持无损）](https://github.com/zhangliangming/Player.git)

# 第三方控件/框架 #

- bugly：崩溃日志收集
- [SwitchButton：开关按钮](https://github.com/zcweng/SwitchButton.git "SwitchButton")
- [LeakCanary：日志泄露分析](https://github.com/square/leakcanary "LeakCanary")
- [Utils-Everywhere](https://github.com/SenhLinsh/Utils-Everywhere.git "Utils-Everywhere")
- [greenDAO：sqlite数据库框架](https://github.com/greenrobot/greenDAO "greenDAO")
- [jjdxm_dialogui：弹出窗口框架](https://github.com/jjdxmashl/jjdxm_dialogui/ "jjdxm_dialogui")
- [LRecyclerView：RecyclerView上拉加载更多，下拉刷新](https://github.com/jdsjlzx/LRecyclerView "LRecyclerView")

# 更新日志 #

## 2018-12-22 ##
- 添加下载页面、添加列表更多菜单功能

## 2018-12-16 ##
- 添加最近和喜欢歌曲列表

## 2018-12-08 ##
- 添加锁屏歌词
- 修复通用跳转权限设置页面

## 2018-12-02 ##
- 添加桌面歌词

## 2018-11-27 ##
- 添加通知栏

## 2018-11-25 ##
- 添加歌词搜索、定时关闭

## 2018-11-18 ##
- 线控
- 修复歌手写真、写真搜索

## 2018-11-13 ##
- 添加歌词字体大小修改及颜色修改

## 2018-09-24 ##
- 添加新歌、排行和歌单列表

## 2018-08-27 ##
- 修复状态栏半透明的问题
- 修复全面屏的问题


## 2018-08-19 ##
- 添加设置和关于页面
- 添加弹出窗口

## 2018-08-18 ##
- HttpClient添加https支持(忽略证书)
- 添加greenDAO框架处理数据库

## 2018-08-13 ##
- 添加了SlidingMenuLayout（侧边栏，viewpager）
- 添加了酷狗的api
- 优化了单个任务多个线程下载代码

# 传送门 #

- [ijkplayer开源框架](https://github.com/Bilibili/ijkplayer "ijkplayer开源框架")
- [Hrc/hrcx歌词制作器（播放器）](https://github.com/zhangliangming/HappyPlayer-PC.git "Hrc/Hrcx歌词制作器（播放器）")
- [浅谈动感歌词](http://zhangliangming.github.io/ "浅谈动感歌词")
- [Kugou-api](https://github.com/ecitlm/Kugou-api "Kugou-api")

# 声明 #
仅用于学习用途

# License #

Apache 2.0. See the [LICENSE](https://github.com/zhangliangming/HappyPlayer5/blob/happy_player6/LICENSE) file for details.

# 捐赠 #
如果该项目对您有所帮助，欢迎您的赞赏

- 微信

![](https://i.imgur.com/l39CVlp.png)

- 支付宝

![](https://i.imgur.com/HutwPUX.png)
