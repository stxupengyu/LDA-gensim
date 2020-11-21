# LDA-gensim
使用LDA模型提取n个句子的主题，并统计每个主题出现的频次。LDA model is used to extract the topic of N sentences, and the frequency of each topic is counted.
## 需求
- gensim  
## 任务
- 内容.xlsx中有n条句子，在进行文本数据预处理后，我们对每条句子当做一个样本，选取主题数=k，通过LDA求解。在这里，我们得到句子的对应主题分布后，选取概率最大的主题作为其最终主题。 
## 文件结构
- stopwords.txt：停用词，预处理时用到。   
- record_topic.csv：最后生成每个句子的对应主题。  


