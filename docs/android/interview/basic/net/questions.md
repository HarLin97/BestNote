# 面试题

### CSMA/CD有什么作用？

CSMA/CD即带冲突检测的载波监听多路访问技术，应用在 `OSI` 的第二层数据链路层，是为了解决共享介质的传输效率的问题。**其原理简单总结为：先听后发，边发边听，冲突停发，随机延迟后重发**。

***

### Http会话的过程？

  - 建立tcp连接
  - 发出请求文档
  - 发出响应文档
  - 释放tcp连接

***

### TCP协议如何实现可靠传输？

TCP 协议是通过ARQ协议以及等待、确认、重传等机制实现可靠传输。