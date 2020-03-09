# tigergraph后台操作教程

1. 打开浏览器，访问http://39.99.135.94:8080/login?next=%2Ftree%3F，出现如下界面，密码是tigergraph

![image-20200227113918593](/Users/dengjun/Library/Application Support/typora-user-images/image-20200227113918593.png)

2. 新建终端

![image-20200227114047184](/Users/dengjun/Library/Application Support/typora-user-images/image-20200227114047184.png)

3. 进入服务器，输入gsql，密码为123456，进入gsql

   ![image-20200227114157358](/Users/dengjun/Library/Application Support/typora-user-images/image-20200227114157358.png)

4. 输入create user，按提示设置用户名和密码

5. 输入GRANT ROLE designer ON GRAPH <gname> TO <user1>，可将图gname授权给用户user1

