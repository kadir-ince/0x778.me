---
title: Kadir Ince
subtitle:
layout: layouts/base.njk
---

<br> <b>

This is my blog page. My name is Kadir Ince. <br> 0x788 is a hexadecimal number. Its decimal base equivalent is [1912](https://en.wikipedia.org/wiki/Alan_Turing).

## Last Posts

<br>
<ul class="listing">
{%- for page in collections.post -%}
  <li>
    <a href="{{ page.url }}">{{ page.data.title }}</a> -
    <time datetime="{{ page.date }}">{{ page.date | dateDisplay("LLLL d, y") }}</time>
  </li>
{%- endfor -%}
</ul>

<div class="nakedLink">

[![Netlify Status](https://api.netlify.com/api/v1/badges/056b4a67-70e6-4af4-9be5-dee151b8e906/deploy-status)](https://app.netlify.com/sites/eleventyone/deploys)

</div>
