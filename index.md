---
layout: home
title: 主页
nav_exclude: true
seo:
  type: 课程
  name: 算法设计与分析
---

# {{ site.tagline }}
{: .mb-2 }
{{ site.description }}
{: .fs-6 .fw-300 }

<!-- {% if site.announcements %}
{{ site.announcements.last }}
[Announcements](announcements.md){: .btn .btn-outline .fs-3 }
{% endif %} -->

## 关于本课程

图灵奖获得者[高德纳(Knuth)](https://en.wikipedia.org/wiki/Donald_Knuth)曾说过：“计算机科学是研究算法的学科。” 尽管如今计算机的发展速度越来越快，但高效算法的重要性依然不可忽视。

因此，在本课程中，我们将为众多“标准”算法问题展示各种算法。我们将讲解算法设计技巧以及算法分析方法。课程结束后，学生将熟练掌握基本的算法设计技巧，并熟悉算法分析中使用的关键理论工具。此外，鉴于本课程为高年级本科生设计，我们还将介绍算法研究中的一些前沿分支领域，为进一步学习提供可能的方向。

关于课程介绍的更多信息和课程要求请关注 [课程信息](syllabus.md)

## 课程基本信息

**主讲人:** [杨启哲](https://basics.sjtu.edu.cn/~yangqizhe/), qzyang(at)shnu.edu.cn

**课程时间地点:** &ensp;&nbsp;9:45 a.m.- 11:15 a.m. &emsp; 每周三(1-16周), 奉贤3教楼401
 <br/>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&nbsp;&ensp;&nbsp;13:00 p.m.- 14:30 p.m. &emsp;每周五(1-8周), 奉贤3教楼401


 更多信息可以关注 [课程安排](schedule.md).


## 课程反馈

我们建立了一个长期的课程反馈问卷:

- [《算法设计与分析》课程调查问卷](https://www.wjx.cn/vm/YhxWixY.aspx# )

欢迎大家提出关于本课程的问题或建议。



## 课程通知

{% assign announcements = site.announcements | reverse %}
{% for announcement in announcements %}
{{ announcement }}
{% endfor %}

## 之前的课程资料

- [2023年秋季学期](https://www.algo2023w.spacepenguin.com.cn)