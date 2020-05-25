---
layout: page
title: "Contact"
description: "Open to any questions"
image: "/assets/img/contact.jpg"
permalink: /contact/
---

If you have any questions, comments, or would just like to say hello in general, please don't hesitate to e-mail me at mario{dot}wt{dot}oh{at}gmail{dot}com. You can also contact me through these following social networks and I'll be sure to respond in a timely manner!

<ul class="social-links">
  {% if site.author.instagram %}
  <li>
     <a rel="me" href="//instagram.com/bluetofu.oh">
      <span class="svg-icon svg-baseline" aria-hidden="true">
        <svg><use xlink:href="/assets/icons/icons.min.svg#icon-instagram"></use></svg>
      </span><br><span class="label">Instagram</span>
    </a>
  </li>
  {% endif %}
  {% if site.author.github %}
  <li>
    <a rel="me" href="//github.com/{{ site.author.github }}">
      <span class="svg-icon svg-baseline" aria-hidden="true">
        <svg><use xlink:href="/assets/icons/icons.min.svg#icon-github"></use></svg>
      </span><br><span class="label">GitHub</span>
    </a>
  </li>
  {% endif %}
</ul>
