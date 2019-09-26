# 《实战深度学习算法：基于Python和Numpy实现》
### 配套的示例源码与数据下载说明。

不借助**深度学习框架**，零起点实现神经网络的重要算法。

正确使用模型和各种深度学习框架，离不开对原理的了解，如果对整体原理了然于胸，在应用深度学习框架的时候，可以避免陷入“盲人摸象”的窘境，看清全貌，直达本质，解决工程实践中遇到的问题。

### 内容组织

1. 提出问题。

2. 以问题为动机引出模型。

3. 介绍模型原理、必要推导和实例。

4. 实现模型算法。

5. 解决问题与验证。

   

### 各章目标问题和数据集



| 章   | 目标问题            | 模型、算法                                                   | 数据集                                                       |
| ---- | ------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| 1    | 空间中的二分类      | 感知机MLP、SGD                                               | 源码生成目标数据集，无需下载                                 |
| 2    | 多分类图像识别      | 全连接神经网络FCN、Softmax方法、信息熵与交叉熵、反向传播推导 | [MNIST手写数字识别](http://yann.lecun.com/exdb/mnist),1D方式载入 |
| 3    | 图像识别（acc>90%） | 深层全连接神经网络DNN、隐藏层、激活函数、过拟合与正则化、DNN的反向传播推导 | 同上、1D方式载入                                             |
| 4    | 图像识别            | 卷积神经网络CNN、卷积与互相关、边缘填充、最大池化与平均池化、CNN反向传播推导 | 同上、3D方式载入                                             |
| 5    | 图象识别            | CNN的提速与优化、向量化、Momentum、NAG、Adagrad、RMSprop、AdaDelta、Adam算法及实现 | 同上、3D方式载入                                             |
| 6    | 图象识别            | 批量规范化 Batch Norm动机、作用、训练、推理、反向传播推导    | 同上、3D方式载入                                             |
| 7    | 序列分析            | 循环神经网络RNN前向计算、反向传播推导                        | 源码生成目标数据集，无需下载                                 |
| 8    | 指数分析            | 长短时记忆网络LSTM前向计算、反向传播推导、梯度裁剪           | 选择1，原始数据，需要自行预处理：./data/沪深300历史数据.csv ；<br>选择2，预处理后数据，可直接用于训练和验证：./data/hs300_data_seq_nodate.csv |
| 9    | 情感分析            | 双向门控循环单元BiGRU前向计算、反向传播推导、Dropout正则化   | 选择1，原始数据，需自行预处理：[IMDB原始数据](http://ai.stanford.edu/~amaas/data/sentiment)、[nltk停用词表](http://www.nltk.org)、[50维40万英文词嵌入矩阵](https://nlp.stanford.edu/projects/glove)。<br>选择2，预处理后的词向量数据（一半数据量），可直接用于训练和验证。https://pan.baidu.com/s/1VZaUCceA6oEmkDaUB9oFJw 提取码 9xdu |

### 勘误

./勘误.pdf	



### 欢迎交流

欢迎同行交流[知乎专栏](<https://www.zhihu.com/people/xu-jerry-82/posts>) ，可从公众号 **JerryX007Srv** 获得更新提醒。

![wechatSrv](https://ws1.sinaimg.cn/large/840c5815ly1ft85ikph1xj2076076jrv.jpg '获得更新')

