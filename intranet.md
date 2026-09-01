---
title: Intranet
permalink: /intranet/
---

### Upcoming lab meetings

On a rotating basis, each member of the lab speaks to share their work. When someone has an upcoming conference talks or poster presentations, they can practice in the lab meetings.

#### Fall 2026
{% raw %}
| Date       | Speaker 1   | Speaker 2 |
|------------|--------|-------|
| 09/18      | Emad    | Srujan  | 
| 10/9       | Pragya  | Nasir   |
| 10/30      | Srujan  | Emad    |
| 11/20      | 3-minute pitch (all) |   |
| 12/4       | Nasir   | Pragya  |
{% endraw %}
<hr>

### Transport and Interfacial Phenomena (TIP) Coffee Hour
#### What is it?
UB has an amazing community of researchers whose work deals with transport and interfacial phenomena across a wide range of applications and scales. This is an opportunity to bring them together! Nothing formal: just a regularly scheduled (Tuesdays at 3pm) opportunity to meet others with shared interests, learn about ongoing research, spark new collaborations, and enjoy some coffee and donuts.
#### Where is it?
250 Bell Hall (MAE lecture room)
#### When is it?
Tuesdays, 3-4 pm. The first meeting will be on September 8, with subsequent meetings held (mostly) every three weeks. Mark your calendar!
#### Who is it?
Anyone interested in TIP! Undergraduate students, graduate students, postdocs and researchers, faculty are all welcome. 

The general format will feature two speakers, each sharing their ongoing research for ~15 minutes followed by open discussions.The tentative presentation schedule is found here:
{% raw %}
| Date       | Speaker 1   | Speaker 2 |
|------------|--------|-------|
| 9/8     | Nasir (Yong lab)  | Ali (Shin lab)  | 
| 9/29    | Mason (Cha lab)  | Reza (Snoeyink lab)  |
| 10/20   | Srujan (Yong lab)  | Sriram (Cha lab)  |
| 11/10   | Sampada (Snoeyink lab)  | Dang (Shin lab)  |
| 12/8    | Emad (Yong lab)  | Osama (Cha lab) |
{% endraw %}

### **For lab members**

<div class="content list">
  {% for post in site.posts %}
    {% if post.categories contains 'students' %}
    <div class="list-item">
      <p class="list-post-title">
        <a href="{{ site.baseurl }}{{ post.url }}">- {{ post.title }}</a>
      </p>
    </div>
    {% endif %}
  {% endfor %}
</div>
