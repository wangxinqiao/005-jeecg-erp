# 005javaweb进销存管理系统jeecg

#### 介绍
库存管理系统。主要功能包括：
货品出入库：货品入库、货品出库、库存查询；
基础资料：货品信息、供货商信息、分公司信息；
系统管理：用户管理、角色管理、数据字典、菜单管理、国标管理、部门管理；
系统监控：系统日志；

源码获取：[ **点此获取** ](http://www.shuyue.fun/?type=productinfo&id=116)

#### 环境需要
1.运行环境：最好是java jdk 1.8，我们在这个平台上运行的。其他版本理论上也可以。
2.IDE环境：IDEA，Eclipse,Myeclipse都可以。推荐IDEA;
3.tomcat环境：Tomcat 7.x,8.x,9.x版本均可
4.硬件环境：windows 7/8/10 1G内存以上；或者 Mac OS；
5.是否Maven项目: 是；查看源码目录中是否包含pom.xml；若包含，则为maven项目，否则为非maven项目
6.数据库：MySql 5.7版本；

#### 技术栈
1. 后端：jeecg

#### 使用说明
1. 使用Navicat或者其它工具，在mysql中创建对应名称的数据库，并导入项目的sql文件；
2. 将项目中dbconfig.properties配置文件中的数据库配置改为自己的配置
3. 使用IDEA/Eclipse/MyEclipse导入项目，Eclipse/MyEclipse导入时，若为maven项目请选择maven;若为maven项目，导入成功后请执行maven clean;maven install命令，配置tomcat，然后运行；
4. 运行项目，输入localhost:8080/xxx 登录
5. 账户admin  密码123456


#### 注意事项
1.maven配置文件settings.xml中，进行如下配置：

nexus-aliyun
*,!jeecg,!jeecg-snapshots
Nexus aliyun
http://maven.aliyun.com/nexus/content/groups/public

2.若还是下载不成功，则可能为jar包版本不匹配，首先在.m2中查看存在的jar包版本，然后在pom.xml中修改jar包版本即可；

## 运行截图
![输入图片说明](https://images.gitee.com/uploads/images/2021/0319/184100_4f00cfa7_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0319/184110_15ea3b01_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0319/184117_4859945b_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0319/184125_aa254fe9_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0319/184136_1c8ecf24_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0319/184147_5c000d6b_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0319/184203_64dbfe3d_863230.png "屏幕截图.png")
