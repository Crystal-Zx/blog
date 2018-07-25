---
title: hexo+github搭建个人博客
date: 2018-07-24 11:33:40
tags:
---
### hexo介绍及node环境检测
##### 特点：快速、简洁且高效的博客框架
##### 环境：基于node(v8.11.3)
1. 环境及检测：
	- win+R输入cmd回车
	- cmd窗口输入node -v回车
	- 如果提示node不是内部或者外部命令,则需要重新安装node
2. 安装node环境:
	- [下载8.11.3版本](https://nodejs.org/zh-cn/)
	- 双击下载得到的mis文件，全程next安装

### 安装git(版本控制器)
1. qq群文件找安装包文件
2. [网站下载](https://git-scm.com/download/win)
    
### 安装hexo
1. [点此](https://hexo.io/zh-cn/)安装hexo
2. cmd命令:
	```
	npm install hexo-cli -g
	```
	- npm:基于node的包管理器，类似于ios的App store
	- 通过npm可以下载安装需要的插件或者框架
3. install:安装、导入
4. -g:表示全局安装(在任何的目录都可以使用)

### 初始化一个博客项目
1. 初始化项目 
	```
	hexo init 项目名
	```
2. 切换到项目目录 
	```
    cd 项目名
    ```
3. 安装项目依赖包
	```
    npm install
	```
4. 启动服务
	```
    hexo server
    ```
	*注:用vscode打开blog文件夹，启动服务,每次修改配置文件都要重启服务*
5. 打开浏览器,查看博客
	网址为:localhost(127.0.0.1):4000

### 更换博客主题
1. hexo官网有主题选项,进入链接选择自己喜欢的主题
2. 找到该主题的github地址clone其zip到本地,然后直接解压到 

### 资源网站
- [小图标](http://www.easyicon.net)