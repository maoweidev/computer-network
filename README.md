# 计算机网络课后习题答案与解析
## 第1章
### 1-01
        计算机网络有两个重要基本特点：连通性和共享。基于这两个特点，目前计算机网络可以向
        用户提供的服务有：电子邮件、网上聊天、网上游戏、网上购物、网上转账、网上检索等等。
### 1-02
        分组交换最主要的特点就是采用存储转发技术。分组交换的优点：1.高效：在分组传输的过程
        中动态分配传输带宽，对通信链路逐段占用；2.灵活：为每一个分组独立地选择最合适的转发
        路由；3.迅速：以分组作为传送单位，不先建立连接就能向其他主机发送分组；4.可靠：保证
        可靠的网络协议；分布式多路由的分组交换网，使网络有很好的生存性。
### 1-03
        电路交换：在通信之前需要建立一条被双方独占的物理通道，传输质量高，适合连续传送大量
        数据，但是线路利用率低，建立连接和释放连接需要时间。
        报文交换：无需预约传输带宽，动态逐段利用传输带宽，适合突发式数据通信，但是传输时延
        大且变化范围大，需要交换系统有高速处理和大容量存储能力。
        分组交换：将大的数据块分割成小的分组，并添加源地址、目的地址等信息，无需建立连接，
        线路利用率高，传输时间短且灵活性好，但是可能出现分组丢失或错序等问题。

        
