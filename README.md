# VolleyOKhttp

Volley 整合OKhttp和Gson

实现简单的get  post  map   post json 

Volley 作为网络框架，无论缓存架构，还是重连等机制都是无可媲美的，所以我们只改变底层实现就好

实现HttpStack 重写performRequest使用okhttp 发起请求
