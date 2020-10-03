# v2rayToClash
个人使用的v2ray订阅地址转clash的yaml的脚本

适配了 network=ws的方式

使用方法：

```bash
## 下载项目
git clone https://github.com/scjtqs/v2rayToClash
## 进入项目目录
cd v2rayToClash
## 通过composer安装依赖
composer require mustangostang/spyc
## 或者使用项目中的composer
php composer.phar require mustangostang/spyc
## 通过php脚本进行转换,修改v2c.php中的url订阅地址
php v2c.php
## 通过docker-compose启动 docker服务
docker-compose up -d
```

然后 打开浏览器 http://127.0.0.1:1234 
即可使用yacd管理clash