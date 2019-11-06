# -NPM-
搭建NPM服务器

# 安装
$ npm install -g sinopia

# 启动 -- 默认端口4873
$ sinopia

# 帮助
$ sinopia -h

# 使用时设置代理
$ npm set registry http://localhost:4873/

# 启动：指定主机和端口
$ sinopia -l 192.168.7.101:8000

# 安装nrm
$ npm install -g nrm

# 配置nrm
$ nrm add mynpm http://192.168.7.101:8000

# 使用nrm
$ nrm use mynpm

# 枚举代理
$ nrm ls

# 切换代理
$ nrm use mynpm

# 创建用户：输入用户名，密码，邮箱用户创建完毕
$ npm adduser --registry http://192.168.7.101:8000

# 初始化：进入你要上传的代码目录，执行初始化。这个过程中要输入项目名，版本号，作者，开源协议等信息，自动生成package.json文件。
$ npm init

# 登陆
$ npm login

# 设置本地仓库地址
npm config set prefix D:\ZXF\npmServer\global_node_modules

# 发布到本地仓库（要开放读写权限）
npm publish --registry http://localhost:4873

# 发布：在项目目录下：发布包名称以packa.json为准（而不是项目目录名）
$ npm publish

# 查看
$ http://192.168.7.101:8000



# 用户：使用：添加代理：开发环境
$ nrm add mynpm http://192.168.7.101:8000

# 用户：使用：安装
$ npm install klpa-bridge
