# B/S架构

第一层是[浏览器](https://baike.baidu.com/item/浏览器/213911?fromModule=lemma_inlink)，即[客户端](https://baike.baidu.com/item/客户端/101081?fromModule=lemma_inlink)，只有简单的输入输出功能，处理极少部分的事务逻辑。由于客户不需要安装客户端，只要有浏览器就能上网浏览，所以它面向的是大范围的用户，所以界面设计得比较简单，通用。

第二层是[WEB服务器](https://baike.baidu.com/item/WEB服务器/8390210?fromModule=lemma_inlink)，扮演着信息传送的角色。当用户想要访问[数据库](https://baike.baidu.com/item/数据库/103728?fromModule=lemma_inlink)时，就会首先向WEB服务器发送请求，WEB服务器统一请求后会向数据库服务器发送访问数据库的请求，这个请求是以[SQL](https://baike.baidu.com/item/SQL/86007?fromModule=lemma_inlink)语句实现的。

第三层是[数据库服务器](https://baike.baidu.com/item/数据库服务器/613818?fromModule=lemma_inlink)，他扮演着重要的角色，因为它存放着大量的数据。当数据库服务器收到了WEB服务器的请求后，会对SQL语句进行处理，并将返回的结果发送给WEB服务器，接下来，WEB服务器将收到的数据结果转换为[HTML](https://baike.baidu.com/item/HTML/97049?fromModule=lemma_inlink)文本形式发送给浏览器，也就是我们打开浏览器看到的界面。

## 工作原理

B/S架构采取浏览器请求，服务器响应的工作模式。

用户可以通过浏览器去访问Internet上由Web服务器产生的文本、数据、图片、动画、视频点播和声音等信息；

而每一个Web服务器又可以通过各种方式与数据库服务器连接，大量的数据实际存放在数据库服务器中；

从[Web服务](https://baike.baidu.com/item/Web服务/2837593?fromModule=lemma_inlink)器上下载程序到本地来执行，在下载过程中若遇到与数据库有关的指令，由Web服务器交给数据库服务器来解释执行，并返回给Web服务器，Web服务器又返回给用户。在这种结构中，将许许多多的网连接到一块，形成一个巨大的网，即全球网。而各个企业可以在此结构的基础上建立自己的Internet。

在 B/S 模式中，用户是通过浏览器针对许多分布于网络上的服务器进行请求访问的，浏览器的请求通过服务器进行处理，并将处理结果以及相应的信息返回给浏览器，其他的数据加工、请求全部都是由Web Server完成的。通过该框架结构以及植入于操作系统内部的浏览器，该结构已经成为了当今软件应用的主流结构模式。 [2] 