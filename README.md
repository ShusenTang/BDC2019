
<div align=center>
<img src="background.png" alt="background"/>
</div>

[2019中国高校计算机大赛——大数据挑战赛](https://www.kesci.com/home/competition/5cc51043f71088002c5b8840/content)

鸡你太美（初赛复赛均第三名）解决方案，包含全部代码、文档及答辩PPT

## 赛题描述：
搜索中一个重要的任务是根据query和title预测query下doc点击率，本次大赛参赛队伍需要根据**脱敏**后的数据预测指定doc的点击率，结果按照指定的评价指标使用在线评测数据进行评测和排名，得分最优者获胜。

### 任务分类：
* 短文本匹配
* 点击率预估

## 数据说明：

`train_data.sample`是官方给的训练样本示例，数据按列分割，分隔符为”,"，为不带表头的CSV数据格式。数据格式如下：

|列名|类型|示例|
|---|---|---|
|query_id|int|3|
|query|hash string，term空格分割|1 9 117|
|query_title_id|title在query下的唯一标识|2|
|title|hash string，term空格分割|3 9 120|
|label|int, 取值{0, 1}|0|

> **注意：提供的样本示例`train_data.sample`仅为帮助理解赛题以及调通代码，由于样本示例仅为两万行，因此构造的出来的特征意义不大（数据严重泄露）。**


## 其他方案
* [第1名-Progressing](https://www.kesci.com/home/project/5d9ef1fc037db3002d3f75a3)
* [第2名-蜗牛本牛](https://github.com/srtianxia/BDC2019_Rank2)
* [第4名-Fah](https://github.com/ZanyFun9/2019BDC_solution_4th)
* [第5名-拯救菜鸟](https://github.com/LiuYaKu/2019-rank5)
* [第9名-bestfitting](https://github.com/tinySean/bdc2019-rank9th)
* [第11名-lili](https://github.com/harrylyx/2019BigDataChallenge)
* [第12名-福建大三本](https://github.com/leadert/BDC2019-Rank12th-lgb-esim)
* [第15名-改革春风吹满地](https://github.com/P01son6415/MatchModels)

------------------

感兴趣就给个star吧:-D

**最后感谢两位队友@Han和@hcccccccc**
