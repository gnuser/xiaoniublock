# serialization (序列化)
这里我们首先要明白，序列化的作用是什么? [可以参考序列化][serialize]    

* 这里简单整理下,序列化是指将数据从有结构清晰的语言定义的数据形式转化为二进制字符串，        
  反序列化则是序列化的逆操作。                  

* 百度百科定义序列化如下：      
序列化 (Serialization)将对象的状态信息转换为可以存储或传输的形式的过程。在序列化期间，对象将其当前状态写入        
到临时或持久性存储区。以后，可以通过从存储区中读取或反序列化对象的状态，重新创建该对象。           

* 在bitcoin项目中，序列化相关的文件: [serialize.h][ser_src]              
  这个文件定义bitcoin项目中所有类的序列化操作，个别类除外,比如类CAddrMan是单独写了序列化操作。





















[ser_src]:https://github.com/bitcoin/bitcoin/blob/master/src/serialize.h
[serialize]:http://blog.csdn.net/kiritow/article/details/53129096