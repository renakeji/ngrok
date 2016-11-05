本库基于 ngrok 1.7 做了如下修改：
* 因官方已不维护v1版本，移除版本更新检查，且配置文件中的`update`参数不再有效
* 移除`HTTP Proxy`功能，配置文件中的`http_proxy`参数不再有效。而且该功能会导致启动ngrok时自动连接一个第三方的IP地址，如果连不上会不再继续连接ngrokd server