# 毕业设计-汽车维修管理系统

#### 介绍
本系统基于springboot + mybatis +jps架构开发，前后端分离，开发环境为jdk1.8、mysql、maven。系统功能主要分为汽车维修管理、配件管理、财务管理、基础数据管理、系统维护5大模块。


#### 软件架构
系统架构：springboot + mybatis +jps  
开发环境：jdk1.8、mysql、maven  

#### 功能结构
![输入图片说明](images/image1.png)

#### 功能介绍
##### 【代码结构与数据库截图】
![输入图片说明](image2.png) 
![输入图片说明](images/image3.png)  

##### 【功能详述】 
   首先通过登录页录入账号密码进行登录
![输入图片说明](images/image4.png)
   登录后首页为财务管理的报表页面，显示维修店经营情况。页面左侧可看到系统的各个模块的菜单入口。


△汽车维修管理
   本模块用于汽车维修整条业务的信息记录： 车辆接待、维修项目登记、维修领料、质检完工、消费结算。
   在车辆接待中登记车辆信息并选派维修人员与质检人员，登记维修项目后，根据项目领料，维修人员完成维修，质检人员完成质检，最后进行费用结算。
![输入图片说明](images/image5.png)


△配件管理
   用于管理汽车维修配件，分为采购配件与库存管理，可以在采购配件中查询采购记录，在库存管理中管理配件库存。
![输入图片说明](images/image6.png)


△财务管理
   展示业务经营情况，可以进行单据查询、采购单据管理及报表统计的查看。
![输入图片说明](images/image7.png)


△基础数据管理
   基础数据管理中可以对系统的各个模块信息设置进行维护，包括【客户资料管理】、【系统基础数据配置】、【维修项目管理】、【供应商管理】、【配件类别管理】、【仓库信息管理】、【业务类型管理】、【配件管理】。本模块可以让用户灵活自定义需要使用的表单。
![输入图片说明](images/image8.png)


△系统维护
   系统维护中【系统用户管理】可以用于管理本系统中登录的用户账号与访问的页面权限；【修改密码】即修改本账号密码；【数据还原备份】可用于备份或恢复备份信息；【系统帮助】可以查看系统使用说明，帮助用户快速上手。
![输入图片说明](images/image9.png)


#### 项目预览
地址：[商品详情 ](https://www.xunmaw.com/shop/detail/1622419623224623105)   
点击商品详情中的演示地址，看查看系统录制的视频    

#### 使用说明
1. 创建数据库，执行数据库脚本
2. 修改jdbc数据库连接参数
3. 下载安装maven依赖jar
4. 在tomcat服务器部署项目  
    请求地址： http://localhost:8080/hotel-manage    
    用户名：admin  
    密码：admin  

#### 联系作者
这是作者的微信二维码，如需本项目源代码，可扫码联系联系作者  
![作者微信](https://gitee.com/xiaoxinlai/book-system/raw/master/xunmaw001.jpg)

这是作者的公众号二维码，时不时会推一些新开发的项目源码与高效软件工具，感兴趣的朋友给个关注  
![作者公众号](https://gitee.com/xiaoxinlai/book-system/raw/master/xunmaw%E5%85%AC%E4%BC%97%E5%8F%B7.jpg)