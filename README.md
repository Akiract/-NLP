# 学习NLP的PR

Dataset来源于kaggle的IMDB影评分析:https://www.kaggle.com/c/word2vec-nlp-tutorial/data

#大致流程可以分为:
导入数据集->将reviews处理为review->利用gensim训练Word2Vec模型->利用模型处理数据集词向量->采用逻辑回归fit训练集->预测
