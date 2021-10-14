---
layout: page
title: About
description: Android程序员
keywords: Letgogo, Android
comments: true
menu: 关于
permalink: /about/
---

一个喜欢李小龙、科比和乔布斯的程序员，兵无常势，水无常形，意念一到，动作就到，

写代码的高一层境界就像打字时的盲打一样，足够的训练和积累让你形成动作记忆和认知记忆，从而达到比较快速而高效率解决问题的境界，

更高一层境界便是在第一层境界的基础上拥有慢思考和深度思考的能力，从而达到高效率解决庞大、复杂、长久性问题的境界

## 联系

<ul>
{% for website in site.data.social %}
<li>{{website.sitename }}：<a href="{{ website.url }}" target="_blank">@{{ website.name }}</a></li>
{% endfor %}
{% if site.url contains 'mazhuang.org' %}

{% endif %}
</ul>


## Skill Keywords

{% for skill in site.data.skills %}
### {{ skill.name }}
<div class="btn-inline">
{% for keyword in skill.keywords %}
<button class="btn btn-outline" type="button">{{ keyword }}</button>
{% endfor %}
</div>
{% endfor %}
