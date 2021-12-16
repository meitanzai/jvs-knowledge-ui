## docker快速安装方式

需要本机安装

* jdk1.8
* maven
* docker
* node

## 下载后端代码

`
git clone https://gitee.com/software-minister/jvs.git
`

`
mvn package -Dmaven.test.skip=true
`

`docker-compose build`

`docker-compose up -d`

## 下载前端代码

`
git clone https://gitee.com/software-minister/jvs-knowledge-ui.git
`

`npm install `

`npm run build`

进入docker目录`cd docker`

`docker-compose build`

`docker-compose up -d`


访问`http://localhost` 即可访问

用户名：admin
密码:admin
