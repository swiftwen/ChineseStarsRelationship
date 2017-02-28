# 中国明星数据爬取

# 目标

代码没有技术含量，仅仅告诉大家一个好的数据源！

爬取网络上的数据，建立一个完整的人物关系网。这里是爬取数据的部分，使用了jsoup就可以了，主要还是网站比较好。


# 方法

深度优先爬取，直到队列没有种子。暂时没有使用多线程。


# 举例

[http://www.baike.com/wiki/%E5%91%A8%E6%9D%B0%E4%BC%A6](http://www.baike.com/wiki/%E5%91%A8%E6%9D%B0%E4%BC%A6)里有完整的关系网络信息，简单解析一下就好啦。

# 结果展示

### 爬取得过程（log4j的日志）

![](/img/img1.png)

### 图片展示 

![](/img/img2.png)

### 结果（尚未爬取结束）
![](/img/img3.png)


