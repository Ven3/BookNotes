# Progress

## 2019年7月10日

https://github.com/Snailclimb/JavaGuide/blob/master/docs/java/Java%E5%9F%BA%E7%A1%80%E7%9F%A5%E8%AF%86.md#6-%E4%BB%80%E4%B9%88%E6%98%AF-java-%E7%A8%8B%E5%BA%8F%E7%9A%84%E4%B8%BB%E7%B1%BB-%E5%BA%94%E7%94%A8%E7%A8%8B%E5%BA%8F%E5%92%8C%E5%B0%8F%E7%A8%8B%E5%BA%8F%E7%9A%84%E4%B8%BB%E7%B1%BB%E6%9C%89%E4%BD%95%E4%B8%8D%E5%90%8C

## 2019年7月11日

- 字符型常量和字符串常量的区别
    > char在Java中占两个字节
    > float 32bit 4字节

- String, StringBuilder 和 StringBuffer
    >操作少量的数据: 适用String
    > 单线程操作字符串缓冲区下操作大量数据: 适用StringBuilder
    > 多线程操作字符串缓冲区下操作大量数据: 适用StringBuffer

- hashCode（）与equals（）的相关规定
    > 如果两个对象相等，则hashcode一定也是相同的
    > 两个对象相等,对两个对象分别调用equals方法都返回true
    > 两个对象有相同的hashcode值，它们也不一定是相等的
    > 因此，equals 方法被覆盖过，则 hashCode 方法也必须被覆盖
    > hashCode() 的默认行为是对堆上的对象产生独特值。如果没有重写 hashCode()，则该 class 的两个对象无论如何都不会相等（即使这两个对象指向相同的数据）

- 简述线程、程序、进程的基本概念。以及他们之间关系是什么?
https://github.com/Snailclimb/JavaGuide/blob/master/docs/java/Java%E5%9F%BA%E7%A1%80%E7%9F%A5%E8%AF%86.md#29-%E7%AE%80%E8%BF%B0%E7%BA%BF%E7%A8%8B%E7%A8%8B%E5%BA%8F%E8%BF%9B%E7%A8%8B%E7%9A%84%E5%9F%BA%E6%9C%AC%E6%A6%82%E5%BF%B5%E4%BB%A5%E5%8F%8A%E4%BB%96%E4%BB%AC%E4%B9%8B%E9%97%B4%E5%85%B3%E7%B3%BB%E6%98%AF%E4%BB%80%E4%B9%88