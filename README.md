## Java语言程序设计实验

* Java语言程序设计实验共8部分
* 实验源码在src目录下与实验相对应的文件夹下
* 每个实验的题目和正确性检验均在以"Exp"开头的Java文件中
* 每个实验需要用到的类均在对应的content文件夹下。
* 每个实验都有文档注释作为概述，可根据概述查看自己感兴趣的源码。
* 实验并不能直接导入IDEA（因为缺少.idea文件夹）仅包含源码及相关文件
* "实验四 图形用户界面程序设计"属于淘汰技术，并未包含在实验中
* 实验八需要导入 com.mysql.jdbc.Driver.jar 驱动
* 实验环境为Java SE 12.0.2 mysql 版本为8.0.18
* 实验八创建数据库操作如下：

```sql
CREATE DATABASE Studentinfo; 

USE Studentinfo;
CREATE TABLE student
(
    Name CHAR(10),
    Sex  CHAR(2),
    Age  INTEGER
);
```

![](thumb/database.png)  
