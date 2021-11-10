# mysql
docker-compose启动本地mysql服务

步骤：
<!-- 启动sql服务 -->
1、make up
<!-- 网页版工具，操作数据库 -->
2、访问 localhost:8080，用户名：root，密码：example
<!-- 用go连接、操作数据 -->
3、go run main.go


database test

Column	Type	Comment
uid	int Auto Increment	
username	text	
department	text	
created	date


redis 命令

```
redis-cli

EXISTS test

GET test
```