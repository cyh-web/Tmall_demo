[comment]: <> (# 迷你天猫商城)

[comment]: <> (+ **问题交流QQ群：763819871**)

[comment]: <> (+ **前台演示地址（服务器1核2G内存，请温和测试 ^ ^）：<https://xianqu.fun/tmall/>**)

[comment]: <> (+ 9/9：备案已完成，目前可以正常访问)

[comment]: <> (### 介绍)

[comment]: <> (迷你天猫商城是一个基于Spring Boot的综合性B2C电商平台，需求设计主要参考天猫商城的购物流程：用户从注册开始，到完成登录，浏览商品，加入购物车，进行下单，确认收货，评价等一系列操作。)

[comment]: <> (作为迷你天猫商城的核心组成部分之一，天猫数据管理后台包含商品管理，订单管理，类别管理，用户管理和交易额统计等模块，实现了对整个商城的一站式管理和维护。)

[comment]: <> (所有页面均兼容IE10及以上现代浏览器。)

[comment]: <> (### 部署方式)

[comment]: <> (1. 项目使用IntelliJ IDEA开发，请使用IntelliJ IDEA的版本控制检出功能，输入“<https://gitee.com/project_team/Tmall_demo.git>”拉取项目即可。)

[comment]: <> (2. 项目数据库为MySQL 5.7版本，在**sqls文件夹**中找到SQL文件并导入到数据库中。)

[comment]: <> (3. 使用IDEA打开项目后，在maven面板刷新项目，下载依赖包。)

[comment]: <> (4. 配置数据库连接并启动SpringBootApplication即可。)

[comment]: <> (### 项目默认运行地址)

[comment]: <> (+ 前台地址：<http://localhost:8080/tmall>)

[comment]: <> (+ 后台地址：<http://localhost:8080/tmall/admin>)

[comment]: <> (### 注意事项：)

[comment]: <> (1. 后台管理界面的订单图表没有数据为正常现象，该图表显示的为近7天的交易额。)

[comment]: <> (2. 该项目同时兼容eclipse，但如有自行扩展代码的意愿，建议使用IDEA。)

[comment]: <> (3. 该项目是我们几个学生在校合作完成的一个练习项目，目的是让编程初学者和应届毕业生可以参考一下用较少的代码实现一个完整MVC模式，Spring Boot体系的电商项目，相关领域大神们可以给我们建议，让我们做得更好。)

[comment]: <> (### 项目界面)

[comment]: <> (+ ##### 后台界面&#40;部分&#41;---)

[comment]: <> (![主页]&#40;https://images.gitee.com/uploads/images/2019/0720/132736_629d409d_1616166.png "主页.png"&#41;)

[comment]: <> (![所有产品]&#40;https://images.gitee.com/uploads/images/2019/0720/132752_a9065bdc_1616166.png "所有产品.png"&#41;)

[comment]: <> (![产品详情]&#40;https://images.gitee.com/uploads/images/2019/0720/132804_07364d8e_1616166.png "产品详情.png"&#41;)

[comment]: <> (![产品分类]&#40;https://images.gitee.com/uploads/images/2019/0720/132815_4fa23e1c_1616166.png "产品分类.png"&#41;)

[comment]: <> (![分类详情]&#40;https://images.gitee.com/uploads/images/2019/0720/132824_0392314c_1616166.png "分类详情.png"&#41;)

[comment]: <> (![用户管理]&#40;https://images.gitee.com/uploads/images/2019/0720/132840_582530ca_1616166.png "用户管理.png"&#41;)

[comment]: <> (![用户详情]&#40;https://images.gitee.com/uploads/images/2019/0720/132849_481238d6_1616166.png "用户详情.png"&#41;)

[comment]: <> (![订单列表]&#40;https://images.gitee.com/uploads/images/2019/0720/132912_190142c1_1616166.png "订单详情.png"&#41;)

[comment]: <> (![订单详情]&#40;https://images.gitee.com/uploads/images/2019/0720/132926_0393d549_1616166.png "订单详情2.png"&#41;)

[comment]: <> (![我的账户]&#40;https://images.gitee.com/uploads/images/2019/0720/132934_e0132cc9_1616166.png "我的账户.png"&#41;)

[comment]: <> (+ ##### 前台界面&#40;部分&#41;---)

[comment]: <> (![登陆界面]&#40;https://gitee.com/uploads/images/2018/0526/223030_17b28619_1616166.png "2018-05-26_221715.png"&#41;)

[comment]: <> (![首页]&#40;https://gitee.com/uploads/images/2018/0526/223018_14e999f1_1616166.png "2018-05-26_221703.png"&#41;)

[comment]: <> (![产品详情]&#40;https://gitee.com/uploads/images/2018/0526/223044_e481ec5f_1616166.png "2018-05-26_221725.png"&#41;)

[comment]: <> (![下单界面]&#40;https://gitee.com/uploads/images/2018/0526/223100_ef6e9612_1616166.png "2018-05-26_221837.png"&#41;)

[comment]: <> (![订单列表]&#40;https://gitee.com/uploads/images/2018/0526/223117_dfd64b43_1616166.png "2018-05-26_221901.png"&#41;)

[comment]: <> (![确认收货]&#40;https://gitee.com/uploads/images/2018/0526/223220_71e2ee3d_1616166.png "2018-05-26_221911.png"&#41;)

[comment]: <> (![产品列表]&#40;https://gitee.com/uploads/images/2018/0526/223233_18e131a5_1616166.png "2018-05-26_222006.png"&#41;)

[comment]: <> (![购物车]&#40;https://gitee.com/uploads/images/2018/0526/223245_3f80d8f4_1616166.png "2018-05-26_223157.png"&#41;)

[comment]: <> (### 作者的话)

[comment]: <> (首先感谢您看到这里)

[comment]: <> (本项目是我和其他两个朋友空闲时间在校合作完成的一个商城demo)

[comment]: <> (前后台业务代码，都是自主完成，后台都是专门设计的样式，前台是参考天猫自行开发界面)

[comment]: <> (技术日新月异，目前我们在使用更流行的前后台技术栈，从而开源更多优质项目)

[comment]: <> (但我们仍记得，我们对这个项目付出的热情和精力)

[comment]: <> (在校开发不易，如对您有帮助，您可以给予我们一点支持!)

[comment]: <> (+ ##### 支付宝)

[comment]: <> (<img src="https://images.gitee.com/uploads/images/2021/0908/120223_b882a30f_1616166.png" alt="支付宝打赏二维码" width="128px" height="128px"/>)

[comment]: <> (+ ##### 微信)

[comment]: <> (<img src="https://images.gitee.com/uploads/images/2021/0908/120333_894f5c7e_1616166.png" alt="微信打赏二维码" width="128px" height="128px"/>)