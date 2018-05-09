# JavaException
Processing for Java Exception 
异常对象都派生于Throwable类的一个实例。
派生于RuntimeException的异常包含下面几种情况：
1）错误的类型转换 2）数组访问越界 3）访问空指针
不是派生于RuntimeException的异常包括：
1）试图在文件尾部后面读取数据 2）试图打开一个不存在的文件 3）试图根据给定的字符串查找Class对象，而这个字符串表示的类并不存在

如果出现RuntimeException异常，那么一定就是你的问题。
