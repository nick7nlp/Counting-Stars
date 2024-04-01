## 数星星

### 2024.4.1: 大海捞多针（LangChain版本）

近期，我们发现LangChain也给出了多针的实验版本，具体介绍可见[Here](https://blog.langchain.dev/multi-needle-in-a-haystack/).


### 2024.3.27: 大海捞多针（OpenCompass版本）

在论文中，我们只是简单介绍了**数星星**和**大海捞针**的区别，而且没有强调说明大海捞**多针**的实测情况。

简而言之，插入多个针是插入多个线索，实现让大模型找到并串联推理多个线索，并获得最终答案（[具体介绍](https://opencompass.org.cn/doc)）。

但目前大海捞多针并不需要找到所有针才可答对问题，只需要找到最后一根针即可，

甚至只插入最后一根针模型也可以获得正确答案。

介绍：

<img src="needles_intro.png" width=80%>

#### Kimi-多针简单测试：（只插入最后一根针）

##### OpenCompass官方指定上下文数据：

<img src="needles_v1.jpg" width=70%>

##### 红楼梦：

<img src="needles_v2.jpg" width=70%>

所以，根据目前的结果看，大海捞多针策略存在一定的弊端。
