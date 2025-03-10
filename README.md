# R语言实战临床预测模型
谨以此书献给我不务正业的研究生生涯。

## 本书缘起

我在2019年接触到R语言和临床预测模型，彼时还是“简单的纯生信也能随便发SCI的上古时代”，当时的临床预测模型并不像现在这么火爆，连培训班也只有零星的几个，收费不过1000块左右。

然而随着大家愈加内卷，各种各样的培训班也越来越多，价格也是水涨船高，竟然都要3000+，甚至5000+了，真是离谱！但是内容并没有什么新意，无非就是列线图/ROC曲线/C-index/NRI/IDI/校准曲线/决策曲线等等。

回想自己的学习经历，这些东西无非就是各种R语言操作而已，本人的公众号也一直向大家免费提供这些教程。这部分内容已经积累了几十篇推文，是时候做个总结了，我把这些内容整理在一起，方便有需要的人学习。

本书github地址：https://github.com/ayueme/R_clinical_model

## 书籍简介

本书主要介绍R语言在临床预测模型中的应用，重实践，少理论，全书只有少量内容是理论，其余部分都是R语言实操。

临床预测模型和统计学以及机器学习交叉很多，本书虽然是R语言实现临床预测模型的入门书籍，但在阅读本书前，还需要你已经对**临床预测模型、统计学、机器学习**具有一定的了解。
本书不适合R语言零基础的人。

如果你是刚入门的小白，我首先推荐你了解下R语言的基础知识，比如R语言和R包安装（初学者可参考附录）、Rstudio的界面、R语言中数据类型（向量、矩阵、数据框、列表等）、R语言中的数据导入导出、R语言的基础数据操作等。

本书内容主要涉及**模型建立、模型评价、模型比较**3部分内容，其中模型建立和模型评价内容占比较多，模型比较部分主要是几个综合性R包的使用，简化多模型比较的流程。对于临床预测模型中常见的列线图、C-index、ROC曲线、校准曲线、决策曲线、临床影响曲线、NRI、IDI等内容，皆进行了详细的操作演示，同时提供多种实现方法。

对于一些比较火爆的机器学习方法，如**随机生存森林、生存支持向量机、deepsurv、Coxboost**等内容，本书并未进行介绍，公众号会逐步更新这部分内容（随机生存森林已完结），需要的朋友可关注公众号：医学和生信笔记。

限于本人水平等问题，难免会有一些错误，欢迎大家以各种方式批评指正，比如公众号留言、粉丝QQ群、github、个人微信等。

本书会不定期更新，内容和格式都会不断完善。

*更新日志*：

- 20231015：首次上传


本书实际上是我公众号历史推文的汇总，**书中涉及的所有数据都可以在相关历史推文中免费获取！**推文合集链接：[临床预测模型](https://mp.weixin.qq.com/mp/appmsgalbum?__biz=MzUzOTQzNzU0NA==&action=getalbum&album_id=2393825487539191816&scene=173&from_msgid=2247495829&from_itemidx=1&count=3&nolastread=1#wechat_redirect)

我也准备了一个PDF版合集，内容和网页版一致，只是打包了所有的数据，付费获取（10元），介意勿扰！**PDF版合集获取链接**：[R语言临床预测模型合集](https://mp.weixin.qq.com/s/81_hepLN2MZC360LrqT1AQ)

## 作者简介

- 阿越，外科医生，R语言爱好者，长期分享R语言和医学统计学、临床预测模型、生信数据挖掘、R语言机器学习等知识。
- 公众号：**医学和生信笔记**
- 知乎：[医学和生信笔记](https://www.zhihu.com/people/li-xiao-yue-65-90)
- CSDN：[医学和生信笔记](https://blog.csdn.net/Ayue0616)
- 哔哩哔哩：[阿越就是我](https://space.bilibili.com/42460432)
- Github：[ayueme](https://github.com/ayueme)
- Gitee：[ayue2019](https://gitee.com/ayue2019)
