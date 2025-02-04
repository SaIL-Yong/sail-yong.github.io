---
title: Intranet
permalink: /intranet/
---

### Upcoming lab meetings

On a rotating basis, each member of the lab speaks to share their work or paper they read.
When someone has an upcoming conference talks or poster presentations, they can practice in the lab meetings.

### Spring 2025
{% raw %}
| Date       | Research   | Journal |
|------------|--------|-------|
| Feb 5      | Iftekhar / Nasir  | Emad  | 
| Feb 12     | BPS poster  | Nasir   |
| Feb 26     | Iftekhar / Emad  | Didarul  |
| Mar 12     | APS talk/poster  |   |
| Mar 26     | Emad / Didarul  | Iftekhar  |
| Apr 9      | Nasir / Iftekhar  | Didarul  |
| Apr 23     | Didarul  | Iftekhar / Nasir   |
| May 7      | Data management review  |   |
| May 21     | Summer research planning  |    |

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
