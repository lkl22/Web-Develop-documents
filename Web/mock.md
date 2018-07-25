RAP：[https://github.com/thx/rap2-delos](https://github.com/thx/rap2-delos)

#### Redis

[https://redis.io](https://redis.io)

```
//安装
$ wget http://download.redis.io/releases/redis-4.0.10.tar.gz
$ tar xzf redis-4.0.10.tar.gz
$ cd redis-4.0.10
$ make

//配置
vim /etc/profile
    //后台启动Redis服务指令
    alias redis-server='nohup /developer/software/redis-4.0.10/src/redis-server &'
    //Redis客户端运行指令
    alias redis-cli='/developer/software/redis-4.0.10/src/redis-cli'
    
source /etc/profile
//启动
$ redis-server
//测试
$ redis-cli
redis> set foo bar
OK
redis> get foo
"bar"
```

#### rap2-delos

后端数据API服务器，基于Koa + MySQL：[https://github.com/thx/rap2-delos](https://github.com/thx/rap2-delos)

#### rap2-dolores

前端静态资源，基于React：[https://github.com/thx/rap2-dolores](https://github.com/thx/rap2-dolores)



