---
layout:     post
title:      Review on Recent Advances in Information Mining From Big Consumer Opinion Data for Product Design
subtitle:   
date:       2019-1-28
author:     WRW
header-img: img/post-bg-desk.jpg
catalog: true
tags:
    - 大数据 用户评论 数据挖掘 产品设计
---


## 用于产品设计的消费者评论数据挖掘最新进展综述

### 摘要
Studies on information extraction of big consumer opinion data are explained from various perspectives, including data acquisition, opinion target recognition, feature identification and sentiment analysis, opinion summarization and sampling, etc.

从数据获取，评论目标识别、特征识别、情感分析、评论总结和抽样等不同方面进行阐述。

Reviews on information utilization of big consumer opinion data for product design are explored in terms of how to extract critical customer needs from big consumer opinion data,
how to connect the voice of the customers with product design,
how to make effective comparisons and reasonable ranking on similar products, 
how to identify ever-evolving customer concerns efficiently, and so on.

如何从用户评论大数据中提取关键用户需求
如何将客户的想法与产品设计联系起来
如何在相似产品之间进行有效对比以及合理排名
如何有效地识别不断变化的用户需求


### 1 Introduction
![](https://ObliviousToZero.github.io/img/文献/1.png)
Fig. 1 A framework of classical procedure regarding information mining from big consumer opinion data for product design

This paper is organized as follows: In Sec. 2, a comprehensive review is given focusing on how big consumer opinions are being processed and exploited to gain critical insights into product design. Next, in Sec. 3, existing approaches with respect to how big consumer opinions can be utilized in design are revealed. Finally, some open research challenges, trends, potential future studies are presented to highlight the significance and value of information mining from big consumer opinion data for product design. 

第二节全面介绍了如何处理用户评论大数据，并从中挖掘出有关产品设计的关键信息。
第三节介绍了利用用户评论来进行产品设计的现有的方法。
最后说明了目前存在的挑战与未来的发展趋势。

### 2 Processing and Mining of Big Consumer Opinion Data

#### 2.1 Information Quality
##### 2.1.1 The Quality of Customer Online Reviews

The helpfulness voting ratio is regarded as the golden criterion in those publications to define the helpfulness of product reviews. 

Hong et al. focused on learning user preferences in three aspects, i.e., whether reviews meet their information needs, whether reviews is credible and whether reviews have the mainstreaming opinion. Then, a binary classification algorithm was modeled to predict the helpfulness of online reviews.

使用二分类来预测在线评论的有效性。后面还介绍了很多检验评论有效性的方法，此处略。

##### 2.1.2 Opinion Spam.

Due to various reasons, fake reviews are widely appearing in e-business websites and they are highly possible to mislead consumers and review analyzers. Accordingly, different methods have been developed to identify opinion spamming activity.


后面还介绍了很多有关识别垃圾评论的方法，此处略。

#### 2.2 Opinion Target Identification.

After high quality customer opinion data are obtained, the next focus is on the opinion target identification. In particular, only one specific product might be focused in his/her reviews by a novice customer. However, for some experienced customers, different products might be referred to a single piece of online review and different alternatives are often compared in terms of various aspects. Then, an interesting problem is how to identify the exact product that the customer refers to automatically. It hence motivates some scholars to explore the interesting problem about opinion target identification. 

#### 2.3 Sentiment Analysis.

Sentiment analysis or opinion mining on big consumer opinion data generally refers to a computational study of customer attitudes toward products on customer textual data. As presented in Fig. 1, the input of sentiment analysis module often contains customer opinions with a target product. Some critical tasks in sentiment analysis involve 
how to extract sentiment polarity,
how to identify different product aspects that customers care about, 
how to retrieve targeted products with representative opinions, etc. 
Also, in this section, cross-language opinion mining will be briefly reviewed.

##### 2.3.1 Sentiment Polarity.

The task of sentiment polarity extraction on online opinion textual data is to analyze whether a customer expresses a positive/negative/neutral opinion toward the target product or a particular feature of one product. In many studies about this task, sentiment words are often assumed to be adjectives or adverbs. Generally, these studies can be categorized into linguistic rules-based algorithms, conventional classification-based approaches, graph model-based approaches, deep learning-based approaches, etc.

在线评论文本数据的情绪极性提取是为了分析用户对产品表达的是怎样的评论（积极/消极/中性）

启发式规则（score words for analyzing the sentiment polarity）

One of the most straightforward approaches is to apply some heuristic rules to obtain the sentiment polarity.

多分类（SVM, Markov model-based approach, hidden Markov model-based approach, and a CRFs-based approach）

Note that the objective of sentiment polarity extraction can be also regarded a typical binary classification problem (positive versus negative) or trinary classification problem (positive, neutral, negative). 


##### 2.3.2 Feature Identification.

A highly correlated task with the analysis of sentiment polarity is feature identification from customer online opinions. 

In some early studies, heuristic rules were often employed to identify features from customer concerns. 

As aforementioned arguments, customer online opinions are one important type of textual data and some widely applied probabilistic models are often welcome for this particular task. 
JST,Reverse-JST,AUSM,MG-LDA,

Some researchers argued that words or phrases that refer to the same product features should be clustered together. Accordingly, an association rule method and a naive Bayesian method were utilized to classify words with similar meaning, which was represented as a product feature.

##### 2.3.3 Opinion Retrieval. 

The objective of opinion retrieve is to find documents with specific opinions. 


##### 2.3.4 Cross-Lingual Sentiment Classification. (跨语言情感分类)

borrow widely available corpus in English for cross-lingual sentiment analysis in other languages. 

借用广泛使用的英语语料库来进行其他语言的跨语言情感分析


#### 2.4 Summarization and Sampling.

Although product features as well as corresponding opinions can be identified, as shown in the fifth lane of Fig. 1, the large volume of consumer opinion data still makes it impossible to read and comprehend the entire set. Then, a good approach is to provide a brief summarization on customer opinions. Hence, the next valuable tasks for product designers are to make a summarization about general customer concerns or sample representative customer feedback from big opinion data.

产品设计师的下一个任务是从大量评论数据中对普遍的客户关注或代表性客户反馈做总结

##### 2.4.1 Hierarchical Organization of Consumer Reviews. 消费者评论的分层组织

##### 2.4.2 Review Summarization.


### 小结
