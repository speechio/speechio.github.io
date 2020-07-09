---
layout: article
title: TIOBE 测试场景:直播 带货
permalink: /zhibo_daihuo
key: TIOBE_zhibo_daihuo
tags: TIOBE-Benchmark
lang: zh-Hans
author: SpeechIO
chart: true
---

# 场景素材来源
YouTube 李佳琪官方频道 & 薇娅官方频道

我们爬取了李佳琪和薇娅的日常带货直播录像，共计约 3.5 个小时

因为场景较复杂，标注过程中我们有一些处理原则：
* 当存在明显的多人同时说话，抢话时，该句丢弃。
* 当句子中存在标注员都完全听不懂的品牌，名字时，将句子丢弃。

# 样例

<iframe src="//player.bilibili.com/player.html?aid=78192213&bvid=BV1pJ411i7Zh&cid=133784196&page=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"> </iframe>

<iframe src="//player.bilibili.com/player.html?aid=540401849&bvid=BV1ei4y1t79m&cid=185006602&page=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"> </iframe>


# 场景特点
* 环境
  * 直播间
  * 直播间内聚集多人团队及嘉宾，有少量人员沟通、工作时产生的背景噪声。
* 拾音设备
  * 麦克风，距主播约一臂距离，拾音效果比近场差
* 说话人
  * 李佳琪及其助理 & 带货嘉宾
  * 薇娅及团队辅助人员 & 带货嘉宾
* 说话方式
  * 自然语言，语速极快
* 方言
  * 普通话
* 内容领域
  * 各种产品介绍，推荐语，闲聊

# 测试结果
请跳转至[TIOBE 滚动测试页面](/tiobe/timeline#场景直播-带货), 该页面包含所有历史及最新性能数据。