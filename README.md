## 基本信息

孙阳，男，1992年生             

求职意向: iOS研发工程师 

工作经验: 3年

电话: 18516994586 邮箱:  sunyang1614@qq.com



## 工作经历

北京桃谷科技移动客户端工程师(2016年08月至今)

北京卫程车联移动客户端实习生(2015年06月 至 2016年06月)



## 代表项目

#### 公司项目

##### 健康e+(2016年至今)

* 项目简介:掌上医院，用户可以在这里进行预约挂号，咨询医生，购买问诊服务等操作。
* 亮点技术:
* * 使用了`多Framework组件化`管理项目。因为不同医院所需要的功能不同，或者相同功能得到细节逻辑不同，所以通过组件化划分不同的功能以及相同功能之间的差异化，只需要一份代码与不同的配置文件，就可以生成一个特定医院的APP，并且凭借这项技术成功上线了**近300个**不同的APP。
  * 资源管理。通过自定义的注释代码与外部脚本，统一管理项目中使用的`颜色，字体，图片`资源，方便在大版本更新或设计方案变更时对资源进行统一修改。
  * HTTPS双向加密验证，使用`KVC`, `runtime`将字典自动转化为模型，基于XMPP协议的IM即时通讯模块等。

##### 医护助理(2016年至今)

- 项目简介: 掌上医院的医生端，医生可以在这里进行回复患者的问题，开处方，查看管理问诊进度，管理患者等操作。

- 亮点技术: 

  * 后台配置前端页面。通过与后台定义协议，并且将前端功能高度的对象化，来实现后台下发功能配置，并且减少冗余代码。


  * 使用WKWebView与H5页面进行交互。配合组件化，通过与H5定义协议，实现扩展性极好的交互形式，跳转指定页面，调起特定功能，且耦合性低。

##### 卫程客户端(2015.07 ~ 2015.10)

* 项目简介: 通过卫程客户端可以查看连接卫程行车记录仪，查看当前记录仪状态，浏览下载记录仪中保存的视频。
* 亮点技术: 
  * 基于Socket的网络通信。参看`AFNetworking`的代码风格，基于`CocoaAsyncSocket`封装了一套Socket请求层，用来跟记录仪进行交互，可以时间简单的read, write操作和持续下载操作。
  * ffmpge解码播放直播流视频。通过ffmpge与VLC，实现实时编解码播放记录仪的直播视频信息。



#### 个人项目

##### 自动化Maker

* 项目简介: Maker是一个包括iOS端、Web端和打包机后台的自动化打包上传工程。
* 亮点技术: 
  * iOS端主要用于生成不同医院的配置文件，编辑医院APP的基本页面，并且可以通过目前的配置文件，模拟运行该医院APP，查看效果。
  * Web端主要分为医院基本信息配置，可视化的打包操作平台两部分。
  * 打包机，通过`xcodebuild`, `xcrun`, `altool`等指令实现自动打包和自动上传ipa包到AppStore，并且为已经打好的包提供二维码下载等服务，方便QA下载测试。

##### Mocker(Python)

* 项目简介: Mocker是基于Python Django框架的一个轻量级的mock数据平台，可以自己编辑接口与返回信息，方便研发。现已开源(https://github.com/Hoikiiz/Mocker)
* 亮点技术: 
  * 二次集成了`Django_REST` 和 `Django_REST_Swagger`提供了内部对象的基本访问API和一个可视化API测试后台，便于二次开发。



## 教育经历

山东建筑大学(信息管理与信息系统) 2012年9月 ~ 2016年6月



## 其他

熟悉Objective-C，对其特性，runtime, runloop等内容有自己的理解 Upwork Objective-C Test 得分4.25，Top20%。

熟悉UIKit，对常用控件及其特性非常清楚，同时对CoreAnimation也有深入的理解。

偏爱Python和Swift这类语言，有代码洁癖，会尽力写出Pythonic的代码，对Swift也一样，认为用OC的思路写Swift毫无意义。

喜欢关注新动向，学习新内容，经常浏览WWDC，Github，Realm Academic，iOS Weekly等网站。

遇到重复性高的工作会尽力想办法用脚本代理，提高效率，比如我之前写的自动生成懒加载代码的Xcode插件，将JSON代码转换为OC模型代码等。

学习能力强，对新事物感兴趣，对大数据，机器学习，区块链，量子信息等都有简单的理论性的理解。

Github主页：https://github.com/Hoikiiz/

简书： https://www.jianshu.com/u/4689590680bf