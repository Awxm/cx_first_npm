# cx_first_npm
### this is my npm packge

It is just for learning

1. npm init
2. npm adduser
3. npm login
4. 403 的时候 可以输入一下命令查看当前的登录源： npm config get registry /
   如果是淘宝镜像切换 npm config set registry=http://registry.npmjs.org
   设置完之后在查看当前登录的源地址：
5. npm publish 上传命令
6. npm unpublish first_npm_cx -- force(删除全部)
7. npm unpublish  first_npm_cx @1.0.0 
// git 教程 ssh 配置
1. ssh-keygen -t rsa -C "xxxxx@xxxxx.com" 完成三次回车 通过查看 ~/.ssh/id_rsa.pub 文件内容，获取到你的 public key 
2. cat ~/.ssh/id_rsa.pub
3. 通过仓库主页 「管理」->「部署公钥管理」->「添加部署公钥」
4. $ ssh -T git@gitee.com $ ssh -T git@github.com
