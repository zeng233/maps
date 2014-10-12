#### 获取Class对象的三种方式 ####

`1）obj.getClass() `用于有引用

`2）Object.class` 用于只知道类名

`3）Class.forName("")`如果2种有同样的类名，就用3来补充，使用具体的包路径，`com.mysql.Driver`