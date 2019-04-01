# 怎么搭建一个github的blog
## 第一步 fork
fork barryclark/jekyll-now
在settings里面修改Repository name，可以用xxx.github.io来标识你想要的域名
接着就可以通过xxx.github.io来访问你的博客了，如果报404直接看下一个就好

## 第二步 自定义和访问你的博客
你可以在_config.yml文件里面修改你的网站的名字和描述还有图标和其它许多的内容。
当你修改了_config.yml或者其它任何文件，github将会用jekyll重建你的网站。重建后的个人网站将会在几秒钟后更新，接着你就可以通过访问xxx.githu.io，来看你的博客了，如果还是404，就再等一会，最多不超过10分钟就会更新完毕。

## 第三步 发布你的第一篇博客
编辑 /_posts/2014-3-3-Hello-World.md 这个文件来发布你的第一个博文。当然也可以在/_posts/中创建一个新的文件。
