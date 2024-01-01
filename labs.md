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
