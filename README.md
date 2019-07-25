
### 项目名称

基于区块链水印技术的视频点播网站

### 项目背景


### 项目功能
本项目分为前台和后台
主要的修改点在于：
* 一是视频上传时加水印，这一点在视频上传时的后台实现，需要调用watermask里面封装的函数。
* 二是付费播放，在视频打开时。
* 三是侵权监测，主要是通过用户上传时对比和用户举报两种方式。
* 四是区块链浏览器，提供用户对区块链的查询功能

前台功能
- 视频展示
- **视频播放（付费播放）**
- **侵权反馈**
- **区块链浏览器**
- 详情评论
- 个人中心

后台功能
- **视频管理(视频上传，加水印)**
- 评论管理
- 用户管理
- 反馈管理

###项目文件介绍
- browser 区块链浏览器
- comment 视频评论
- contract 智能合约  
contractApi.py 封装和区块链合约交互功能
- myadmin 视频管理后台  
视频上传加水印、上传时版权监测在此实现
- static 静态文件
- templates 模板文件
- users 用户
- video 视频  
视频付费播放、侵权举报在此实现 
- watermask 水印  
watermaskApi.py封装和水印相关的功能


### 演示地址

[https://v.mypython.me/](https://v.mypython.me/)

后台管理地址

[https://v.mypython.me/myadmin/](https://v.mypython.me/myadmin/)

测试账号

用户名：admin123456  密码：admin123456

### 适合人群

python初级学员、大学生、系统设计人员

### 技术栈
python/django/nginx/mysql/semantic-css/jquery/html

### 源码
[https://github.com/geeeeeeeek/videoproject/](https://github.com/geeeeeeeek/videoproject/)


### 开发教程
[https://mypython.me](https://mypython.me)
