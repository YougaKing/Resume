### 联系方式

* 手机：15339149065
* Email：yougakingwu@gmail.com
* QQ/微信号：451477973

---

### 个人信息

* 吴华友/男/1990
* 工作年限：3年
* 技术博客：https://yougaking.github.io
* GitHub：https://github.com/YougaKing
* 期望职位：Android开发工程师
* 期望薪资：税前月薪10k~12k
* 期望城市：西安

---

### 工作经历
#### 西安群花网络科技有限公司 （ 2017年3月 ~ 2017年9月 ）

##### 花花星球-Android客户端

###### 花花星球是一款私密秀场直播软件

###### 项目职责：

* 接入金山云KSYStreamer对Android端音视频数据采集、处理、推流以及主播美颜滤镜
* 接入金山云KSYMediaPlayer对Android端音视频数据拉流、编码及播放
* 集成Agora的Native接口，辅播通过KSYStreamer采集本地音视频数据发送给声网服务器,主播接受声网服务器的音视频数据和本地音视频数据合成在推至服务器完成连麦功能
* 利用属性动画ObjectAnimator实现直播间快速的连击动画效果,利用fresco显示直播间webp动画(反编译UP直播/YY直播/映客直播获取动画素材,利用libwebp对webp文件进行拆分、压缩计算时长)
* 利用webSocket协议实现直播间聊天、刷礼物、摇色子、抽奖等互动,利用Ping、Pang机制实现断线重连
* 接入融云IMKIT实现即时聊天功能,自定义消息,会话界面,实现自主好友体系
* 接入微信/QQ登陆,微信/微博/QQ分享,微信支付宝支付，http请求利用PARAMKEY对参数加密
* 适配Android M的Runtime Permission,使用FileProvider 适配Android N文件操作

#### 西安菜瓜软件科技有限公司 （ 2015年1月 ~ 2017年3月 ）

##### 结婚小秘书-Android客户端

###### 结婚小秘书是为婚纱影楼行业客户服务，提供订单展示、进度通知、服务评价、婚姻登记处查询、喜帖/微相册制作分享，婚庆话题讨论、婚品购买，婚礼事宜流程、酒店预订等各项服务。

###### 项目职责：

* 负责项目的前期框架搭建，Beta版本开发测试打包混淆发布各应用市场
* 对引入的开源框架进行抽象封装,自定义一些View
* 不断重构解决项目需求变动频繁留下大量冗余代码和资源文件,优化布局文件,协同同事制定一些规范和讨论需求
* 负责婚庆话题社区模块、在线选择摄影师模块、喜帖制作模块、结婚吉日模块、阿里妈妈婚品商城集成、优酷视屏播放集成，微信分享、支付宝/微信支付
* 优化项目中大量图片展示/频繁操作图片所引起的内存不足而崩溃，排查解决内存泄漏大幅度降低OOM发生的几率，排查解决界面卡顿问题。
* 适配Android M的Runtime Permission,使用FileProvider 适配Android N文件操作。
* http升级https双向认证,采用AES对数据加密解密以及CRC校验
* 利用AIDL加文件共享与影楼大管家之间通讯,结婚小秘书评价时判定是否可能是员工身份,记录评价次数并上传可疑员工信息至服务端

##### 影楼大管家-Android客户端

###### 影楼大管家是为婚纱影楼行业定制的ERP-CRM-OA软件，根据员工的权限给予不同的操作模块，提供开单、流程转交、任务安排、收银、业务统计、考勤、单点登录等功能

###### 项目职责：

* 项目从零开始到各版本迭代，个人全权负责Android客户端的开发。
* 利用UUID+Jpush推送实现单点登录功能，统一登录异常验证机制
* 开发工具从Eclipse转换成AndroidStudio，项目版本控制也从Svn换成Git
* 集成Jpush推送、Umeng统计、amap高德地图定位服务、 zxing扫码。
* 适配Android M的Runtime Permission,使用FileProvider 适配Android N文件操作。
* http升级https双向认证,采用AES对数据加密解密以及CRC校验
* 利用AIDL加文件共享与结婚小秘书之间通讯,结婚小秘书评价时判定是否可能是员工身份,记录评价次数并上传可疑员工信息至服务端


##### 其他项目

影楼全掌控app（为影楼老板提供业绩统计、考勤统计、订单渠道统计等功能）, 三秦全搜索app(网络抓取设置的关键字，筛选负面新闻推送，提供各给陕西各县 行政官员使用)。


#### 芜湖时间图网络技术有限公司 （ 2014年2月 ~ 2014年11月 ）

##### 时间图-Android客户端

###### "时间图"是一个集合大型信息的社交应用,以时间系统为主要特点,以百科类目、国家地域、事件人物为纬线，描绘“时间之图”。

###### 项目职责:

* 引导页面完成了对SharePreference的存值与读取,使用了ViewPager + ViewPager + Fragment嵌套进行显示,部分UI界面绘制结合ButterKnife进行对界面资源的注入,使用ormlite管理SQLite存储信息以及增删改查
* Activity和Fragment的生命周期以及以及数据交互,ormlite的使用以及数据库升级和数据备份

---

### 开源项目和作品

#### 开源项目

* DragRecyclerView：RecyclerView 加载更多，可搭配SwipeRefreshLayout 下拉刷新，支持EmptyView loading error 图片文字可自定义，支持 LinearLayoutManager GridLayoutManager StaggeredGridLayoutManager。
* ImageSelector：适配android 7.0权限，支持拍照.相册选择.图片裁剪

#### 技术文章

* android调用系统相机拍照总结调用系统相机的知识，文件操作所需权限，解决AndroidNougat所引起的BUG
* EditText Keyboard 未解之谜 总结EditText弹起Keyboard相关的知识，分析 部分机型无法正确弹起Keyboard的原因
* 农历的那些事儿 程序猿需要懂得的农历知识，了解农历的由来，程序猿需要懂得的农历知识
* 贪吃蛇大作战-刷分-反编译 http/https请求抓包，分析.so文件库的安全，汇编工具IDA Pro使用

---

### 技能清单

* 熟悉butterknife/dagger/retrofit2/okhttp/rxjava/gson/glide/Picasso/facebook..各类Android开发框架
* 开发工具：Eclipse/AndroidStudio
* 数据库相关：SQLite
* 版本管理、文档和自动化部署工具：Svn/Git
* 单元测试：junit/mockito/espresso
* 熟悉Android事件分发机制，View绘制流程、自定义控件和动画等。

致谢

感谢您花时间阅读我的简历，期待能有机会和您共事。

