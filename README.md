# login_GUANGZHOU_by_papp_cloud

papp_cloud: 翻译为云桌面应用.　papp_cloud上有一个用户名, 是你注册时候所用的邮箱名。例如，用户名可以是： huanggg08@163.com　。这个用户名有一个密码(比如Dyla----), 这个密码也是用ssh来登录远程服务器的密码.


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
我已经在.bashrc中设置了别名:

```shell
alias gz='papp_cloud ssh blsc78@gz'
```
所以，我只需用命令
```shell
gz
```
登录就可以了。
