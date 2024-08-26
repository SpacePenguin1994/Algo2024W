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

Turing Award awardee [Knuth](https://en.wikipedia.org/wiki/Donald_Knuth) once said, "Computer Science is the study of algorithms". Even though the speed of computers is now so fast that we might even question whether Moore's Law still holds true, the significance of an efficient algorithm remains essential for us. 

Therefore, in this course, we aim to present various algorithms for numerous 'standard' algorithmic problems. We will illustrate both algorithm design techniques and the methods employed in algorithm analysis. By the end of the course, students will attain proficiency in applying fundamental algorithm design techniques and will become acquainted with the key theoretical instruments utilized in algorithm analysis. Moreover, since this course is designed for senior undergraduates, we will provide an introduction to notable subfields within algorithmic research, thereby offering potential directions for further study.

关于课程介绍的更多信息和课程要求请关注 [课程信息](syllabus.md)

## 课程基本信息

**主讲人:** [杨启哲](https://basics.sjtu.edu.cn/~yangqizhe/), qzyang(at)shnu.edu.cn

**课程时间地点:** &ensp;&nbsp;9:45 a.m.- 11:15 a.m. &emsp; 每周三(1-16周), 奉贤3教楼401
 <br/>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&nbsp;&ensp;&nbsp;13:00 p.m.- 14:30 p.m. &emsp;每周五(1-8周), 奉贤3教楼401


 更多信息可以关注 [课程安排](schedule.md).


## 课程反馈

我们建立了一个长期的课程反馈问卷:

- [《算法设计与分析》课程调查问卷](https://www.wjx.cn/vm/tU88Sco.aspx)

欢迎大家提出关于本课程的问题或建议。



## 课程通知

{% assign announcements = site.announcements | reverse %}
{% for announcement in announcements %}
{{ announcement }}
{% endfor %}

## 之前的课程资料

- [2023年秋季学期](https://www.algo2023w.spacepenguin.com.cn)