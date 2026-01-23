---
title: Intranet
permalink: /intranet/
---

### Upcoming lab meetings

On a rotating basis, each member of the lab speaks to share their work or paper they read.
When someone has an upcoming conference talks or poster presentations, they can practice in the lab meetings.

### Spring 2026
{% raw %}
| Date       | Research   | Journal |
|------------|--------|-------|
| Jan 30     | Pragya / Emad  |   | 
| Feb 13     | Didarul / Nasir  | Srujan  |
| Feb 18     | BPS talk practice (Emad)  | Pragya  |
| Feb 27     | Ifti / Srujan  | Didarul  |
| Mar 13     | APS talk practice (Pragya / Nasir / Didarul)  |   |
| Mar 27     | Emad / Didarul | Nasir  |
| Apr 10     | Ifti / Pragya  | Emad  |
| Apr 24     | Srujan / Nasir  | Ifti  |
| May 07     | Data management review  |   |


{% endraw %}
<hr>

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
