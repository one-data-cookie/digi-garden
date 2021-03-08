---
layout: post
title: By Seasons
permalink: /seasons/
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
    {% assign seasons = site.notes | map: 'season' | join: ' '  | split: ' ' | uniq %}
    {% for season in seasons %}
        {% if season != "autumn" %}
        <h3 id="{{ season }}">{{ season | captalize }}</h3>
        {%- for note in site.notes -%}
            {%- if note.season == season -%}
                <li style="padding-bottom: 0.6em; list-style: none;"><a href="{{note.url}}">{{ note.title }}</a></li>
            {%- endif -%}
        {%- endfor -%}
        {%- endif -%}
    {%- endfor -%}
    <br/>
    <br/>
</main>
