---
layout: test
title: Oh! My JK
top: トップページ！
---
# Welcome to my JK Home page!
jkによる誰かのbacklog的な何か
以下site変数の持つ情報  
{{ site.markdown }}
{{ site }}

以下ドロップス
{{ Drop }}

<ul>
{% for post in site.posts %}
  <li>
    <a href="{{ post.url }}">{{ post.date | date_to_long_string }} : {{ post.title }}</a>
  </li>
{% endfor %}
</ul>

<a href="/backlog_home">BACKLOG</a>
