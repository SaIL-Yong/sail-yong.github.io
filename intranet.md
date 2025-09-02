---
title: Intranet
permalink: /intranet/
---

### Upcoming lab meetings

On a rotating basis, each member of the lab speaks to share their work or paper they read.
When someone has an upcoming conference talks or poster presentations, they can practice in the lab meetings.

### Fall 2025
{% raw %}
| Date       | Research   | Journal |
|------------|--------|-------|
| Sep 11     | Ifti / Pragya  |   | 
| Sep 25     | Didarul / Nasir  | Emad  |
| Oct 9      | Emad / Ifti  | Nasir  |
| Oct 23     | Pragya / Nasir  | Didarul  |
| Nov 6      | Didarul  | Iftekhar  |
| Nov 13     | DFD talk practice (Ifti) / Emad | Pragya  |
| Dec 4      | Data management review  |   |
| Dec 11     | Winter research plan  |   |


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
