> #### 作者主页：[舒克日记](https://blog.csdn.net/cativen)
>
>  简介：Java领域优质创作者、Java项目、学习资料、技术互助
>
> <b><font color=red>文中获取源码</font></b>

# 项目介绍

本系统的使用角色可以被分为用户和管理员，用户具有注册、查看信息、留言信息等功能，管理员具有修改用户信息，发布新闻等功能



# 环境要求



1.运行环境：最好是java jdk1.8,我们在这个平台上运行的。其他版本理论上也可以。 

2.IDE环境：IDEA,Eclipse,Myeclipse都可以。推荐IDEA; 

3.tomcat环境：Tomcat7.x,8.X,9.x版本均可 

4.硬件环境：windows7/8/10 4G内存以上；或者Mac OS; 

5.是否Maven项目：是；查看源码目录中是否包含pom.xml;若包含，则为maven项目，否则为非maven.项目 

6.数据库：MySql5.7/8.0等版本均可；





# 技术栈



运行环境：jdk8 + tomcat9 + mysql5.7 + windows10

服务端技术：SpringBoot + MyBatis + Vue + Bootstrap + jQuery





# 使用说明





1.使用Navicat或者其它工具，在mysql中创建对应sq文件名称的数据库，并导入项目的sql文件； 

2.使用IDEA/Eclipse/MyEclipse导入项目，修改配置，运行项目； 

3.将项目中config-propertiesi配置文件中的数据库配置改为自己的配置，然后运行；





# 运行指导

idea导入源码空间站顶目教程说明(Vindows版)-ssm篇：

http://mtw.so/5MHvZq 

源码地址：[http://www.codegym.top](http://www.codegym.top/)





# 运行截图









![springboot207基于springboot的实习管理系统10](https://img-blog.csdnimg.cn/img_convert/a682d0716f8ee87b4b30a17bce3ab591.png)

![springboot207基于springboot的实习管理系统11](https://img-blog.csdnimg.cn/img_convert/42e3dac831640ea87e42a8b41eca5a92.png)

![springboot207基于springboot的实习管理系统12](https://img-blog.csdnimg.cn/img_convert/9d598e2baf197a059e92b3f46603b8fc.png)

![springboot207基于springboot的实习管理系统13](https://img-blog.csdnimg.cn/img_convert/4aff0d3dc6b5459d3cb6860098796159.png)

### 代码

```java
	@Override
	public List<String> getOption(Map<String, Object> params) {
		return commonDao.getOption(params);
	}
	
	@Override
	public Map<String, Object> getFollowByOption(Map<String, Object> params) {
		return commonDao.getFollowByOption(params);
	}
```









