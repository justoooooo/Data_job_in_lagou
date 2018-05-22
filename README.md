# 拉勾网数据相关岗位招聘信息分析
## 项目背景
    笔者原本一名电商行业的从业者，做得是运营岗位，在日常工作中数据分析也是必不可少的一部分。笔者在工作中慢慢发现先有的数据分析知识并不能满足想解决的数据分析问题，自己也比较向往做专业的数据分析师，于是开始了漫长的数据分析专业学习过程。
    这一年期间回顾了概率论、线性代数、统计学等理论基础，自学了工具爬虫和python爬虫，掌握了python数据分析相关的运用，入门了机器学习。自己也已经做了3个实践项目了，后面打算开始找工作了，所以决定通过数据分析相关岗位的招聘信息来分析一下岗位现状
## 项目简介
    笔者打算找互联网公司的数据分析工作，所以专注互联网招聘的拉勾网是个不错的选择。通过这些招聘信息我才能了解到现阶段还有哪些不足，来为自己后续的学习指明方向。
    本项目将会对获得的数据集进行一些探索和分析，解答笔者心中对这个岗位的一些疑问。
## 数据来源
    本项目采用了两份数据集进行分析。
    第一份来自于在天善学院参与数据分析课程时秦路老师爬取的2017年年中拉勾网全国数据相关岗位的招聘信息，分为职位表和公司表两张表。
    第二份来自笔者于2018年5月用chrome插件webscraper爬取的拉勾网杭州站数据分析相关岗位的招聘信息，包含职位和公司信息的一张表。
    本来笔者也有考虑爬boss直聘的招聘信息，因为boss直聘的移动版页面似乎可以加载出更多页的信息，但因boss对爬虫不太友好，请求间隔设置得长一点还是会跳出验证码，所以笔者放弃了，还是爬拉勾网吧。
## 分析目录
## 一.全国数据相关岗位分析
###     0.数据加载和清洗
###     1.单因素分析
        1.1 城市
        1.2 行业领域 
        1.3 工作类型
        1.4 岗位标签
        1.5 薪资
        1.6 学历
        1.7工作经验
###     2.多因素交叉分析
        2.1 地域和薪资
        2.2 岗位类别和薪资
        2.3 行业类别和薪资
        2.4 工作经验和薪资
        2.5 学历和薪资
        2.6 岗位名称和薪资
        2.7 岗位名称和学历
        2.8 工作经验和学历
        2.8 学历和工作经验和薪资
###     3.关联公司信息多因素交叉分析
        3.1 各公司招聘人数
        3.2 公司规模
        3.3 公司规模和薪资
        3.4 公司规模和学历
        3.5 公司规模和岗位名称和学历
        3.6 公司规模和岗位名称和薪资
        3.7 公司规模和学历和薪资
## 二.杭州近期招聘岗位分析
###     0.数据加载和清洗
###     1.多因素交叉分析
        1.1 岗位名称和薪资
        1.2 公司规模和学历
        1.3 公司规模和工作经验
        1.4 学历和薪资
###     2.岗位描述词云分析
        2.1 中文词云分析
        2.2 英文词云分析
###     3.技能和薪资       