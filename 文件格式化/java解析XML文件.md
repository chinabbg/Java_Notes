# XML

### 一、什么是XML

​	是一种与平台、语言、系统无关的通用的一种数据交换格式，给数据集成与交互带来了极大的方便。XML在不同的语言环境中解析方式是一样的，只是实现的语法不同。

### 二、XML的作用

​	在java项目中，XML文件一般用来存储配置信息

​	如jdbc编程中，可以把数据库的连接字符串写入到xml文件中，若修改数据库连接，只需修改xml文件即可；

​	框架中的xml，除了配置信息，还可以写一些对应关系，其实也是一种配置信息。拿Struts来说，xml的配置是页面								URL	对应后台java类(action)的关系，在配置和修改时，只需修改一个xml文件即可，不需要一个个的查找java代码；

​	java项目完成后，模块之间是独立的，模块之间的关系可以用xml文件来维护，spring就是

​	一个好的项目，应具有好的可拓展性，若把配置信息和逻辑关系都写入到java代码中，可拓展性会很差，所以使用xml可以对整个项目进行调度。

​	xml也可用于存储数据

### 三、java解析xml

1、DOM(Document Object Model)解析

2、SAX(Simple APIs for XML)解析

3、JDOM解析

4、DOM4J解析



