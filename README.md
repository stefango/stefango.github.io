<link href="/assets/public/css/APlayer.min.css" rel="stylesheet">
<script src="/assets/public/js/APlayer.min.js"></script>
<style>
  .aplayer {
  max-width: 700px;
  margin:0px auto 0px auto;
</style>
<div class="aplayer">
<div id="player1"></div>
</div>
<!-- 如果是放在.md文件内则将js 的内容插在<script>中 -->
<script>
const ap = new APlayer
({
    container: document.getElementById('player1'),
    autoplay: false,
  volume: 0.5,
  mini: false,
  preload: 'auto',
  mutex: true,
  listFolded: false,
  listMaxHeight: 90,
  loop: 'all',
  order: 'list',
    audio: [{
    title: '心拍数♯0822',
    author: 'H△G',
    url: '/music/%E5%A3%B0%20~VOCALOID%20Cover%20Album~/H%E2%96%B3G%20-%20%E5%BF%83%E6%8B%8D%E6%95%B0%E2%99%AF0822.mp3',
    pic: '/music/%E5%A3%B0%20~VOCALOID%20Cover%20Album~/cover.jpg'
    },
  {
    title: 'Freesia',
    author: '(K)NoW_NAME,Ayaka Tachibana',
    url: '/music/SAKURA%20QUEST%20BEST/(K)NoW_NAME,Ayaka%20Tachibana%20-%20Freesia.mp3',
    pic: '/music/SAKURA%20QUEST%20BEST/cover.jpg'
    },
    {
    title: '渡月橋 〜君 想ふ〜',
    author: '倉木麻衣',
    url: '/music/%E6%B8%A1%E6%9C%88%E6%A9%8B%20%E3%80%9C%E5%90%9B%20%E6%83%B3%E3%81%B5%E3%80%9C/%E5%80%89%E6%9C%A8%E9%BA%BB%E8%A1%A3%20-%20%E6%B8%A1%E6%9C%88%E6%A9%8B%20%E3%80%9C%E5%90%9B%20%E6%83%B3%E3%81%B5%E3%80%9C.mp3',
    pic: '/music/%E6%B8%A1%E6%9C%88%E6%A9%8B%20%E3%80%9C%E5%90%9B%20%E6%83%B3%E3%81%B5%E3%80%9C/cover.png'
    },]
});
ap.init();
</script>

# 2018-2019-1

## 许子立本周主要工作

- 一是使用Xshell配置AWS EC2（CentOS7+Tomcat7+Java 1.7）
- 二是编写<a href="http://54.169.47.114:8080/LabFirst/">实验室网页</a>
- 三是提交大创项目中期报告

## 下周工作打算

- 一是了解如何在树莓派上配置Nginx服务器并部署网站
- 二是继续学习<a href="https://www.imooc.com/video/5553">Web开发</a>

## Week 5

- 学习[python爬虫](https://www.bilibili.com/video/av31697253?share_medium=android&share_source=qq&bbid=EChJfRh8Hnoffk1_AzEDMQMxUzUCZgU0A38Dinfoc&ts=1538295452321)，使用pip安装python第三方包[requests](http://docs.python-requests.org/en/master/api/#requests.Response)、lxml，了解[Python 编码规范(Google)](https://www.runoob.com/w3cnote/google-python-styleguide.html)
- 完善JSP/Servlet实验四“Servlet动态表单”
- 配置Amazon RDS for MySQL，并使用Navicat连接
- 潭州python群548377875：课件+screenShot.py
- JS登录验证、定时器setInterval()的使用

## Week 6

- 周六下午四点去办公室录入国励信息
- 室长名单统计周日中午前发给2679885223@qq.com
- [Struts1.x学习](http://edu.51cto.com//center/course/lesson/index?id=54146)、JSP实验五

## Week 7

- 周一朱海霞入学教育重修报名（已报，周三扣费）

- 周五找周荣打印谈话

- 备份照片DCIM/Pictures/PicsArt、便签、软件、WPS文件

- 卡刷方法：第一步：备份好手机资料后，进入设置——其他高级设置(更多设置)——备份和重置，重置手机，清空手机上的所有数据；第二步：复制以下网址（<http://www.miui.com/download.html>）在您手机自带浏览器里面打开，选择对应的手机型号进入，选择开发板，然后下载到手机上。第三步：下载完后，进入手机设置——关于手机——点系统更新——选择右上角的三个小白点——手动选择安装包——找到名字为Download文件夹，进入后选择您刚才下载的卡刷包，打开即可卡刷系统。第四步：开启卡刷后一般需要10~25分钟时间卡刷，这段时间不要关机，不要做任何操作，等待卡刷完成后重启手机，重启手机的过程会稍为长一点，需要耐心等待。卡刷完成后再看看手机还有没有异常情

- 本地备份：在设置-更多设置（其他高级设置）-备份与重置-本地备份-新建备份，选中全部数据进行备份。（第三方软件的聊天记录、软件数据或其他重要数据请自行备份，完成本地备份后，将手机存储中“MIUI/backup/AllBackup”路径下的备份文件拷贝至电脑中。把照片，视频，音乐，文件等数据也都备份到电脑中的，待刷机完成后，可将这个文件夹原路径复制回手机，在“本地备份”中进行数据恢复。其他的文件也可以再拷贝回手机中的 

- 证书、义工申请PU，第二课堂，学分需要共160分，活动类需要70-100分。申请类需大于60分，活动类是平时扫PU的得分，申请类需要申请，社会实践，党校毕业证，六级可以申请，申请审核人填班主任，需在11月10日前完成（义工自动申请）

- jdk安装docker pull hub.c.163.com/tonight/oracle_jdk_1.8_131:131

- C:\Windows\system32>bcdedit /copy {default} /d "Windows 10 VMware"
  已将该项成功复制到 {5968edc6-d33e-11e8-a2a6-3497f6b7d2e4}。

  C:\Windows\system32>bcdedit /set {5968edc6-d33e-11e8-a2a6-3497f6b7d2e4} hypervisorlaunchtype off
  操作成功完成。

## Week8

- JSP实验报告（第10周结束）、课程设计（第8-11周）
- Oracle实验三
- 大创结项报告

## Week9

- JSP实验七、实验八，课程设计（第8-11周）：用户的增删改查
- Oracle实验三

## Week10

- JSP课程设计：用户搜索、过滤器、登录session验证
- Oracle实验三、考试

- 了解神经机器翻译 

  + [(Neural Machine Translation）系列教程 - （一）神经机器翻译-开源项目](https://blog.csdn.net/shijiandehaizi/article/details/74930507)

  - [我爱自然语言处理](http://www.52nlp.cn/)

  + [机器翻译自动评估-BLEU算法详解](https://blog.csdn.net/qq_31584157/article/details/77709454)

  - [知晓程序-腾讯翻译君-经BLEU评测翻译质量行业领先](https://minapp.com/miniapp/3410/)

- 无序序列的前缀-+*(使用不同前缀进入子序列)

```java
system.out.print("Hello");
system.out.print("Hello");
system.out.print("Hello");
system.out.print("Hello");

setTimeout(function(){
    window.parent.location.reload();//修改成功后刷新父界面
}, 1000);
```

## Week11

- JSP课程设计、报告
- Oracle实验四、实验五
- 管理沟通公选课作业

## Week12

- Layui全文排序问题（已解决：检查重载后的传参变化，更改后台SQL语句）
- JSP课程设计、报告、JavaEE实验一
- 管理沟通公选课作业、期末考试

## Week13

- Oracle实验四、实验五（未交）
- Java将文字写入图片（验证码）
- 联系信息办SSL证书、AJAX // 相对协议
- UML做PPT

## Week14

- 管理沟通公选课作业、期末考试(12月5日-2018年12月16日 23:30公布成绩)

- 提交Oracle实验五（已交）、完成实验六

- JavaEE实验三(\* IOC（控制反转）是利用java的反射思想实现的

  \* DI（依赖注入）是利用java的内省机制实现)

- 16周提交软件项目的组员报告

## Week15

- 周一打印JSP课程设计
- 周三中午12：40入学教育N6-102
- 周四课上测试数据库对象操作部分
- 蓝桥杯资质认证、报名B组Java（算法竞赛（入门经典））

## Week16

- [x] 周三今晚设计ASCC数据库(**不需要用户表**、`站内文章表、文章类别表、项目表、团队成员表、合作伙伴表、站内基本信息表`)、询问ui设计进度、前端页面下周一
- [x] JavaEE实验二、实验三、期中代码提交（已交）
- [x] UML提交笔记（周五中午12点）
- [x] 17周周一周二javaee加两节实验课进行期末课程设计答辩，课程设计报告（20+页）17周结束交齐。所有实验四、五、六18周前交齐（报告中不需要贴代码）。
- [x] Oracle实验六（已交）、两千字读书报告（17周交）
- [x] 第9P 9. 尚硅谷_佟刚_Spring_SpEL
- [x] 谢世豪内务整改（周一收齐）
- [x] CSDN收藏 [MyBatis的Mapper接口以及Example的实例函数及详解](https://blog.csdn.net/biandous/article/details/65630783)

## Week17

- [x] JavaEE实验四、五、六
- [x] 软件项目测试复习（1月3日）
- [x] Oracle复习（1月7日）
- [x] ASCC网页后台管理

## Week18考试信息

|      课程名称      |        开始时间        |   考试地点   |
| :----------------: | :--------------------: | :----------: |
| 软件过程与项目管理 | 2019-01-03 13:30-15:30 | 六艺楼S5-201 |
|  Oracle数据库应用  | 2019-01-07 10:10-12:10 | 九章楼N4-102 |
|                    |                        |              |

## Week19

- [x] 开展苏州项目，辅助前端开发，需要用到C#
- [x] 雷达-院级大创结项报告
- [x] 借SpringInAction、PHP-Laravel的书(视频: PHP Laravel Vue.js 视频教程 - CODECASTS、[php开发知乎视频](https://github.com/JellyBool/zhihu-app))、续借三本书、020尚硅谷VUE核心技术视频
- [x] [安装 LEMP 环境 （PHP7）](https://www.codecasts.com/series/deploy-laravel-app-on-vps/episodes/2)
- [ ] coursera-algorithm和Java程序设计、啊哈算法
- [ ] 基于JWT标准的用户认证接口实现
  https://www.xiaohuochai.cc/posts/5b02978325115949d4b67eae
- [ ] Java 算法竞赛（入门经典）

# 大三寒假

- [ ] 华东师范大学(专硕数二+英二+数据结构)何积丰院长即将退休，资源扩散，软件招生名额减少
  - 魅影·啸月(376652106)
  - 1.院系调整，华师软件砍了30%的名额，大部分给了华师计科；而且华师软件目前仅剩了冷门方向
  - 2.华师计科偏向acm选手，acm有经验的推荐计科，因为华师计科机试占比很大，好坏能拉初试20分左右
  - 常年软件三百来人，计科一百来人复试
- [ ] 中国人民大学高瓴**líng**人工智能学院2021改408，2020过渡期
- [ ] 苏州大学(专硕数二+英二+数据结构与操作系统)、华东理工大学、上海大学、东南大学（含苏州研究院）、江南大学(不保护一志愿、徐少杰说专业课压分)、杭电、武汉大学(ABCD卷、D卷360+才稳)、19华科学硕扩招(？)、中科院信工所（290+）、cskaoyan、南师大
- [ ] 东华大学(夏令营降十分录取、计算机应用系：[黄永锋(副教授)Web开发](http://cst.dhu.edu.cn/62/85/c3131a25221/page.htm)、计算机软件与理论系：陈德华(副教授)][黄秋波(副教授)JavaEE、SSH](http://cst.dhu.edu.cn/62/37/c3132a25143/page.htm)
- [ ] 东北石油大学联合培养（1年在东北石油大学、1年在常熟理工）、日本九州工业大学
- [x] 主要：主页、个人中心
- [x] 次要：购买页面、新闻公告、新闻页面

# 2018-2019-2

## Week1

- [x] PHP实验一
- [x] 软件测试实验一
- [x] 设计模式实验一
- [x] 蓝桥杯Java训练

##  Week2

### Weekdays

- [x] 安卓实验一
- [x] VS编写C需要在return 0之前添加system("pause")
- [x] 看屠皓民考研英语书P1-P20
- [x] 安卓机房的实验二导入本机IDEA时，需要设置Project Structure的Project SDK为API21，SDKs也要查看一下，点击Edit Configurations并新增Android App结束后，若遇到The activity must be exported or contain an intent-filter，则在AndroidManifest.xml中android:exported="true"。
- [x] 咨询程浩老师普通高中分数线是否包含体育和理化生分数，给程浩老师开发查分网站
### Saturday

- [x] 上午熟悉各大考研机构的高数视频
- [x] 下午练英语字帖一页

## Week3

- [x] php实验二
- [x] 晚上六级真题模拟（30min一篇阅读理解正确率：4/5）
- [x] 第一讲 极限的定义（讲义P3~7）
- [x] 汤加凤1、2、3、4（11:30）
- [x] 咨询殷旭东老师IP、宿舍垃圾袋带过来、16个义工
- [x] 安卓实验二
- [x] 1月24日-函数的概念、1月25日-函数的特性、1月26日-数列极限
- [x] [b站数据结构与算法基础-java版](https://www.bilibili.com/video/av33835237) 
  - [P11.1数据结构概述](https://www.bilibili.com/video/av33835237/?p=1)
  - [P21.2算法概述](https://www.bilibili.com/video/av33835237/?p=2)
  - [P32.1数组的基本使用](https://www.bilibili.com/video/av33835237/?p=3)
  - [P42.2数组元素的添加](https://www.bilibili.com/video/av33835237/?p=4)
  - [P52.3数组元素的删除](https://www.bilibili.com/video/av33835237/?p=5)
  - [P62.4面向对象的数组](https://www.bilibili.com/video/av33835237/?p=6)
  - [P72.5查找算法之线性查找](https://www.bilibili.com/video/av33835237/?p=7)

## Week4

- [x] [考研数学零基础教材精讲班-高昆轮](https://www.bilibili.com/video/av18866922)
  - [P104.第一章 第二节 数列的极限](https://www.bilibili.com/video/av18866922/?p=1)
  - [P205.第一章 第三节 函数的极限](https://www.bilibili.com/video/av18866922/?p=2)
  - [P3P3](https://www.bilibili.com/video/av18866922/?p=3)
  - [P407.第一章 第五节 极限运算法则](https://www.bilibili.com/video/av18866922/?p=4)
- [x] [b站数据结构与算法基础-java版](https://www.bilibili.com/video/av33835237) 
  - [P82.6 查找算法之二分法查找](https://www.bilibili.com/video/av33835237/?p=8)
  - [P92.7查找算法整合](https://www.bilibili.com/video/av33835237/?p=9)
  - [P102.8栈](https://www.bilibili.com/video/av33835237/?p=10)
- [x] 周五上午训练蓝桥杯Java
- [x] 周日上午蓝桥杯比赛、下午六级听力

## Week5

- [ ] 曹政百度云、闲鱼卖家百度云
- [x] 周一、周二：扇贝网听力练习、201606CET6阅读真题(①80分钟做了202.35分；②45分钟做了213分)、准备6月份六级考试(当前时间不在学籍校区网上报名时间(`周二`2019-03-26 13:00 至 2019-04-04 23:55)内,无)
- [x] 陈正康英语Unit1
- [ ] 递归、DFS及有向DFS
- [x] 安卓作业二
- [x] 软件测试实验二（已完成个人作业、还有小组作业没写）
- [x] 设计模式实验二
- [x] 处理百度云盘重复文件
- [x] [考研数学零基础教材精讲班-高昆轮](https://www.bilibili.com/video/av18866922)
  - [P508.第一章 第六节 极限存在法则、两个重要极限](https://www.bilibili.com/video/av18866922/?p=5)
  - [P609.第一章 第七节 无穷小的比较01](https://www.bilibili.com/video/av18866922/?p=6)
  - [P710.第一章 第七节 无穷小的比较02](https://www.bilibili.com/video/av18866922/?p=7)
  - [P811.第一章 第八节 函数的连续性与间断点](https://www.bilibili.com/video/av18866922/?p=8)
  - [P912.第一章 第九节 连续函数的运算和函数的连续性](https://www.bilibili.com/video/av18866922/?p=9)
  - [P1013.第一章 第十节 闭区间上连续函数的性质](https://www.bilibili.com/video/av18866922/?p=10)

## Week6

- [x] 安卓实验三
- [x] 设计模式实验三
- [x] 4月23日(周二)还书

## Week7

- [x] [考研数学零基础教材精讲班-高昆轮](https://www.bilibili.com/video/av18866922)

  - [P1114.第二章 第一节 导数与微分01](https://www.bilibili.com/video/av18866922/?p=11)

  - [P1215.第二章 第一节 导数与微分02](https://www.bilibili.com/video/av18866922/?p=12)
- [P1316.第二章 第二节 函数的求导法则](https://www.bilibili.com/video/av18866922/?p=13)
  - [P1417.第二章 第三节 高阶导数](https://www.bilibili.com/video/av18866922/?p=14)
  - [P1518.第二章 第四节 特殊函数的导数](https://www.bilibili.com/video/av18866922/?p=15)
  - [P1619.第二章 第五节 函数的微分](https://www.bilibili.com/video/av18866922/?p=16)
  
- [x] 设计模式实验四

- [x] 20190411实验课老师代码

- [x] 汤家凤第二章P11-16


## Week8

- [x] 电子商务期中作业4k字
- [x] 复习php的PPT，第九周期中考试
- [x] 复习2019年4月18日代码、安卓理论作业3、实验四部分完成
- [x] 周末体测，:smile:
- [x] 子悦智慧后勤申请校级大创
- [x] 周日晚更新周报 `week8 over`（实际拖到了第九周的周一😭）


## Week9

- [x] 复习php的PPT，第九周期中考试
- [x] 安卓期中考试-申请周二和1班一起考
- [x] 五一之后软件测试期中
- [x] 周三设计模式期中
- [x] 杨明珠简历
- [x] 奇数天健身

## Week12

- [x] 电子商务实验五
- [ ] ~~php实验四~~，知乎，发布博文图片，邮件订阅，关注用户，评论(搁置)
- [x] 设计模式实验五
- [x] ~~安卓完善理论作业3和实验四、imooc的BaseAdapter视频、4月25日安卓代码、5月9日安卓代码~~、myapp_4_16 RecyclerView导包
- [x] 软件测试实验三
- [x] 东华大学2020夏令营(5月13日发布)
- [x] 支付宝报销住院费用
- [x] 打印助学贷款申请表(下载目录中)
- [x] 续借至2019-06-17

## Week13

- [x] 安卓：~~作业4、实验5（周日之前交）~~、[Android应用项目中BaseAdapter、SimpleAdapter和ArrayAdapter中的三种适配器](https://www.cnblogs.com/demoMeng/p/6115289.html)、大作业（17周）、[okhttp-post](https://raw.githubusercontent.com/square/okhttp/master/samples/guide/src/main/java/okhttp3/guide/PostExample.java)
- [x] 软件测试：实验四Junit（周五之前交）
- [x] 设计模式：实验六、实验七

## Week14

- [x] php：[PHP数据库utils](https://www.cnblogs.com/woider/p/5875262.html)

  ①Vue-cli项目打包后，发布到容器子目录`projectName`下，需要对项目作出两处修改：一处是在`config/index.js`的`build`下面修改`assetsPublicPath: '/'`改为`assetsPublicPath: './'`，一处是在`src/router/index.js`的`Router`下面新增`base: '/projectName/'`。最后，可以通过`http://域名/projectName`来访问项目了。

  注：`Router`的 `mode: 'history'`可以去掉#号，但是会导致发布后的项目在刷新的时候报404。

  ②当Vue-cli项目的生产版本和发布版本调用的api不同时，我们可以在`build/webpack.dev.conf.js`和`
  build/webpack.prod.conf.js`中分别添加键值对`API_ROOT: '"http://127.0.0.1/dev_api"'`和`API_ROOT: '"http://domainname/prod_api"'`，此时你会发现在vue组件中使用的`process.env.API_ROOT`是`undefined`，`console.log(process.env)`只显示`{NODE_ENV: "development"}`。原因是修改webpack配置后，需要重启项目才能生效，然而CSDN的这位网友并未阐明:cry:
  
  ref: https://blog.csdn.net/u014054437/article/details/82970725#commentBox

- [x] 安卓：~~`xzl_5_28`的`MainActivity`无法获取`xzl_5_30`的`ContentProvider`（原因：注意修改`AndroidManifest.xml`中`provider`的`android:authorities`）、作业5、实验六~~、BottomNavigationView底部导航


## Week15

- [x] 周一向周荣提交剩余的4份宿舍卫生检讨书
- [x] PHP：实验五？、final医生处理病人、病人查看预约信息、完善主页信息、添加新闻管理、解决头像为空、[MySQL定时任务](https://blog.csdn.net/sinat_27933301/article/details/85948162)、[10秒带你实现图片上传到服务器](https://github.com/surmon-china/vue-quill-editor/issues/135)
- [x] 安卓：final-提交时间：2019.6.20晚，答辩时间：2019.6.21上午8：00-10：30 N6-103
- [x] 软件测试：实验五、实验报告
- [x] 找王学宇成绩单盖章
- [x] 设计模式：实验八
- [x] [常规问题解决：File "/usr/bin/yum", line 30 及 File "/usr/libexec/urlgrabber-ext-down", line 28](https://www.cnblogs.com/Trees/p/7497268.html)

## Week16

- [x] CET6：201812-1、201812-3、周六下午三点考试(准考证、眼镜、身份证、手表、橡皮、铅笔、中性笔、耳机)

- [x] 安卓：作业六、实验七（周四前提交）

- [x] 电子商务：final（周五前）

- [x] 6月16日还书（17日过期）

- [x] [iview upload 动态改变上传参数](https://www.jianshu.com/p/a15c22909dd9)

- [x] 河南省轻工业学校（对口大专：河南轻工职业学院）：500元预报名即可录取，有郑州轻工业大学保送名额

- [x] 联系郑州信息技术/郑州十中（对口大专：郑州市旅游职业学院）咨询电话：0371-5666 3156、61130911工作时间：早9：00-晚5：00

- [x] 字体颜色渐变

  ```css
  .gradient-text{
      background:-webkit-linear-gradient(left,#eb1f79 0%,#2a2361 100%);
      -webkit-background-clip:text;
      -webkit-text-fill-color:transparent
  }
  ```

## Week17

- [x] 软件测试：~~实验JMeter（17周周二之前上交）~~、复习指南（2019-06-27(10:10-12:10)）
- [x] 形式与政策：朝核问题及东南亚国际局势分析。600-800字，这周五之前word发杜文婷邮箱。
- [x] 安卓：21号周五答辩

## Week18

- [x] 设计模式：周三上午答辩：单例模式、建造者模式、适配器模式、策略模式
- [x] 软件测试：周四考试：2019-06-27(10:10-12:10)九章楼N4-102

    - anki的SQA牌组19个知识点
    - 插桩大题、案例分析
    - 一、判定题（5 小题，每小题 2 分，共 10 分）
    - 二、选择题（5 小题，每小题 2 分，共 10 分）
    - 三、填空题（5 小题共 10 个空格，每个空格 1 分，共 10 分） 
    - 四、名词解释（5 小题，每小题 2 分，共 10 分） 
    - 五、简答题（6 小题，每小题 5 分，共 30 分）
    - 六、案例分析（3 小题，每小题 10 分，共 30 分）
- [ ] 下学期重修操作系统？
- [x] 实验室安全考试

# 大三暑假（7月1日）

## Week1

- [x] 7月5日去上海
  - 续贷证明和导出续贷申请表
  - 行李箱
  - 不参加推免面试的只需要带身份证和学生证。

# 20190731

## 143-0731

- 感冒

## 142-0801

- [x] 新建dev分支
- [x] 第二次提交到dev分支

## 141-0802

- [ ] [理财系统springboot](https://www.bilibili.com/video/av40320810?from=search&seid=6308388692867925026)

- [x] 取快递（徐涛政治）

## 139-0804

- [x] 区间再现专项练习

## 117-0825

- [ ] git add

