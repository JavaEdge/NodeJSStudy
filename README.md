<p align="center">
    <img src="resource/img/Nodejs_logo.png" width="200px">
</p>

# Study NodeJS :octocat:

## NodeJS是什么
NodeJS是一个平台， 提供javascript运行环境。  
NodeJS基于事件机制，异步执行。
可用于高并发开发。

## 事件机制
<p align="left">
    <img src="resource/img/EventLoop.jpg" width="350px">
</p>
Node.js 是单进程单线程应用程序，但是通过事件和回调支持并发，所以性能非常高。

Node.js 的每一个 API 都是异步的，并作为一个独立线程运行，使用异步函数调用，并处理并发。

Node.js 基本上所有的事件机制都是用设计模式中观察者模式实现。

Node.js 单线程类似进入一个while(true)的事件循环，直到没有事件观察者退出，每个异步事件都生成一个事件观察者，如果有事件发生就调用该回调函数.

## 优点 & 缺点
优点 | 缺点
----- | -----
事件机制，适于大规模系统 | 单线程运行，发生问题，可能会影响这个系统
使用Javascript - 很多多人都了解JS  | 也会有一些JS自身的bug
使用Gogoole用c++开发的V8 JS引擎 | 速度不比c/c++开发的服务快
有很多开源的NPM模块使用 | 

### 现有的JS引擎
企业或团体 | 引擎 
----- | -----
Internet Exploer | Chackra
Google | V8
Mozila | Spider Monkey
Apple | Squirrel Fish
Opera | Karakan 

## 安装
[http://nodejs.org](http://nodejs.org)
支持Windows, Linux, MacOS

## 运行代码模式

```javascript
>node
>colsole.log('Hello, World!');
Hello, World!
```
## 运行JS文件

helloWorld.js
```javascript
console.log('Hello, world!');
```

```javascript
>node helloWorld.js
Hello, world!
```

