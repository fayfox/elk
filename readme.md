# ELK集群搭建demo

> 单机搭建demo，学习用。

采用7.9.0版本搭建

由于官方Docker镜像下载极其缓慢，这里使用在阿里云创建了私人公开镜像，ES的镜像安装了ik和pinyin插件，Logstash和Kibana没做任何修改。

Elasticsearch采用集群的方式，部署了3个实例。