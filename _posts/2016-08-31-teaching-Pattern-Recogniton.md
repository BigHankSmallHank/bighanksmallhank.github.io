---
layout: post
title: "《模式识别》--研究生课程"
date: 2016-08-30
excerpt: "模式识别"
teaching: true
published: true
tags: [teaching post, pattern recognition]
---


### 简介 ###

这是从2016年秋季学期开始的一门研究生专业选修课。主要以“PPT讲解+实际数据操作+小组讨论”形式来完成学习。最终提交一篇课程论文，作为考核材料。

2016年秋季只有我的两个研究生选修。

### 目标 ###

多数研究生没有接触过模式识别，因此讲解内容偏重于基本概念原理和基本方法，主要讲授模式识别框架，基于距离测度的模式分类，基于统计决策的模式分类，基于判别模式的模式分类，非监督分类；练习数据将采自实际模式应用中的现实数据，要求最终方法和程序满足实际需求；小组讨论将以学生讲解某一专题或者其所做数据项目为主；课程PPT内容采用英文，主要目的是顺便熟悉相关的专业词汇，以便于进一步搜索与阅读相关的英文资料，但讲解采用中文。

### 主要内容（不断更新中） ### 
1. Introduction       [PPT](http://bighanksmallhank.github.io/mydata/Chapter1 Introduction.ppt)
2. Distance measures for pattern classification_partI   [PPT](http://bighanksmallhank.github.io/mydata/Chapter2 Distance measures for pattern classification_part I.ppt)
3. Distance measures for pattern classification_partII  [PPT](http://bighanksmallhank.github.io/mydata/Chapter2 Distance measures for pattern classfification_part II.ppt)
4. Probability measures for pattern classification_partI  [PPT](http://bighanksmallhank.github.io/mydata/Chapter3 Probability measures for pattern classification_part I.ppt)
5. Probability measures for pattern classification_partII  [PPT](http://bighanksmallhank.github.io/mydata/Chapter3 Probability measures for pattern classification_part II.ppt)
6. Estimation and Learning_partI   [PPT](http://bighanksmallhank.github.io/mydata/Chapter4 Estimation and Learning_part I.ppt)
7. Estimation and Learning_partII  [ppt](http://bighanksmallhank.github.io/mydata/Chapter4 Estimation and Learning_part II.ppt)
8. Discrimination function for pattern classification   [PPT](http://bighanksmallhank.github.io/mydata/Chapter5 Discrimination funciton for pattern classification.ppt)
9. PCA  [ppt](http://bighanksmallhank.github.io/mydata/Chapter6 Feature extraction_PCA.ppt)
10. Logistic Regression [ppt](http://bighanksmallhank.github.io/mydata/Chapter7 Logistic Regression.ppt)
11. to be continued ....


digital number image set:   [dataset](http://bighanksmallhank.github.io/mydata/digital_image_set.zip)
课程论文模板 [模板](http://bighanksmallhank.github.io/mydata/template1.doc)

### 上课时间与地点 ###
花溪校区大数据与计算机科学学院6402, 每周三下午2:00-4：00

### 其他上课前注意事项 ###
1. 携带笔记本电脑
2. 下载课程ppt和数据集(QQ传给你们)预习
3. 先做好数据集中图片的预处理，即（1）通过重采样将所有样本图片变为相同的尺寸大小。（2）统一为灰度图片。(3) 课前演示上次课所讲分类器的训练结果
4. 课前提交书面分类结果与分析（包括，3个基本分类器（ED分类器，MICD分类器，高斯最大后验分类器）间的性能比较；数字图像大小归一化操作对性能的影响；图像归一化大小数值对性能的影响；）请使用交叉验证指标进行分析。