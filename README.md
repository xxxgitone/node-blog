# node.js学习
### 1.node环境配置，以安装好
### 2.mongodb安装与配置
mongodb对windows的支持不太友好，主要是windows7 32位以及之前版本的。我的电脑苦逼的就是windows7 32位，发现最新mongodb版本支持的最低的也是windows7 64位，连可视化管理工具都是这样。心累，最后下了mongodb 3.0 版本的，可视化工具为mongodbChef。
* 安装路径为 `E:\MongoDB` 并手动创建一个文件夹db
* 开启服务：cmd使用命令进入安装目录下的bin目录下，输入命令

		mongod --dbpath E:\MongoDB\db --port=27017
* 重新打开一个cmd窗口，继续进入到bin目录下

		mongo.exe
		
		
* 安装好mongodbChef，点击connect，输入一个数据库名如：localhost，连接即可。

### 3.node知识和命令
* node <文件名>  运行某个文件
* 安装supervisor，以便修改代码后自动重启服务,使用`supervisor --harmony <文件名>`启动

		npm install supervisor -g

