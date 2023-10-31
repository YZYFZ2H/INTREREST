# INTREREST
HERE WE NEED TO NOTICE THAT

本实验是基于情感词典的情感分析模型
python==3.6
requirements：
jieba
os
xlrd
sqlite3
re
sys

运行main.py文件即可直接查看模型效果，需要注意更改调用文件的路径为本地路径

dic就是多个词典，corpus就是采用的数据集（中文酒店评论），还有用到的词性表

抱歉，排版有些不妥，请下载interest.main.zip后解压，解压后的文件夹请命名为Emotion_Manager，然后在Emotion_Manager新建一个文件夹Modules，并把Emotion_Manager中除了zip外的所有文件都放进Modules
![image](https://github.com/YZYFZ2H/INTREREST/assets/135771056/c2d6fc80-870f-4a40-80fe-bbf4b9f66c8e)

然后在Modules内新建文件夹res，并把dic和corpus放进来![image](https://github.com/YZYFZ2H/INTREREST/assets/135771056/b1dec77a-1493-496e-a7ad-54ceb7122085)

出错处理：
1、如果出现找不到Emotion_Manager错误，可以直接把几个py文件内的所有Emotion_Manager.都删掉，不要漏了“.”
2、如果没有安装什么包，可以直接pip install 或conda install即可

THANKS
