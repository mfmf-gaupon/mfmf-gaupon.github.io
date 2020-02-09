---
layout: test
title: Oh! My JK
top: test
---
# Welcome to my JK Home page!
jkによる誰かのbacklog的な何か
以下site変数の持つ情報  
{{ site.markdown }}
{{ site }}

<ul>
{% for post in site.posts %}
  <li>
    <a href="{{ post.url }}">{{ post.date | date_to_long_string }} : {{ post.title }}</a>
  </li>
{% endfor %}
</ul>


以下page変数の持つ情報  
{{ page }}
