---
layout: page
title: GS Assignments
nav_order: 9
description: Lab Assignments
---

# GradeScope Programming Assignments

<!-- For a complete listing of GSA assignments, please refer to each chapter in the zyBook.

Some GSA assignments in the zyBook will reference particular
labs by number from the list below. -->


{% for lab in site.labs %}
* [{{lab.num}}]({{ lab.url | relative_url}})&mdash;{{lab.desc}}
{% endfor %}

# Formatting guide
Please make sure the code you submit follows the formatting guide below, and we **do** 
review your format as a part of our grading. You may lose points if you are not following 
this guide completely.

<a href="assets/pdfs/formatting-guide.pdf" target="_blank">Open in new tab</a>

<embed src="assets/pdfs/formatting-guide.pdf" width="800" height="500"> 