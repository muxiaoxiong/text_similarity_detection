# 文本相似度检测

编程语言：
python3.7

主要技术：
jieba / TF-IDF / MultinomialNB / KMeans / editdistance / TopN

项目简介：
通过分析不同机构发布的文章，判断是否有文章抄袭的情况，并找到原文和抄袭的文章，以及具体相似的句子。可以应用于毕业论文查重，IP作品及文本抄袭检测

主要工作：
对采集的文档进行数据清洗，采用TF-IDF提取文本特征，使用朴素贝叶斯分类器进行写作风格分类，并针对模仿自己写作风格的文章进行抄袭检测。先采用聚类算法对文档进行聚类降维，针对预测写作风格一致的作品，进行相似度检测及编辑距离检测


