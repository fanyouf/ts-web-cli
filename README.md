
# ts-web-cli
在浏览器端，构建一个最小环境来学习 typescript 。

- 自动builder
- 在网页中使用
- 通过live-server自动刷新
- 支持less
- 使用gulp


## 安装

```
npm install -g cli-web
```

## 创建项目
```
cli-web create 
```
根据提示，输入项目名称和提示信息。



## 启动并使用项目
要启动项目，你必须先安装两个包：gulp,live-server。

1. gulp。如果够你还没有安装，请先安装。安装命令是：
````
npm install -g gulp
````
2. live-server。如果够你还没有安装，请先安装。安装命令是：
````
npm install -g live-server
````


接下来，分别执行两个命令：

命令1 : 

```
npm run gulp
```
它会执行gulpfile.js中的配置。

命令2 : 

```
npm run start
```
