# mgweb
go语言编写的 mongodb web管理工具

项目使用beego框架实现

## 项目依赖
项目基于beego,mgo等项目，使用时需提前安装依赖库

## 安装
$ git clone https://github.com/29392964/mgweb 

$ go build

$ ./mgweb

##相关配置
可以在conf/app.conf文件中配置

服务端口

每页显示数据条数

##登录
mongouri 格式如下：

user:password@ip:port/db 

#DEMO
http://mgweb.no3g.com

##使用golang docker交叉编译
docker run -it -v /Users/yuecaili/Documents/work/golang:/usr/src/myapp  -w /usr/src/myapp golang:1.7 bash

export GOPATH="/usr/src/myapp"

go build
