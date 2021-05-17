---
layout: page
title: Links
permalink: /links/
---

## This page is dedicated to awesome links I found on the internet. It is kind of like a reading list.

### Press `Ctrl` + `F` to search for a specific link.

[The Anatomy of an Amazon 6-pager](https://writingcooperative.com/the-anatomy-of-an-amazon-6-pager-fc79f31a41c9)

<ul class="post-list">
    {%- for link in site.data.links -%}
    <li>
    <h3>
        <a class="post-link" href="{{ link.url }}">
        {{ link.title | escape }}
        </a>
    </h3>
    {{ link.description }}
    </li>
    {%- endfor -%}
</ul>
