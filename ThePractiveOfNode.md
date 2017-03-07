#创建程序的文件结构

- lib目录：存放服务器端的逻辑
- public子目录：存放客户端文件：如Javascripts,Stylesheets
- 指明依赖项，package.json
##包括
**name**,**version**,**description**,**dependencies**
##例如 
> {
>   "name": "chatrooms",
>   "version": "0.0.1",
>   "description": "Minimalist multiroom chat server",
>   "dependencies": {
>     "socket.io": "~0.9.6",
>     "mime": "~1.2.7",
>   }
> }
