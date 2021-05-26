---
title: Hello World
categories: Demo
tags:
- Tag0
- Tag1
- Tag2
toc: true
sticky: 100 
only:
- home
---
Welcome to [Hexo](https://hexo.io/)! This is your very first post. Check [documentation](https://hexo.io/docs/) for more info. If you get any problems when using Hexo, you can find the answer in [troubleshooting](https://hexo.io/docs/troubleshooting.html) or you can ask me on [GitHub](https://github.com/hexojs/hexo/issues).

## Quick Start

### Create a new post

``` bash
$ hexo new "My New Post"
```

More info: [Writing](https://hexo.io/docs/writing.html)

### Run server

``` bash
$ hexo server
```

More info: [Server](https://hexo.io/docs/server.html)

### Generate static files

``` bash
$ hexo generate
```

More info: [Generating](https://hexo.io/docs/generating.html)

### Deploy to remote sites

``` bash
$ hexo deploy
```

More info: [Deployment](https://hexo.io/docs/one-command-deployment.html)

```
title: Hello World
categories: Demo
tags:
- Tag0
- Tag1
- Tag2
toc: true
sticky: 100 
only:
- home
- category
- tag
```

```
{% alertbox success "成功啦o(*￣▽￣*)ブ" %}
{% alertbox danger "有危险Σ(っ °Д °;)っ" %}
{% alertbox info "有消息(・∀・(・∀・(・∀・*)" %}
{% alertbox warning "当心哦≧ ﹏ ≦" %}
```

{% alertbox success "成功啦o(*￣▽￣*)ブ" %}
{% alertbox danger "有危险Σ(っ °Д °;)っ" %}
{% alertbox info "有消息(・∀・(・∀・(・∀・*)" %}
{% alertbox warning "当心哦≧ ﹏ ≦" %}

```
{% collapse 折叠框的标题 %}

被折叠的内容 1
被折叠的内容 2
...

{% endcollapse %}
```

{% collapse 折叠框的标题 %}

被折叠的内容 1
被折叠的内容 2
...

{% endcollapse %}

```
{% collapse 折叠框的标题 open %}

被折叠的内容 1
被折叠的内容 2
...

{% endcollapse %}
```



{% collapse 折叠框的标题 open %}

被折叠的内容 1
被折叠的内容 2
...

{% endcollapse %}

```
{% colorpanel TYPE 面板框的标题 %}

面板里的内容 1
面板里的内容 2
...

{% endcolorpanel %}

TYPE是面板框的类型，可以是：

success
danger
info
warning
```

{% colorpanel success 面板框的标题 %}

面板里的内容 1
面板里的内容 2
...

{% endcolorpanel %}

```
文章概要
可以将文章开头的一段作为概要显示在首页主题部分，方法就是在需要分割的地方加入<!-- more -->即可；或者可以在文章头指定excerpt

图片资源
Hexo有为每篇文章生成一个资源文件夹，可以将图片资源以{% asset_img 文件名 备注 %}的格式插入文章，本主题引入的fancybox会自动实现对文章内图片的放大功能。
```

