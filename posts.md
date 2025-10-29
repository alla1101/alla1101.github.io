---
layout: default
title: Posts
---

# Posts

This page contains my academic posts, thoughts, and updates. Check back regularly for new content!

<ul class="post-list">
{% for post in site.posts %}
  <li class="post-item">
    <h3><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h3>
    <div class="post-meta">
      <i class="fas fa-calendar"></i> {{ post.date | date: "%B %d, %Y" }}
      {% if post.categories.size > 0 %}
      | <i class="fas fa-tags"></i> 
      {% for category in post.categories %}
        <span class="category">{{ category }}</span>{% unless forloop.last %}, {% endunless %}
      {% endfor %}
      {% endif %}
    </div>
    {% if post.excerpt %}
    <div class="post-excerpt">
      {{ post.excerpt }}
    </div>
    {% endif %}
    <a href="{{ post.url | relative_url }}" class="button">Read More</a>
  </li>
{% else %}
  <li class="post-item">
    <p>No posts yet. Check back soon!</p>
  </li>
{% endfor %}
</ul>

---

## How to Add Posts

To add a new post, create a file in the `_posts` directory with the following naming convention:

`YYYY-MM-DD-post-title.md`

Example: `2024-01-15-my-first-post.md`

Each post should start with front matter like this:

```yaml
---
layout: post
title: Your Post Title
date: 2024-01-15
categories: [academic, research]
---
```

Then write your post content below the front matter.

