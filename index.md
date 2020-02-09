---
layout: test
title: Oh! My JK
---
# Welcome to my JK Home page!
jkによる誰かのbacklog的な何か

<ul>
{% for post in site.posts %}
  <li>
    <a href="{{ post.url }}">{{ post.date | date_to_long_string }} : {{ post.title }}</a>
  </li>
{% endfor %}
</ul>

以下site変数の持つ情報
{{ site }}

以下page変数の持つ情報
{{ page }}
