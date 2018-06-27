---
layout: page
title: About
description: 搬砖创造世界
keywords: vonway
comments: true
menu: 关于
permalink: /about/
---

迷途小书童，搬砖小民工。

仰慕「搬砖的艺术」。

## 坚信

* 熟能生巧
* 努力改变人生

## 联系

* GitHub：[vonway](https://github.com/vonway)
* 博客：[{{ site.title }}]({{ site.url }})
* 知乎: [@冯可烦](https://www.zhihu.com/people/vonway)

## Skill Keywords

#### Software Engineer Keywords
<div class="btn-inline">
    {% for keyword in site.skill_software_keywords %}
    <button class="btn btn-outline" type="button">{{ keyword }}</button>
    {% endfor %}
</div>

#### Mobile Developer Keywords
<div class="btn-inline">
    {% for keyword in site.skill_mobile_app_keywords %}
    <button class="btn btn-outline" type="button">{{ keyword }}</button>
    {% endfor %}
</div>

#### Windows Developer Keywords
<div class="btn-inline">
    {% for keyword in site.skill_windows_keywords %}
    <button class="btn btn-outline" type="button">{{ keyword }}</button>
    {% endfor %}
</div>
