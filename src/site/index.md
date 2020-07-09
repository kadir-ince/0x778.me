---
title: Kadir Ince
subtitle:
layout: layouts/base.njk
---

<br> <b>

My name is Kadir Ince. <br> 0x788 is a hexadecimal number. Its decimal base equivalent is <a href="https://en.wikipedia.org/wiki/Alan_Turing" target="_blank">1912</a>.

## Last Posts

<br>
<ul class="listing">
{%- for page in collections.post | reverse -%}
  <li>
    <a href="{{ page.url }}">{{ page.data.title }}</a> -
    <time datetime="{{ page.date }}">{{ page.date | dateDisplay("LLLL d, y") }}</time>
  </li>
{%- endfor -%}
</ul>

<div class="nakedLink">

</div>
