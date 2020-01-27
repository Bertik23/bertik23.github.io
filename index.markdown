---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults
title: Bertik23 home page
layout: home
---
# 🚧!Under Construction!🚧
Welcome to my site. Here will be all my projects and, hopefully, a documentation for them.
## All my projects
{%for page in site.pages%}
	{%if page.main%}
[{{page.title}}]({{page.url}})
	{%endif%}
{%endfor%}
<a href="projects/python-encryptor/test" class="RRRed">HI!</a>