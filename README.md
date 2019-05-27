# pku_bigdata319_sentiment


## 数据源说明：

1. 出处：数据为从淘宝有关坚果的评论中爬取下来的短文本
2. 字段含义： 

|序号|商品号|文本内容|商品下该文本内容为出现次数|情感（1为正面，0为负面）|
|:--:|:--:|:--:|:--:|:--:|


  - 第一列为序号
  - 第二列为对应的商品号
  - 第三列为文本内容
  - 第四列该商品下该文本内容为出现次数
  - 第五列为情感（1为正面，0为负面）
  
  
3. 训练集要求：以前6000条为训练数据，之后的数据为测试数据
4. 输出：进行文本的情感分类，自行选择模型，算法，
5. 作业要求：最后要求提交代码（详细注释），准确率截图

## Setup

```
conda create --name pku_bigdata319_sentiment
conda activate pku_bigdata319_sentiment
conda deactivate
```

## 需求分析

1. 文本内容需要分词处理
2. 商品下文本内容出现次数，暗示是用`TF-IDF`  

## 参考资源

1. 停用词词库 https://github.com/wangye8899/stopwords
