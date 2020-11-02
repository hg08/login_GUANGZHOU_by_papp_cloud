# A Guide for login of GUANGZHOU by papp_cloud (Chinese)

papp_cloud, 中文译为云桌面应用.　papp_cloud上有一个用户名, 是你注册时候所用的邮箱名。例如，用户名可以是： huanggg08@163.com　。这个用户名有一个密码(比如Dyla----), 这个密码也是用ssh来登录远程服务器的密码.


如果忘记了密码，你可以去如网页版的云桌面的地址找回密码: https://cloud.paratera.com



在利用ssh登陆远程服务器之前，需要你先登录papp_cloud。比如，

```shell
papp_cloud login -u huanggg08@163.com -p
password: Dyla----
```
然后，用命令如下命令就可以登录：

```shell
papp_cloud ssh blsc78@gz
```
如果你在.bashrc中设置别名:

```shell
alias gz='papp_cloud ssh blsc78@gz'
```
那么，就只需用如下更简单的命令登录了。
```shell
gz
```