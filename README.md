# uni-app-ticket

#### 介绍
1. 由于本人老家到北京交通不是很方便, 所以有私人旅行社巴士和个人车辆进行城际拼车, 买票必须到车跟前及不能知道出发时间等各种不便利因素,所以产生做这个项目的想法
2. 用uni-app + color-ui 仿照飞猪做了一个小项目,此项目可以打包出7个平台(微信小程序, h5, ios, android, 支付宝小程序, 百度小程序, 字节跳动小程序)
但是只有前三个平台是本人亲自测试过没什么问题的

<p style="text-align: center;">
  <img src="https://github.com/qianchaozhao/uni-app-ticket/blob/master/ReadmeImg/WechatIMG132.png" alt="" style="max-width:100%;" width="300">
  <img src="https://github.com/qianchaozhao/uni-app-ticket/blob/master/ReadmeImg/WechatIMG133.png" alt="" style="max-width:100%;" width="300">
  <img src="https://github.com/qianchaozhao/uni-app-ticket/blob/master/ReadmeImg/WechatIMG134.png" alt="" style="max-width:100%;" width="300">
  <img src="https://github.com/qianchaozhao/uni-app-ticket/blob/master/ReadmeImg/WechatIMG135.png" alt="" style="max-width:100%;" width="300">
  <img src="https://github.com/qianchaozhao/uni-app-ticket/blob/master/ReadmeImg/WechatIMG136.png" alt="" style="max-width:100%;" width="300">
  <img src="https://github.com/qianchaozhao/uni-app-ticket/blob/master/ReadmeImg/WechatIMG137.png" alt="" style="max-width:100%;" width="300">
  <img src="https://github.com/qianchaozhao/uni-app-ticket/blob/master/ReadmeImg/WechatIMG138.png" alt="" style="max-width:100%;" width="300">
  <img src="https://github.com/qianchaozhao/uni-app-ticket/blob/master/ReadmeImg/WechatIMG139.png" alt="" style="max-width:100%;" width="300">
  <img src="https://github.com/qianchaozhao/uni-app-ticket/blob/master/ReadmeImg/WechatIMG140.png" alt="" style="max-width:100%;" width="300">
</p>

#### 项目布局

``` lua
colorui -- ui框架
Colorui -- UniApp -- UI框架官方案例(与项目无关,可供参考)
common -- 所需要的公用方法
myui -- 自定义样式
static -- 图片等静态文件
ReadmeImg -- readme所需静态文件
unpackage -- 打包各平台后的代码
pages.json -- 路由配置
pages -- 源码目录
├── common -- 公用组件
├── index -- 首页
├── home -- 首页默认的第一页面
├── order -- 订单页面
├── my -- '我的'页面
└── richText -- 富文本公用页面
```

#### 软件架构
1. 前端: uni-app + color-ui
2. 后端准备用:spring-cloud + springboot等(还没开始写)

#### 安装教程
本项目依着h5端和小程序先来

1. [需要安装HbuilderX开发工具 下载地址及介绍]( https://uniapp.dcloud.io/quickstart?id=%E9%80%9A%E8%BF%87-hbuilderx-%E5%8F%AF%E8%A7%86%E5%8C%96%E7%95%8C%E9%9D%A2)

2. 测试小程序安卓微信开发者工具, ios或其他平台测试都下载对应的开发工具(各平台的开发工具安装及环境搭建google或baidu吧)
3. 将项目导入HbuilderX
4. h5运行 : 点击HbuilderX工具上侧导航栏的 运行-> 运行到浏览器 -> Chrome等选择一个浏览器
5. wechat小程序运行: 点击HbuilderX工具上侧导航栏的 运行-> 运行小程序模拟器 -> 微信开发者工具

#### 使用说明

1. [uni-app 官网参考]( https://uniapp.dcloud.io)

#### 交流

<p style="text-align: center;">
  <img src="https://github.com/qianchaozhao/uni-app-ticket/blob/master/ReadmeImg/myWeChat.jpeg" alt="" style="max-width:100%;" width="300">
</p>
1. 此项目写的不好, 不喜勿喷, 仅限学习交流, 商业用途出现事故与此项目无关

