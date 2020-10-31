# login_GUANGZHOU_by_papp_cloud


在利用ssh登陆远程服务器之前，需要您先登录papp_cloud。比如，

```shell
papp_cloud login -u huanggang08@163.com -p
password: Dylan***8
```
然后，用命令

```
papp_cloud ssh blsc784@gz
```
就可以登录了。
我已经在.bashrc中设置了别名:
```
alias gz='papp_cloud ssh blsc784@gz'
```
所以，我只需用命令
```
$gz
```
登陆就可以了。

