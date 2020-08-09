---
layout: archive
title: "Kubernetes"
permalink: /kubernetes/
author_profile: true
header:
     image: "/assets/images/kube_header.jpg"
---

Want to learn difficult concepts in a fun way? Check out the comics below...

<br>
<br>


<div class="grid__wrapper">
    {% for post in site.posts %}
        {% if post.categories contains 'kubernetes' %}
            {% include archive-single.html type="grid" %}
        {% endif %}
    {% endfor %}
</div>
