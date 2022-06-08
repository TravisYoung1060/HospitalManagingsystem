# HospitalManagingSystem
基于SpringBoot的医院信息管理系统
医院管理系统,分为管理员、医生、病人三种角色；
管理员主要功能包括：
首页、系统管理：医生管理、患者管理、药品管理；预约管理；病史管理；住院信息管理；管理员用户管理；
医生主要功能包括：首页、就医/查看病史；
病人主要功能包括：首页、病史、住院信息、挂号；


#### 环境需要
1.运行环境：最好是java jdk 1.8，我们在这个平台上运行的。其他版本理论上也可以。
2.IDE环境：IDEA，Eclipse,Myeclipse都可以。推荐IDEA;
3.tomcat环境：Tomcat 7.x,8.x,9.x版本均可
4.硬件环境：windows 7/8/10 1G内存以上；或者 Mac OS；
5.是否Maven项目: 是；查看源码目录中是否包含pom.xml；若包含，则为maven项目，否则为非maven项目 
6.数据库：MySql 5.7版本；

#### 技术栈
1. 后端：SpringBoot
2. 前端：Layui+Freemaker

  
#### 使用说明
1. 使用Navicat或者其它工具，在mysql中创建对应名称的数据库，并导入项目的sql文件；
2. 使用IDEA/Eclipse/MyEclipse导入项目，Eclipse/MyEclipse导入时，若为maven项目请选择maven;若为maven项目，导入成功后请执行maven clean;maven install命令
3. 将项目中application.yml配置文件中的数据库配置改为自己的配置,配置tomcat，然后运行；
4. 运行项目，输入http://localhost:8088 登录
5. 管理员账户：admin1  密码：123456
医生账户：zhangsan 密码：123456
病人账户：zhaoone 密码：123456
