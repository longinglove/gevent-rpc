### gevent rpc(tcp) ###

传输方式可以配置,实现 pickle-rpc, json-rpc, msgpack-rpc

传输协议参数:

    客户端请求: [func_name(str), args, kwargs]
    服务端响应: [code, result/error_message] code:0-ok, other-error

Useage:  
见: [demo.py](https://github.com/gf0842wf/gevent-rpc/blob/master/demo.py)