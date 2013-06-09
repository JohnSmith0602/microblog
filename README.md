microblog
=========

基于node.js开发的微博系统

这个基于node.js开发的微博终于发布到github上了

这个项目具有教学的作用，其中我把项目依赖的node_modules文件夹全部删除了，为了是最小化托管

下载项目后，可以进入项目的根目录(cd microblog)里，用npm install安装项目的依赖

	"express": "*",
    "ejs": "*",
    "mongodb": "*",
    "connect-mongo": "*",
    "mongoose": "*",
    "socket.io": "*"

然后安装好你的node.js和mongodb,开启mongodb数据库服务，就可以命令行node app开启整个项目

项目利用socket.io实现了每一个人发一条微博后，在3秒钟内，会被分发到所有同样访问到主页的人的页面上，
已经实现了微薄的基本功能。

这里也利用了mongoose驱动，使数据库的操作更规范话

接下来的日子里将不断更新优化这个项目。还有很多功能没有实现

如果大家有什么疑问，建议，都可以直接联系我本人,或者fork我的项目自行修改，然后可以pull request我

我一有时间会完善这个项目的，书面教程，发布在wiki页面

==========================================================================
新浪微薄：@Cook1凡

微信：kanny87929

qq：32582048

email: 32582048@qq.com
