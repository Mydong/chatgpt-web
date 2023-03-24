# chatgpt-web

基于官方API的ChatGPT前端web

*****

### 搭建：

```
docker pull loewe24/chatgpt-web:latest
docker run --name chatgpt-web --restart=always -p 5200:5200 -d loewe24/chatgpt-web:latest
```

### 更新:

```
// 停止容器并删除
docker stop chatgpt-web && docker rm chatgpt-web
// 重新运行容器
docker run --name chatgpt-web --restart=always -p 5200:5200 -d loewe24/chatgpt-web:latest
```

*****

### 便利：

配置API URL：
`https://api.openai.com/v1/chat/completions`
这个官方的Openai的api接口是被和谐的，需要使用魔法才能正常使用.

#### 免魔法接口：

- 接口1：zeabur chatgpt-proxy 搭建：
  
  ```
  https://chatgptproxyapi.zeabur.app/proxy
  ```
  
  原作者仓库-搭建教程：
  [chatgpt-proxy/README-CN.md at main · imyuanx/chatgpt-proxy · GitHub](https://github.com/imyuanx/chatgpt-proxy/blob/main/README-CN.md ) 
  One-click deployment of the ChatGPT private proxy, power by Next.js - chatgpt-proxy/README-CN.md at main · imyuanx/chatgpt-proxy
  
  使用方式：
  本项目原配置API URL：`https://api.openai.com/v1/chat/completions` 替换为：
  `https://chatgpt-proxy-preview.zeabur.app/proxy/v1/chat/completions`  
   注：原作者示例接口，建议自己搭建使用

- 接口2：CF 
  
  
  
  
  
  
