# MyBatis简介

* MyBatis是支持定制化SQL、存储过程以及高级映射的优秀的持久层框架
* MyBatis 避免了几乎所有的JDBC代码和手动设置参数以及获取结果集
* MyBatis 可以使用简单的XML或注解用于配置和原始映射，将接口和Java的POJO(Plain Old Java Objects,  普通的Java对象)映射成数据库中的记录

# MyBatis 历史

* 原是Apache的一个开源项目iBatis，2010年6月这个项目由Apache Software Foundation 迁移到了 Google Code ，随着开发团队转投Google Code旗下，iBatis3.x正式更名为MyBatis，代码于2013 年 11月迁移到Github
* iBatis 一次来源于“Internet”和“abatis”的组合，是一个基于Java的持久层框架。iBatis提供的持久层框架包括SQL Maps和Data Access Objects   (DAO)

# 为什么使用MyBatis？

* MyBatis是一个<font color=#00bf00 size=3><b>半自动化的持久化层框架</b></font>
* JDBC
  * SQL夹在Java代码块里，耦合度高导致编码内伤
  * 维护不易且实际开发需求中sql是有变化，频繁修改的情况多见

* Hibernate和JPA
  * 长难复杂SQL，对于Hibernate 而言处理也不容易
  * 内容自动生产的SQL，不容易做特殊优化
  * 基于全映射的全自动框架，大量字段的POJO进行部分映射时比较困难，导致数据库性能下降

* 对于开发人员而言，核心sql还是需要自己优化
* <font color=#FF3030 size=3><b>sql和java编码分开，功能边界清晰，一个专注业务、一个专注数据</b></font>

# 去哪找到MyBatis？

[MyBatis]: https://github.com/mybatis/mybatis-3/

