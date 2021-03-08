---
layout: post
title: By Categories
permalink: /categories/
content-type: eg
---

<style>
.category-content a {
    text-decoration: none;
    color: #4183c4;
}

.category-content a:hover {
    text-decoration: underline;
    color: #4183c4;
}
</style>

<main>
    {% assign categories = site.notes | map: 'category' | join: ' '  | split: ' ' | uniq %}
    {% for category in categories %}
        <h3 id="{{ category }}">{{ category | captalize }}</h3>
        {%- for note in site.notes -%}
            {%- if note.category == category -%}
                <li style="padding-bottom: 0.6em; list-style: none;"><a href="{{note.url}}">{{ note.title }}</a></li>
            {%- endif -%}
        {%- endfor -%}
    {%- endfor -%}
    <br/>
    <br/>
</main>
