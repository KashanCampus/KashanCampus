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
  <br />
  <a href="tel:{{ page.mobile }}/">
    <span class="subtitle">{{ page.mobile }}</span>
  </a>
  <br />
  <span class="subtitle">{{ page.country }}, {{ page.city }}</span>

  <p class="subtitle">{{ page.languages }}</p>

  <table width="100%" border="0">
    <tr>
      <td valign="top">
        <a href="https://github.com/{{ page.github }}/">
          <img src="https://github.com/{{ page.github }}.png?size=80" width="80">
        </a>
      </td>
      <td>
        {{ content }}
      </td>
    </tr>
  </table>
</article>
