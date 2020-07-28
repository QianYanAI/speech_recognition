## 中文语音识别
##### 1. 环境
python                    3.6.10
tensorflow-gpu            1.9.0
numpy                     1.19.0
keras                     2.2.0

------

##### 2. 训练数据下载
- 清华大学中文语料库（thchs30）[下载地址](http://www.openslr.org/18/)

------

##### 3. 训练
- 配置conf目录下的conf.ini文件中的各项
- 在终端运行 ```python train.py``` 开始训练
- 在终端运行 ```python test.py``` 测试
- 也可以使用PyCharm打开

------


##### 4. 训练效果
第25次迭代，错误率：0.0032279575，损失：12.641949558258057

##### 5.测试结果
读入语音文件:  G:\\代码\\数据集\\语音数据集\\data_thchs30\\test\D11_783.wav
开始识别语音数据......
语音原始文本: tian1 kong1 yi4 xie1 yun2 mang2 zou3 yue4 liang5 xian4 jin4 yun2 wei2 shi2 yun2 he2 yan1 yang4 he2 mei2 shan1 yang4 kuai4 yao4 ran2 shao1 shi4 de5 
识别出来的文本:  tian1 kong1 yi4 xie1 yun2 mang2 zou3 yue4 liang5 xian4 jin4 yun2 wei2 shi2 yun2 he2 yan1 yang4 he2 mei2 shan1 yang4 kuai4 yao4 ran2 shao1 shi4 de5 

 
