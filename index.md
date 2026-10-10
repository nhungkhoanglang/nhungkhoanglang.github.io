---
layout: default
title: Trang Chủ
---

# Chào mừng đến với Những Khoảng Lặng!

Đây là không gian ghi chép cá nhân, chia sẻ về công việc, trải nghiệm và cuộc sống thường nhật.

---

### 📝 Các bài viết mới nhất:

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }}) - *{{ post.date | date: "%d/%m/%Y" }}*
{% endfor %}

---
*Cập nhật thường xuyên.*
