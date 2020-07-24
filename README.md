**仓库迁移** ，新地址：[https://github.com/Rodert/JavaPub](https://github.com/Rodert/JavaPub)



# usefulApi
Useful interface, long - term maintenance, suggestion message(有用的接口，长期维护，有建议留言)

# 声明

问题咨询与建议，欢迎加入

![image](https://github.com/wangshiyu777/usefulApi/blob/master/static/20200212154159.jpg)

# 目录

[TOC]

# 通用说明
调用ip：http://39.96.53.204:16001

样例：http://39.96.53.204:16001/ContentServer?fmt=json&url=http://world.people.com.cn/n1/2018/1220/c1002-30478654.html

# 更新日志
20200211 第一次更新，加入正文解析接口

# 版权声明
如有侵权，请联系删除。
所有数据，内容来源仅供用于学习，非授权用于商业用途，后果自负。

# API
## 一、新闻相关
#### 抽取新闻正文

a)接口说明：抽取新闻正文，定位新闻正文部分，智能抽取

b)接口地址：[HOST]/ContentServer?fmt=json&url=http://world.people.com.cn/n1/2018/1220/c1002-30478654.html

c)接口参数：fmt：返回类型，包括（json/html）,url：新闻详情页地址

d)返回值：包含（标题，时间，正文）


![](https://img-blog.csdnimg.cn/20200702221636781.jpg)
