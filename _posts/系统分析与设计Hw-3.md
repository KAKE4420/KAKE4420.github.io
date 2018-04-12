---
layout: post
title: 系统分析与设计Hw-3
date: 2018-4-12 12:00:10+00:00
categories: 日志
tags: 博客
---

## 系统分析与设计Hw-3
### 用例建模
1. 按照Asg_RH文档绘制用例图
![1](https://raw.githubusercontent.com/KAKE4420/KAKE4420.github.io/master/_img/1.png)
2. 选择去哪儿网，再次绘制用例图，其中红色用例为创新用例，橙色为外部系统
 ![2](https://raw.githubusercontent.com/KAKE4420/KAKE4420.github.io/master/_img/2.png)
3. 创新思路
- 尽可能的让用户定制自己的商品，比如在搜索和排序时提供更多的类型，让用户根据自己的需求去定制
- 简化操作，拒绝复杂的流程，比如在订单确认时，可以之间添加和修改订单的信息，而不是返回上一页面去修改
4. 开发需求backlog 

| ID  | Name     | Importance | Estimate | How to demo                               |
| --- | :------- | :--------: | :------: | :---------------------------------------: |
| 1   | 搜索酒店 | 15         | 12       | 输入相关信息可以显示搜索结果              |
| 2   | 选择酒店 | 9          | 10       | 在酒店列表里点击酒店可以进入预订页        |
| 3   | 预订酒店 | 9          | 10       | 预定时可以选择房间类型，以及入住/离开时间 |
| 4   | 确认订单 | 8          | 5        | 可以对订单的人员，酒店入住时间做修改      |
| 5   | 付款     | 10         | 5        | 支付后完成预订                            |
### 业务建模
1. 绘制找酒店的流程图
![3](https://raw.githubusercontent.com/KAKE4420/KAKE4420.github.io/master/_img/3.png)
2. 绘制ATM取款的流程图
![4](https://raw.githubusercontent.com/KAKE4420/KAKE4420.github.io/master/_img/4.png)
3. 淘宝退款流程
![5](https://raw.githubusercontent.com/KAKE4420/KAKE4420.github.io/master/_img/5.png)

### 用例书写
* Full
    >- 优点：有严格的书写格式规范，考虑全面
    >- 缺点：费时，书写起来很复杂
* Causal
    >- 优点：说明比brief丰富，容易完成
    >- 缺点：需要详细说明时无法使用
* Brief
    >- 优点：描述直观，可以直接的理解用例
    >- 缺点：缺乏细节，只适合早期开发