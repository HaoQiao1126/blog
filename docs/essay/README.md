## 什么是 Serializable 接口 ？

一个对象序列化的接口，一个类只有实现了Serializable接口，它的对象才能被序列化

## 什么是序列化 ？

将对象的状态信息转换为可以存储或传输的形式的过程，在序列化期间，对象将其当前状态写入到临时存储区或持久性存储区，之后，便可以通过从存储区中读取或反序列化对象的状态信息，来重新创建该对象

## 什么情况下需要序列化 ？

当我们需要把对象的状态信息通过网络进行传输，或者需要将对象的状态信息持久化，以便将来使用时都需要把对象进行序列化

