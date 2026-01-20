---
layout: default
title: 首页
---

## 拒绝抽象病 站在人这边 🌿

这里是我思考和记录的地方。

## 📝 最新文章

{% for post in site.posts %}
* {{ post.date | date: "%Y-%m-%d" }} » [{{ post.title }}]({{ post.url }})
{% endfor %}

---

[👉 访问我的 GitHub](https://github.com/YourNPCer)