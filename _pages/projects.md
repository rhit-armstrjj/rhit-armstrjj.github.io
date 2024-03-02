---
author_profile: false
layout: archive
title: Project Portfolio
permalink: /projects/
collection: projects
---
{% assign projects = site.projects %}

<ul>
    {% for project in projects %}
    <li>
        <h2>
            <a href="{{ project.url }}">{{ project.title }}</a>
        </h2>
    </li>
    {% endfor %}
</ul>