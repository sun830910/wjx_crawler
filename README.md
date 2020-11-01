# 问卷星投票结果监控

## 目的

爬取问卷星投票结果，设定定时执行可达到实时票数监控的目的，后续可通过票数变化查看票数是否异常的场景。

## 爬取页面示例

![image](https://github.com/sun830910/Taipei_QA_Matching/blob/master/img/result1.jpeg)

## 需求

除安装需要的库之外，由于使用了selenium解析js页面源码，需要下载浏览器driver后配置至代码中。

Chrome Driver下载地址：https://sites.google.com/a/chromium.org/chromedriver/home

## 用法

运行main.py即可，会以当前时间作为档名记录各个候选人的当前票数。