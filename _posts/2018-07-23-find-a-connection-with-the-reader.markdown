---
layout: post
title:  第一次写博客，记录一下我用jekyll的过程...
date:   2020-07-21 19:54:35 +0300
image:  02.jpg
tags:   Myblog
---
**第一步：准备一个GitHub账号，新建一个Repository。用自己的“名字.github.io"命名。**

**第二步：在本地安装Jekyll，推荐查阅官网:https://www.jekyll.com.cn/docs/installation/。**

**第三步：去Jekyll themes官网选自己喜欢的blog模板。然后可以fork到你自己的仓库，或者下载到本地,自己改好后git上去。连接：http://jekyllthemes.org/**



## First.

1. 准备一个github账号，有手就会，不说了吧。

2. 新建一个repository。for example 我的github名字叫dithyrambus，所以新建一个这样的仓库。

   ![1600692188098]({{ site.baseurl }}/images/first1.png)

***

### Second!

**1.**在RubyInstaller下载Ruby+Devkit,一直下一步，最后执行ridk安装。

**2.**在开始菜单打开一个新的名利提示符窗口，官网说这样对PATH环境变量的更改就会生效。

![1600780425114]({{site.baseurl}}/images/second1.png)

我这安装完之后正好有一个这个，打开安装Jekyll和bundler，via： **gem install jekyll bundler** 

安装之后检查一下。via：**jekyll -v**

**3.**你可以在./myblog 目录下新建一个全新的jekyll网站。via：**jekyll new myblog**

然后cd进去，然后启动本地服务器 via：**bundle exec jekyll serve**.

**4.**然后方问localhost：4000，里边是空的，意思是让你自己往里边写，那谁会啊，赶紧去jekyllthemes下载一个现成的，往下看

****

### Third.

**1.**直接去Jekyll themes官网选自己喜欢的blog模板。你可以先fork到自己仓库。在github上边改，但是生效有点慢，要刷新好多次才有效果，所以在这里我们下载到本地，然后用启动jekyll服务器，查看效果比较方便。

**2.**下载到本地，解压好，在文件目录里直接进黑窗口。(注意文件夹目录不要有中文，会发生不好的事情！！)

![]({{site.baseurl}}\images\third1.png)

**3.**然后    via：**bundle install**            接着 via: **bundle exec jekyll server**

再然后你会看见这样的结果，如多报错你可以baiduzhidao.

![]({{site.baserul}}\images\third2.png)