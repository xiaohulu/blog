# Spring boot

## 配置数据库连接

1. mysql

   ```ini
    # jdbc 驱动
    spring.datasource.driver-class-name = com.mysql.jdbc.Driver
    # 数据库连接，db 为数据库名
    spring.datasource.url = jdbc:mysql://127.0.0.1:3306/db
    # 用户名
    spring.datasource.username = root
    # 密码
    spring.datasource.password = your_password
   ```