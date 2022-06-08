**需要完整代码可以加qq  931708230 或者加微信 ynwwxid**

**需要完整代码可以加qq  931708230 或者加微信  ynwwxid**
#程序员 #java #毕业设计 #网上商城 #springboot #课程设计 #编程 #thymeleaf #Spring-data-jpa #源代码
# SpringBoot网上商城
> 使用SpringBoot 集成Spring-data-jpa,Druid连接池,mysql,thymeleaf模板实现的一个简单网上商城项目，包含后台管理

前台功能
商品分类查询，加入购物车，提交订单，查看订单

后台功能：
用户管理，订单管理，分类管理，商品管理

项目地址：
前台访问：http://127.0.0.1:8081/mall

用户名： hfb   密码：123456

后台访问：http://localhost:8081/mall/admin/toLogin.html

用户名： admin   密码：admin

项目效果截图

![contents](./picture/picture1.png)

![contents](./picture/picture2.png)

![contents](./picture/picture3.png)

![contents](./picture/picture4.png)

![contents](./picture/picture5.png)

![contents](./picture/picture6.png)

![contents](./picture/picture7.png)

![contents](./picture/picture8.png)




### 基础环境 :IDEA，maven3.6+，JDK 1.8 ， Mysql 5.8

### 源码+数据库脚本 

所有项目以及源代码本人均调试运行无问题 可支持远程调试运行

**需要完整代码可以加qq  931708230 或者加微信  ynwwxid**

**需要完整代码可以加qq  931708230 或者加微信  ynwwxid**


## Docker镜像
### Pull image
```bash
docker pull skywa1ker/mall:latest
```
### Run
```bash
docker run -p 8081:8081 --name mall -v /data/mall/config:/data/mall/config -v /data/mall/log:/data/mall/log --restart=always -d skywa1ker/mall:latest
```