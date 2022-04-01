# fasthttp 

1. 底层使用net包的Listen和Accept方法，监听端口和接收请求
2. 实现了一个workerPool来处理tcp连接
3. 通过sync.Pool减少对象创建和GC压力