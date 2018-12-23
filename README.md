# 中文谣言数据

该数据为从新浪微博不实信息举报平台抓取的中文谣言数据，分为两个部分。其中当前目录下的数据集仅包含谣言原微博，不包含转发/评论信息；而CED_Dataset中是包含转发/评论信息的中文谣言数据集。

## 数据集介绍

第一部分数据集（./rumors_v170613.json）共包含从2009年9月4日至2017年6月12日的31669条谣言。文件中，每一行为一条json格式的谣言数据，字段释义如下：

* **rumorCode**: 该条谣言的唯一编码，可以通过该编码直接访问该谣言举报页面。
* **title**: 该条谣言被举报的标题内容
* **informerName**: 举报者微博名称
* **informerUrl**: 举报者微博链接
* **rumormongerName**: 发布谣言者的微博名称
* **rumormongerUr**: 发布谣言者的微博链接
* **rumorText**: 谣言内容
* **visitTimes**: 该谣言被访问次数
* **result**: 该谣言审查结果
* **publishTime**: 该谣言被举报时间

第二部分数据集（CED_Dataset）的介绍在其目录下。

## 引用

如果您使用该数据集，请引用以下论文：

* 中文：

```
	@article{liu2015rumors,
	  title={中文社交媒体谣言统计语义分析},
	  author={刘知远 and 张乐 and 涂存超 and 孙茂松},
	  journal={中国科学: 信息科学},
	  volume={12},
	  pages={1536--1546},
	  year={2015}
	}
```

* English：

```
	@article{liu2015rumors,
	  title={Statistical and semantic analysis of rumors in Chinese social media},
	  author={Liu, Zhiyuan and Zhang, Le and Tu, Cunchao and Sun, Maosong},
	  journal={Scientia Sinica Informationis},
	  volume={45},
	  number={12},
	  pages={1536},
	  year={2015}
	}
```
