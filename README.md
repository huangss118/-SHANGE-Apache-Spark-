# -SHANGE-Apache-Spark-源码阅读笔记

## Overview {#overview}

本笔记是我于2016年末学习[Apache Spark](http://spark.apache.org/)源码时的阅读笔记。

本文档对应的 Apache Spark 源码版本为 1.3.0。

本人经验、能力以及实验条件实在是有限，在研究过程中难免会有诸多不足。若在阅读本文档时发现有错误与遗漏之处，还望能够提出指正。

一开始想要用GitBook来记录笔记也是受到了[@ihainan](http://github.com/ihainan)的影响，一开始的笔记格式也是参考了他的，他的[GitBook](https://ihainan.gitbooks.io/spark-source-code/content/index.html)也有很多干货，顶礼膜拜。

## How to Read {#how-to-read}

在学习过程中，Matei Zaharia 发表的论文_Resilient Distributed Datasets: A Fault-Tolerant Abstraction for In-Memory Cluster Computing_和他的博士毕业论文_An Architecture for Fast and General Data Processing on Large Clusters_，这篇博士论文已经由CSDN上发布中文版本，如果有需要的话，可以用于参考。Jerry Lead 关于 Apache Spark 内部机制的[系列文章](https://github.com/JerryLead/SparkInternals)，ColZer 关于 Apache Spark 的[学习笔记](https://github.com/ColZer/DigAndBuried)，等等文章资料都给了我相当多的帮助。在阅读本系列文章时，我十分推荐配合上面几篇材料一起学习，不同文章解析 Apache Spark 的角度各不相同，相信都会对你有所启发。

