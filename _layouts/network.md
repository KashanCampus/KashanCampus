---
layout: default
title: پروفایل متخصص
---

<article itemscope itemtype="http://schema.org/BlogPosting">
  <h1>
    <a href="/network/">&uarr;</a>
    {{ page.name }}
  </h1>
  <b><span class="subtitle">{{ page.role }}</span></b>
  <br>
  <a href="https://github.com/{{ page.github }}/">
    <span class="subtitle">{{ page.email }}</span>
  </a>
  <br>
  <span class="subtitle">{{ page.country }}, {{ page.city }}</span>

  <table width="100%" border="0">
    <tr>
      <td valign="top">
        <a href="https://github.com/{{ page.github }}/">
          <img src="https://github.com/{{ page.github }}.png?size=80" width="60">
        </a>
      </td>
      <td>
        {{ content }}
      </td>
    </tr>
  </table>
</article>
