介绍:
====
nodeJS对我来说，这是一个独立于浏览器的一个js解析器。<br>

用处？ 开发一个web性能服务器，类似nginx。<br>

好处？看了下相关资料，发现nodeJs的IO以及事件处理真的是太方便了。当然对于某些人来说，他们是不支持的。<br>

接下来我的学习历程：我直接附上链接：点击进入github<br>

1. 模块
----

    文件：module_cache<br>

    解说：这是一个测试代码，当第一次引入一个模块时候，第二次引入模块，模块被缓存化了<br>

    文件：module_require_dir<br>

    解说：这是一个简单测试下 当我们使用require引入模块时，nodejs默认从哪些路径引入<br>

    

    文件：node_package<br>

    解说：该文件夹介绍node的package简单用法<br>

2. buffer(除了js的字符串类型之外的另外一个二进制类型)
----

    文件：node_buffer<br>

    解说：该文件介绍了buffer与字符串类型的区别<br>

3. http、server
----

    文件：node_http<br>

    解说：该文件介绍node使用http进行创建服务端以及客户端<br>

    文件 node_server<br>

    接受：该文件夹介绍node创建web服务器<br>

4.IO（文件操作）
----

    文件：node_stream<br>

    解说：该文件介绍node的文件操作、性能优化以及path相关用法<br>

5. 进程
----

    文件：node_process<br>

    解说：该文件介绍node的进程以及子进程之间通信<br>

6.异步同步事件机制
----

    文件： node_sync  <br>  

    解说：该文件介绍 node的同步与异步之间的差别，以及性能上面以及相关写法。<br>

7. 字符编码
----

    文件： node_unicode<br>

    解说：该文件夹介绍node对文件的编码相关处理<br>

8. 结合上面所有的代码，整合一个web服务器。
----

