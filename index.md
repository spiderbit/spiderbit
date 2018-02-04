---
title: Stefan Huchler's blog
layout: default
---
<div class="blurb">
	<h1>Hi there, I'm Stefan Huchler!</h1>
	<p>I'm a Software Programmer (Lisp)</p>
</div><!-- /.blurb -->

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
