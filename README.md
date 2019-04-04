# QiNiu_JS_GenToken

七牛云存储，全前端上传不走后台服务器。



## 七牛云存储，JS__Token生成配置

> 配置文件路径：/GenToken/getToken.js，配置项如下

- accessKey：七牛的accessKey

- secretKey：七牛的secretKey

- scopeName：存储空间名称

- deadline：token有效截止日期，时间戳表示。

最后运行/GenToken/index.html文件即可。



## 使用Webuploader上传文件至七牛云存储

> 配置文件路径：/FileUpload/upload.js

* siteUrl：存储空间配置的默认域名

* siteToken：上一步生成的有效token

最后运行/FileUpload/index.html文件即可。
