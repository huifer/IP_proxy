IP代理池
===

[![](https://img.shields.io/badge/Powered%20by-@huifer-green.svg)](https://wt1187982580.github.io/about/)
[![](https://img.shields.io/badge/language-Python-green.svg)](https://github.com/wt1187982580/IP_proxy)
## 目录说明
- API     API接口
- config   配置
- db      数据库操作
- log     日志
- spider  爬虫目录
- test    测试
- util    工具
结构图
![结构图](pic/IP_proxy.png)
## 运行程序
```shell
cd API
python flask_spider_main
```
===
## url地址
首页    localhost:5000
插入数据库   http://localhost:5000/getip/type/1/page/2
查询数据库   http://localhost:5000/search

## 执行效果
首页
![首页](pic/index.png)
插入
![插入](pic/insert.png)
查询
![查询](pic/search.png)
数据表
![数据表](pic/数据库表.png)