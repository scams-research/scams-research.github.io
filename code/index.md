---
layout: default
title: Code
---

The development of scientific software is a necessary part of research in the {{ site.title }} group. 
In addition to our code enabling cutting edge science, we strive towards the best software engineering practices.
Below, we list some software projects that we participate in. 
Other packages, and core repositories to support publications can be found on [our GitHub page](https://github.com/scams-research).

<body>
  <ul>
    {% for package in site.data.code %}
      <li>
        <code>{{ package.name }}</code><small> &mdash; <a href="{{ package.github }}">Repo</a> | <a href="{{ package.docs }}">Docs</a>{% if package.doi.size > 0 %} | <a href="https://doi.org/{{ package.doi }}">Paper</a>{% endif %}</small>
      </li>
    {% endfor %}
  </ul>
</body>

