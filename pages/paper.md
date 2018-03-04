---
layout: page
title: Paper
description: Lab papers
keywords: Paper, Yuyang Wang
comments: true
menu: Paper
permalink: /paper/
---



<p class="repo-list-description">
	These are the articles in our CS lab. If any of the following papers can help your learning, I hope you can cite it, thanks.
</p>

--  Yuyang Wang



## Popular papers


<ol class="repo-list">
	{% for paper in site.data.papers %}
    	<li class="repo-list-item">
	        <h3 class="repo-list-name">
	          <a >{{ paper.name }}</a>
	        </h3>
	        <p class="repo-list-description">
	            {{ paper.reference }}
	        </p>
	    </li>
    {% endfor %}
</ol>

