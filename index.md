---
layout: default
title: Welcome to My Website
---

# Hello！👋

這是我的個人網站。我會在這裡分享：
- 📌 學習記錄
- 📚 作業筆記

👉 [About](about)

---

## 📝 Posts
{% for post in site.posts %}
- 📅 **{{ post.date | date: "%Y-%m-%d" }}** - [{{ post.title }}]({{ post.url }})
{% endfor %}
