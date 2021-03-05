#  NLP分析工具

**NLP分析工具**是一款基于NLP开源算法、模型库（jieba、spacy、paddlenlp），开发上前后端结合flask_api+js+bootstrap+echarts，通过机器学习算法（聚类、主成分分析、图网络GraphicalLasso）实现文本数据词语之间的关联性分析。涉及参数如下：

- **sentence** ：待分析文本，可编辑或上传txt文件
- **embedding** ：词向量模型选择（开源的词向量库）
- **cor** ：相关性度量方式（协方差矩阵、精度矩阵（偏相关））
- **xy** ：降维算法选择 ，Locally linear embedding（LLE）是一种非线性降维算法，它能够使降维后的数据较好地保持原有流形结构。
- **cluster** ：聚类算法选择，AP（非约束簇）- 与kmeans相比，不需要指定k值
- **topK** ：分析关键词的数量，默认20个，重要性从高到低排序
- **withWeight** ：每个关键词的权重


![avatar](/static/picture/pic01.jpg)

![avatar](/static/picture/pic02.jpg)

![avatar](/static/picture/pic03.jpg)
