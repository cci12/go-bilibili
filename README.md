# go-bilibili

### 文件目录说明

```
bilibili 
├── /.idea/
├── /config/ 配置文件包
├── /controller/ 控制器包
├── /dao/ 数据库访问
├── /document/ 敏感词词库
├── /images/ 图片引用
├── /middleware/ 中间件
│   ├── ffmpeg/ 视频截图
│   ├── ftp/ 文件服务器
│   ├── jwt/ 鉴权
│   ├── rabbitmq/ 消息队列
│   ├── redis/ 缓存
├── /service/ 服务层
├── /util/ 工具
├── .gitignore
├── /go.mod/
├── LICENSE
├── main.go
├── README.md
└── router.go
```

### 使用到的技术
框架相关：
- [Gin](https://gin-gonic.com/docs/)
- [Gorm](https://gorm.io/docs/)

服务器相关：
- [Nginx](https://www.nginx-cn.net/)
- [vsftpd](https://www.linuxfromscratch.org/blfs/view/svn/server/vsftpd.html)
- [ffmpeg](https://ffmpeg.org/documentation.html)
- [goftp](http://t.zoukankan.com/lvdongjie-p-9554849.html)

中间件相关：
- [Redis](https://redis.io/docs/)
- [RabbitMQ](https://www.rabbitmq.com/documentation.html)

数据库：
- [MySQL](https://dev.mysql.com/doc/)

