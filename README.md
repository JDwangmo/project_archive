# project_archive

## 列表：

### 1 综合类
- 1.1 [deepLearningBook](https://github.com/JDwangmo/deepLearningBook)
    - 学习笔记
- 1.2 [papers_archive](https://github.com/JDwangmo/papers_archive)
    - paper 归档
- 1.3 工具
    - [spark_test](https://github.com/JDwangmo/pyspark_test): pyspark脚本
    - [CnblogsSpider](https://github.com/JDwangmo/CnblogsSpider): 爬虫，数据爬取，Scrapy框架
    - [Crayon](https://github.com/torrvision/crayon): 可视化工具（Crayon is a framework that gives you access to the visualisation power of TensorBoard with any language. Currently it provides a Python and a Lua interface, however you can easily implement a wrapper around the provided RESTful API.）
    - [pytorch](https://github.com/pytorch/pytorch):Tensors and Dynamic neural networks in Python with strong GPU acceleration.
        - 安装方法： 
         - `> pip install http://download.pytorch.org/whl/cu75/torch-0.1.12.post2-cp27-none-linux_x86_64.whl`
         - `> pip install torchvision`
        - [官网](http://pytorch.org)
        - [torchsample](https://github.com/ncullen93/torchsample)：High-Level Training, Data Augmentation, and Utilities for Pytorch
        - [the-incredible-pytorch](https://github.com/ritchieng/the-incredible-pytorch):a curated list of tutorials, papers, projects, communities and more relating to PyTorch.
        - [practical-pytorch](https://github.com/spro/practical-pytorch):pytorch教程
    
### 2 文本类/自然语言处理(NLP)

#### 2.1 综合类

- 2.1.1 [awesome-nlp](https://github.com/keonkim/awesome-nlp)
    - 自然语言处理工具汇总
    
- 2.1.2 [LINDAT](https://lindat.mff.cuni.cz/en/)
    - 有不少语言学的处理工具，如语法树等，来自捷克共和国的语言学研究中心

- 2.1.3 [stopwords资源](https://github.com/JDwangmo/stop-words): 多种语言的stopwords汇总
    1. [Alir3z4/python-stop-words](https://github.com/Alir3z4/python-stop-words) ： a Python package containing stop words.
        - > For Mac/Unix with pip:  $ sudo pip install stop-words.
    2. [astuanax/stopwords](https://github.com/astuanax/stopwords): 同样是python版本的stopwords,在上面项目的基础之上
        - > For Mac/Unix with pip:  $ sudo pip install stopwords.

- 2.1.4 [SnowNLP](https://github.com/isnowfy/snownlp): Python library for processing Chinese text; Simplified Chinese Text Processing

- 2.1.5 [PyStanfordDependencies](https://github.com/dmcc/PyStanfordDependencies)： Python interface for converting Penn Treebank trees to Stanford Dependencies.
    - Stanford依赖树，需要先下载 模型文件 

#### 2.2 sentimentAnalysis
    
- 2.2.1 [nlp_util](https://github.com/JDwangmo/nlp_util)
    - 自然语言处理工具
    
- 2.2.2 [sentiment_classification](https://github.com/JDwangmo/sentiment_classification)
    - 多个英文公共数据集 上做 句子 的语义分类

- 2.2.3 [sentimentAnalysis](https://github.com/JDwangmo/sentimentAnalysis):
    - IALP 2016 Shared Task:Dimensional Sentiment Analysis for Chinese Words 
    - 中文 词 多维度语义分析
    
- 2.2.4 [weiboStanceDetection](https://github.com/JDwangmo/weiboStanceDetection):
    - NLPCC-ICCPOL 2016 Shared Task： Stance Detection in Chinese Microblogs
    - 中文微博立场分析，中文,aspect-based sentiment analysis
    
- 2.2.5 [chinese_sentiment_net](https://bitbucket.org/JDmowang/chinese_sentiment_net):
    - 收集了中文的词典、hownet、wordnet等
    - 构建一个中文语义网络/字典   
    - 2017.02.28 为了保护知识产权，只能从github上面删除，移到 bitbucket 的私有项目
     
- 2.2.6 [IALP2016_OOD_DA_Recognition](https://bitbucket.org/JDmowang/ialp2016_ood_da_recognition):
    - IALP 2016 paper 的实验部分
    - Dialogue Act Recognition for Chinese Out-of-Domain Utterances using Hybrid CNN-RF (oral paper)
    - 2017.02.28 为了保护知识产权，只能从github上面删除，移到 bitbucket 的私有项目
    
#### 2.3 Dialogue system 

- 2.3.1 [coprocessor](https://bitbucket.org/JDmowang/coprocessor):
    - c h 2 r 协处理项目，中文 ， 导购       
    - 已经停止更新
    - 已拆分多个项目
    - 2017.02.28 为了保护知识产权，只能从github上面删除，移到 bitbucket 的私有项目
    
- 2.3.2 [ch2r_dataset](https://bitbucket.org/JDmowang/ch2r_dataset):
    - from C h 2 R system's log
    - some dataset for SLU research 
    - 2017.02.28 为了保护知识产权，只能从github上面删除，移到 bitbucket 的私有项目

- 2.3.3 [ITPRSLU](https://bitbucket.org/JDmowang/itprslu):
    - ITPR SLU 主处理项目，中文，旅游    
    - 2017.02.28 为了保护知识产权，只能从github上面删除，移到 bitbucket 的私有项目

- 2.3.4 [ch2r_ID_detection](https://github.com/JDwangmo/ch2r_ID_detection):
    - C h 2 R system
    - C h 2 R in-domain's detection
    - 有效语义检测
    - ID 检测模块，即将输入对话系统的话语分为 ID 和 OOD 两类，
        - ID话语的进入[2.3.6 Ch2RSLU](http://git.oschina.net/mowang/Ch2RSLU)处理，
        - 而OOD话语进入[2.3.5 协处理](http://git.oschina.net/mowang/Ch2RCorprocess)
    
- 2.3.5 [Ch2RCorprocess](http://git.oschina.net/mowang/Ch2RCorprocess):
    - c h 2 r 系统SLU - 协处理
    - c h 2 r 协处理项目（服务器） ，中文 ， 导购 
    
- 2.3.6 [Ch2RSLU](http://git.oschina.net/mowang/Ch2RSLU)
    - c h 2 r 系统SLU - 主处理
    - 主处理器 ID（领域内话语）的 SLU（句子理解）     
    
- 2.3.7 [Ch2RDomainInfoManage](http://git.oschina.net/mowang/Ch2RDomainInfoManage)
    - Ch2R 领域信息 管理
    - 手机信息的爬取
    - 当前版本: version1.0
    
### 3 图像类/图像处理(Image Processing)

#### 3.1 对象识别（Object Recognition）
    
- 3.1.1 [image_util](https://github.com/JDwangmo/image_util)
    - 图像处理工具
    
- 3.1.2 [digitRecognition](https://bitbucket.org/JDmowang/digitrecognition):
    - 字符（34个，10数字+24字母）识别
    - 2017.03.07 为了保护知识产权，只能从github上面删除，移到 bitbucket 的私有项目
    
- 3.1.3 [digitRecognition_C](https://github.com/JDwangmo/digitRecognition_C):
    - 字符（34个，10数字+24字母）识别，CNN34分类器和CNN2分类器组合;项目 `3.1.2` 的C语言实现版本   
    
- 3.1.4 [dR_c](https://bitbucket.org/JDmowang/dr_c):
    - 字符（34个，10数字+24字母）识别，项目 `3.1.2` 的C语言实现版本;在项目`3.1.3`的基础
- 3.1.5 [faster_rcnn](https://github.com/JDwangmo/faster_rcnn): Faster RCNN

### 4 用户建模/客户画像

#### 4.1 客户画像
- 4.1.1 [customerPortrait](https://github.com/JDwangmo/customerPortrait)
