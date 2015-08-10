---
layout: page
title: gLabels
tagline: Label Designer
description: glabels label designer program for GNU/Linux.
---
{% include JB/setup %}

gLabels is a GNU/Linux program for creating labels and business cards. It is
designed to work with various laser/ink-jet peel-off label and business card
sheets that you'll find at most office supply stores.
gLabels is free software and is distributed under the terms of the GNU General
Public License (GPL).

## News

{% for post in site.posts limit:2 %}
<div class="panel panel-default">
     <div class="panel-heading">
	  <a class="pull-right" href="{{ BASE_PATH }}{{ post.url }}"><span class="glyphicon glyphicon-link"></span></a>
	  <h2 class="panel-title">{{ post.title }}<br><small>{{ post.date | date_to_string }}</small></h2>
     </div>
     <div class="panel-body">
     	  {{ post.content }}
     </div>
</div>
{% endfor %}

[Older news...]({{ BASE_PATH }}/pages/archive.html)


## Screenshot
<img class="center-block" alt="glabels screenshot" src="{{ BASE_PATH }}/images/320-screenshot-main.png">
