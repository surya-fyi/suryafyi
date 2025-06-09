---
layout: home
title: Home
---

# Hey, I am Surya

### Software Engineer & Tech Enthusiast

I am passionate about software engineering, system design, and building scalable applications. This space is where I share my thoughts, experiences, and learnings from my journey in technology.

## Recent Blog Posts

{% for post in site.posts limit:5 %}
* {{ post.date | date: "%b %d, %Y" }} : [{{ post.title }}]({{ post.url | relative_url }})
{% endfor %}

[View all posts →](/blog)

## Newsletter

Join my newsletter to receive weekly updates on software engineering, system design, and technology insights.

[Subscribe on LinkedIn](https://linkedin.com/in/your-profile) | [Subscribe on Substack](https://your-substack.substack.com)

## Connect With Me

[GitHub](https://github.com/your-username) | [LinkedIn](https://linkedin.com/in/your-profile) | [Twitter](https://twitter.com/your-handle)

---

*Last updated: {{ site.time | date: "%B %Y" }}*
