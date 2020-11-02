# login_GUANGZHOU_by_papp_cloud

papp_cloud: 云桌面应用.
papp_cloud上有一个用户名, 为你注册时候所用的邮箱名。例如: huanggg08@163.com
这个用户名有一个密码(比如Dyla----), 这个密码也是用ssh来登录远程服务器的密码.

网页版的云桌面的地址: https://cloud.paratera.com
如果忘记了密码，在这个网址里可以去找回。

在利用ssh登陆远程服务器之前，需要你先登录papp_cloud。比如，

```shell
papp_cloud login -u huanggg08@163.com -p
password: Dyla----
```
然后，用命令

```
papp_cloud ssh blsc78@gz
```
就可以登录了。

我已经在.bashrc中设置了别名:

```
alias gz='papp_cloud ssh blsc78@gz'
```
所以，我只需用命令
```
gz
```
登录就可以了。
