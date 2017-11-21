---
layout: default
---

# $ cat posts.txt
{:id="posts"}

<ul>
{% for post in site.categories.posts %}

<li><a href="{{ post.url }}" title="{{ post.description }}">{{ post.title }}</a> :: {{ post.description }}</li> 

{% endfor %}
</ul>

# $ cat articles.txt
{:id="articles"}

<ul>
{% for post in site.categories.articles %}

<li><a href="{{ post.url }}" title="{{ post.description }}">{{ post.title }}</a> :: {{ post.description }}</li> 

{% endfor %}

</ul>

# $ cat projects.txt
{:id="projects"}

<ul>
{% for project in site.categories.projects %}
<li><a href="{{ project.link }}">{{ project.title }}</a> - {{ project.description }}</li>
{% endfor %}
</ul>

# $ cat tools.txt
{:id="tools"}

<ul>
{% for tool in site.categories.tools %}
<li><a href="{{ tool.link }}">{{ tool.title }}</a> - {{ tool.description }}</li>
{% endfor %}
</ul>

# $ cat talks.txt
{:id="talks"}

<ul>
{% for talk in site.categories.talks %}
<li><a href="{{ talk.link }}" title="{{ talk.description }}">{{ talk.title }}</a> at {{ talk.where }}</li>
{% endfor %}
</ul>

# $ cat about.txt
{:id="about"}

My name is [Kumar Shivang](https://fb.com/km.shivang) and I am final year under-grad at IIT-Kanpur.
This [part of web](https://kshivang.github.io) is for my personal blogging cum project updates.

# $ cat contact.txt
{:id="contact"}

Find me at : [kshivang](https://github.com/kshivang).

# $ cat team.txt
{:id="team"}

<ul>
{% for member in site.categories.team reversed %}
<li id="{{ member.title }}">{{ member.title }}
<ul>
<li>{{ member.mail }}</li>
<li><a href="https://github.com/{{ member.github }}">https://github.com/{{ member.github }}</a></li>
<li><a href="{{ member.site }}">{{ member.site }}</a></li>
</ul>
</li>
{% endfor %}
</ul>





