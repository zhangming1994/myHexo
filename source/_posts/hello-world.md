---
title: Hello World
cover: /img/Desktop.jpg
---

### 生成新的文章


``` bash
$ hexo new "My New Post"
```

更多: [Writing](https://hexo.io/docs/writing.html)

### 运行

``` bash
$ hexo server
```

更多: [Server](https://hexo.io/docs/server.html)

### 生成

``` bash
$ hexo generate
```

更多: [Generating](https://hexo.io/docs/generating.html)

### 部署

``` bash
$ hexo deploy
```

更多: [Deployment](https://hexo.io/docs/one-command-deployment.html)


### 常用命令[注意以下命令需要切换到blog文件夹(cd blog)执行]

``` text
hexo n "文章名称"  => hexo new "文章名称"  #这两个都是创建新文章，前者是简写模式，下同，new后面加一个draft可以生成草稿
hexo p  => hexo publish  # 发布草稿
hexo g  => hexo generate  # 生成
hexo s  => hexo server  # 启动服务预览
hexo d  => hexo deploy  # 部署
 
hexo server   # Hexo 会监视文件变动并自动更新，无须重启服务器。
hexo server -s   # 静态模式
hexo server -p 5000   #更 改端口
hexo server -i 192.168.1.1   # 自定义IP
hexo clean   # 清除缓存，网页正常情况下可以忽略此条命令
```