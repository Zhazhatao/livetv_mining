### 关于项目
***

#### 介绍

项目实现**爬虫**、**数据挖掘/分析**等功能。目前主要是扫描直播站点收集数据，后续会开发相关数据分析模块。

架构采用前后端分离，通过RESTFul API通信。前端Vue+Webpack，后端Flask。

文件结构分为三部分，每个部分可以单独提供服务：

* frontend 前端代码，使用Vue+Webpack开发管理。
* server   后端RESTFul服务，使用Flask搭建提供API。
* crawler  爬虫服务，使用框架scrapy对直播站点爬取数据。

使用中有问题或更新建议，欢迎提issue或用以下联系方式跟我交流：

* 邮件: zwtzjd@gmail.com
* QQ: 3084582097

#### 历程

* 2017-01-07 完成全部功能迁移，前后端分离完成。
* 2016-12-24 引入vuex进行state和权限管理。
* 2016-12-15 引入vue-resource，主模块(Main)完成分离。
* 2016-11-25 研究流行前端框架和开发方式，确定使用webpack开发。
* 2016-11-20 重新设计结构，进行前后端分离。
* 2016-11-01 修正改造搜索功能，需要登录后才能使用。
* 2016-10-29 完成渲染初步改造，已实现调用REST API进行访问读取。爬虫运行间隔20分钟。
* 2016-10-20 引入Vue.js，改造前端渲染方式，减轻服务器压力。开发完成简单 [Flask-Vue](https://github.com/taogeT/flask-vue) 插件。
* 2016-10-15 引入Scrapy重构爬虫，精简爬虫步骤。仅保留斗鱼、BiliBli爬虫。

##### 2016-08-15 v1.0版本开发结束，代码保存在分支v1.0

### 捐助开发者
***

如果你喜欢我的作品 or 站点对你有所帮助，希望能支持我一下。

| 微信 | 支付宝 |
| ---- | :------|
| <img width="80%" src="http://ww4.sinaimg.cn/large/77ef2ab1gw1f2ne2zgy4zj20bt0bqq4s.jpg"> | ![alipay](http://ww3.sinaimg.cn/mw690/77ef2ab1gw1f2ne2zc10cj209a09bdgz.jpg) |
