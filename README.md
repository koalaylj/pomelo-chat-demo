## c/s 聊天例子

> + 目的：实现了一个简单的c/s结构聊天例子，演示了c#客户端和pomelo服务器的交互，使用原生socket通信方式。本来是想用unity3d和pomelo通信，但是unity3d里面处理异步比较麻烦，为了使例子简洁，这里用纯.net环境演示了这个例子。
> 
> + 环境：win7 + vs2012 + nodejs(v0.10.25) + pomelo(~0.9.0)
> 
> + 客户端：依赖pomelo官方的客户端.net库 [pomelo-unityclient-socket](https://github.com/NetEase/pomelo-unityclient-socket/) library，这里直接以源码的方式加进来，方便学习。
>
> + 服务端：是pomelo官方例子 [chatofpomelo-websocket](https://github.com/NetEase/chatofpomelo-websocket)

## 使用方式

> * 1. 启动服务端 cd 到 pomelo-chat-demo\chat-server\game-server 下执行
> ``` bash
>   pomelo start
> ```
> * 2. 直接运行 Pomelo-NativeSocket 项目启动或者直接运行编译好的exe启动客户端。此时就可以进行聊天了。
