# JJAFNetworking
封装AFNetworking

# 使用方法
每一个api继承JJAFNApi。

* 重写JJAFNApi+RewriteMethod类中的方法，改变请求方式或者参数等。

* 重写JJAFNApi+HandleMethod类中的方法，处理数据。

* 该框架实现回调和Block两种方式获取结果。

* 手动导入：引入头文件JJAFNetworking.h

* cocoapods导入：pod 'JJAFNetworking', '~> 1.0'
