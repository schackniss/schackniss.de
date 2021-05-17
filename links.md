---
layout: page
title: Links
permalink: /links/
---
This page is dedicated to awesome links I found on the internet. It is kind of like a reading list.

Press `Ctrl` + `F` to search for a specific link.

<ul class="post-list">
    {%- for link in site.data.links -%}
    <li>
    <h3>
        <a class="post-link" href="{{ link.url }}">
        &#x1F517 {{ link.title | escape }}
        </a>
    </h3>
    {{ link.description }}
    </li>
    {%- endfor -%}
</ul>
