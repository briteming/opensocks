##### 简单的Socks5代理

- 只支持Socks CONNECT的域名
- 不支持UDP forward , Bind

-isClient=false
-p=your-port

安装方法：
go install github.com/briteming/opensocks@latest

u will get the exec file opensocks.

opensocks -isClient=false -p=2455

在服务区的2455端口上，就运行了一个socks proxy server.该socks proxy server可以用作各类 tunnel程序的后端程序。
