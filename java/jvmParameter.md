# JVM参数
jvm参数设置以及参数具体含义
## 参考文档
[jdk13参考](https://www.oracle.com/java/technologies/javase/vmoptions-jsp.html)

## 常用jvm参数，必会


## -X参数
-X 参数为jvm中稳定参数，基本不会改变含义和用法
### 有关内存的参数
1、-Xmx|m、g   
设置jvm最大堆内存，不带单位时，用字节表示   
2、-Xms|m、g  
设置jvm最小堆内存，-Xms和-Xmx长设置成一样的，避免jvm扩容，影响性能   
3、-Xloggc:/path/log   
设置存储jvm gc日志路径   
4、


## -XX:参数
-XX:参数为不稳定参数，可能随着jdk版本升级而废弃
1、-XX:NewSize=1G   
设置新生代大小参数   
2、-XX:MaxNewSize=1G   
新生代最大内存

## -D参数
-D参数为用户自定义参数