1.mysql 安装配置

解压后修改my.ini
#设置3306端口
port = 3306 
# 设置mysql的安装目录
basedir=E:\mysql-5.7.16-winx64
# 设置mysql数据库的数据的存放目录
datadir=E:\mysql-5.7.16-winx64\data

安装mysql到本地服务
mysqld --initialize --user=root --console
mysqld --install

启动mysql服务
net start mysql

2.redis 安装配置

解压后运行redis-server.exe

3.修改项目配置application.properties

spring.datasource.url=jdbc:mysql://localhost:3306/travel_note?characterEncoding=utf-8&autoReconnect=true&failOverReadOnly=false&useSSL=false
spring.datasource.username=root
spring.datasource.password=123456
spring.datasource.driver-class-name=com.mysql.jdbc.Driver
#redis
spring.redis.host=localhost
spring.redis.database=0
spring.redis.password=


