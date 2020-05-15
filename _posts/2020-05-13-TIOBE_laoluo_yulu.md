---
layout: article
title: TIOBE 测试场景:老罗语录
permalink: /tiobe/laoluo_yulu
key: TIOBE_laoluo_yulu
tags: TIOBE-Benchmark
lang: zh-Hans
author: SpeechIO
chart: true
---

# 场景素材来源
Bilibili哔哩哔哩 老罗语录

我们搜罗并爬取了老罗在新东方讲课时期的录音，即[老罗语录]。从中选取了一部分相对清晰的音频，累计约 3.5 小时原始音频

# 样例

<iframe src="//player.bilibili.com/player.html?aid=74543521&bvid=BV1dE411q7tP&cid=127504429&page=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"> </iframe>

<iframe src="//player.bilibili.com/player.html?aid=73154894&bvid=BV15E411y7ZH&cid=125126431&page=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"> </iframe>

<iframe src="//player.bilibili.com/player.html?aid=70683221&bvid=BV1iE411f7L9&cid=122464624&page=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"> </iframe>

<iframe src="//player.bilibili.com/player.html?aid=79944130&bvid=BV1NJ411b7xy&cid=136820991&page=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"> </iframe>

# 场景特点
* 环境
  * 新东方教室（礼堂、大型讲堂）
  * 老师讲台上面讲课，学生下面听课，存在学生笑声、交头接耳等噪声
* 拾音设备
  * 学生自己的手机 & 录音笔
  * 收音距离一般较远，属于远场，音频质量较差
  * 教室较大，因此录音存在一定混响
* 说话人
  * 罗永浩
* 说话方式
  * 自然语言，有备课，语言流畅，语速较快
* 方言
  * 普通话
* 内容领域
  * 闲聊

该场景相当有挑战：自然语言 + 远场语音识别 + 单麦克风的手机和录音笔(均不属于专业远场拾音设备)

标注过程中，标注员遇到了相当比例听不清的句子，我们采取了丢句的策略。

# 测试结果
请跳转至[TIOBE 滚动测试页面](/tiobe/timeline#场景老罗语录), 该页面包含所有历史及最新性能数据。