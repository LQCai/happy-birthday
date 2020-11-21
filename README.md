# README

## 使用介紹

### 环境要求

- docker
- docker-compose

### 文本自定义

- 修改nginx/www目录下的customize.json文件，以修改姓名及祝福语
- 根据情况修改nginx/www/index.html中的文字描述

### 运行

- 进入项目目录执行下方代码
- 端口修改docker-compose.yml中的`8080`

~~~
docker-compose up -d
~~~