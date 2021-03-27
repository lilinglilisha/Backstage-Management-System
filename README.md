# Backstage-Management-System
vue
需要自己安装node-modules

安装node-modules步骤


项目中有package.json 文件 没有 node-modules  操作步骤

1:  npm  install    安装 node-modules

  npm  转 cnpm  淘宝镜像

1:  管理员 cmd 执行

2: 先安装nrm

npm install nrm -g

3: nrm ls   查看使用镜像

4: nrm use taobao   指定使用淘宝镜像

5: 如果使用cnpm   需要安装       前面如果不使用nrm切换 ,此处也可以指定淘宝镜像仓库

npm install -g cnpm --registry=https://registry.npm.taobao.org    

6: cnpm install     安装node-modules
