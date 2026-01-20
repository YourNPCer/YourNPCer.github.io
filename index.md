---
layout: default
title: 首页
---

## 站在人这边 拒绝抽象病

这里是我思考和记录的地方。

## 📝 最新文章

<ul>
  {% for post in site.posts %}
    
      <span style="color:gray; font-size:0.8em;">{{ post.date | date: "%Y-%m-%d" }}span>
       
      {{ post.title }}
    
  {% endfor %}


---

[👉 访问我的 GitHub](https://github.com/YourNPCer)