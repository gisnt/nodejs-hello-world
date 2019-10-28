
# nodejs-hello-world

这是一个Node.js的示例程序，运行后在本机8080端口开启Web服务，浏览器输入localhost:8080后，显示“hello world”。

* 使用方法

启动服务器：node my_web_server.js
客户端访问：http://localhost:8080

-------------------------------------------------------------------------------------
**nodejs的基本概念 (https://blog.csdn.net/weixin_44114310/article/details/90452246)**

# nodejs的基本概念
## 一.为什么要学习nodejs
**为什么要学习服务端开发?**

1.通过学习node.js开发理解服务器开发,web请求和响应过程,了解服务器端如何与客户端配合

2.作为前端开发工程师(FE)需要具备一定的服务端开发能力

3.全栈工程师的必将之路

**服务器开发语言有很多,为什么要选择nodejs**

1.降低编程预压切换成本,(nodejs实际上还是用的JavaScript)

2.nodejs是前端项目的基础设施,前端项目中用到大量的工具,都是基于nodejs实现的

3.nodejs在处理高并发上有得天独厚的优势

4.前端就是要掌握,别想太多了,学就对了

参考资料：

Node.js 究竟是什么？(https://www.ibm.com/developerworks/cn/opensource/os-nodejs/)

为什么要用 Node.js(http://blog.jobbole.com/100058/)

## 二.nodejs是什么
node.js，也叫作node，或者nodejs，指的都是一个东西。

node.js官方网站(https://nodejs.org/)

node.js中文网(http://nodejs.cn/)

node.js 中文社区(https://cnodejs.org/)

Node.js是一个Javascript运行环境(runtime environment)，发布于2009年5月，由Ryan Dahl开发，实质是对Chrome V8引擎进行了封装。Node.js对一些特殊用例进行优化，提供替代的API，使得V8在非浏览器环境下运行得更好。

Node.js 是一个基于 Chrome V8 引擎的 JavaScript 运行环境。

         1. nodejs是在服务端运行javascript的运行环境
         2. javascript并不只是能运行在浏览器端，浏览器端能够运行js是因为浏览器有js解析器，因此只需要有js解析器，任何软件都可以运行js。
         3. nodejs可以在服务端运行js，因为nodejs是基于chrome v8的js引擎。

Node.js 使用了一个事件驱动、非阻塞式 I/O 的模型，使其轻量又高效。

Node.js 的包管理器 npm，是全球最大的开源库生态系统。

nodejs的本质：不是一门新的编程语言，nodejs是javascript运行在服务端的运行环境，编程语言还是javascript

## 三.nodejs与浏览器的区别
相同点：nodejs与浏览器都是浏览器的运行环境，都能够解析js程序。对于ECMAScript语法来说，在nodejs和浏览器中都能运行。

不同点：nodejs无法使用DOM和BOM的操作，浏览器无法执行nodejs中的文件操作等功能

#  四.nodejs可以干什么
- 开发服务端程序

- 开发命令行工具（CLI），比如npm,webpack,gulp,less,sass等

- 开发桌面应用程序（借助 node-webkit、electron 等框架实现）
