## 使用Hero#ku部署V#r#ay高性能代理服务两种协议

> 提醒： Hero#ku 已经封禁本专案，请 Fork 本专案后，将 README.md 中的 用户名 替换为 自己的用户名

## 概述

Hero#ku 为我们提供了免费的容器服务，我们不应该滥用它，所以本项目不宜做为长期翻墙使用。
- [x] 支持VM#ess和VL#ESS两种协议
- [x] 支持自定义websocket路径
- [x] 伪装首页（3D元素周期表）
- [x] HTML5测速
- [x] 使用v#r#ay最新版构建
* 请求`/`，返回3D元素周期表
* 请求`/speedtest/`，html5-speedtest测速页面
* 请求`/test/`，文件下载速度测试
* 请求`/ray`（可配置）websocket路径

## 服务端

[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://dashboard.heroku.com/new?template=https://github.com/wilhelmma/hero-demo0511) 

点击上面紫色`Deploy to Hero#ku`，会跳转到hero#ku app创建页面，填上应用的名称、选择节点(建议用欧洲节点，美国节点会自动删除YouTube评论与点赞！)、按需修改部分参数和UUID后点击下面`deploy`开始创建部署应用  
如出现错误，可以多尝试几次，待部署完成后页面底部会显示`Your app was successfully deployed` 
  * 点击Manage App可在Settings下的Config Vars项**查看和重新设置参数**  
  * 点击Open app跳转域名即为hero#ku分配域名，格式为`app.herokuapp.com`，用于客户端  
  * 默认协议密码为`24b4b1e1-7a89-45f6-858c-242cf53b5bdb`，路径为`/ray`


