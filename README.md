# Twitter 后端系统 - Python 项目实战

![license](https://img.shields.io/badge/%E4%B9%9D%E7%AB%A0%E7%AE%97%E6%B3%95-jiuzhangsuanfa-blue)

|:books: |:bulb: |:house: |:rocket: |:checkered_flag:|:email:|
| :--------: | :---------: | :------: | :------: | :------: | :------: |
| [介绍](#介绍) | [技术栈](#技术栈) | [信息流](#信息流) | [演示](#演示) | [ToDoList](#TodoList) | [联系我们](#联系我们) |

## 介绍
 这里写介绍
 
## 技术栈
| 技术                             | 官网                                                                                       |
|----------------------------------|--------------------------------------------------------------------------------------------|
|Django                            |[https://www.djangoproject.com/](https://www.djangoproject.com/)                            |
|Django REST framework             |[https://www.django-rest-framework.org/](https://www.django-rest-framework.org/)            |
|MySQL                             |[https://www.mysql.com/](https://www.mysql.com/)                                            |
|HBase                             |[https://hbase.apache.org/](https://hbase.apache.org/)                                      |
|Redis                             |[https://redis.io/](https://redis.io/)                                                      |
|Memcached                         |[http://memcached.org/](http://memcached.org/)                                              |
|RabbitMQ                          |[https://www.rabbitmq.com/](https://www.rabbitmq.com/)                                      |

## 信息流
在设计信息流系统时，一般有两种信息流模式：`拉(pull)模式` 和 `推(push)模式`，如果去设计一个如 Tweet 的社交网络服务系统：


`拉(pull)模式`：在 `拉(pull)模式`，下一个人发帖只在 Tweet 表单中产生一条新记录

`推(push)模式`：在 `推(push)模式`，下一个人发帖除了在 Tweet 表单中产生一条新纪录，还会产生 N 条 NewsFeed 记录，N 是粉丝的个数
