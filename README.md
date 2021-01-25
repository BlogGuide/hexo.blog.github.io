# hexo.blog.github.io

![http://hexo.blog.itedus.cn/](https://bugstack.cn/assets/images/2020/all-21-1.png)

- **介绍**：Hexo 是一个快速、简洁且高效的博客框架。Hexo 使用 Markdown（或其他渲染引擎）解析文章，在几秒内，即可利用靓丽的主题生成静态网页。
- **官网**：[https://hexo.bootcss.com](https://hexo.bootcss.com/)
- **案例**：[http://hexo.blog.itedus.cn](http://hexo.blog.itedus.cn/)
- **源码**：[https://github.com/BlogGuide/hexo.blog.github.io](https://github.com/BlogGuide/hexo.blog.github.io) - *克隆到自己的仓库*
- **命令**：
```java
npm install hexo-cli -g
hexo init blog
cd blog
npm install
hexo generate # 生成
hexo server   # 启动服务
```
- **特点**：
  - hexo的主题特别多，选择性很高
  - 需要本地编译后，把编译文件推送到Github
- **其他**：
  - 因为需要编译和推送，如果只是想简单的写博客，不推荐使用。
  - 但如果想把静态博客部署到个人的服务器，那么就非常适合了。
