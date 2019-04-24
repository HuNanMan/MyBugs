[详细内容可以参考博客](https://blog.csdn.net/u012062455/article/details/52442838)



### 问题描述：

在第二种方式中：

jdbc:oracle:thin:@//host:port/service_name 

如何获得service_name?



### 解决办法：

登录oracle后，输入：
```sql
select * from global_name;
```

