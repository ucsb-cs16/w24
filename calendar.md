---
layout: page
title: Calendar
nav_order: 3
description: Listing of course topics and due dates.
---

<style>
  iframe { width: 100%; height: 600px; }
</style>


# CMPSC 16, Winter 2024

# Office Hours and Course Calendar

* For office hours held in 2510, 3525, or 3526,  these refer to rooms in Phelps Hall.
* For online office hours, the zoom room link is on the Canvas site for the course

<iframe src="https://calendar.google.com/calendar/embed?height=600&wkst=1&bgcolor=%23ffffff&ctz=America%2FLos_Angeles&mode=WEEK&src=Y180MmFlNDVlNzg3NjE3M2MzYzUzYjc0YjY5OWM2YjE0MWVmMzMxNzBmM2M4YmE3ZjE0MzZhNmI5N2JiOWY1ZGE1QGdyb3VwLmNhbGVuZGFyLmdvb2dsZS5jb20&color=%233F51B5" style="border:solid 1px #777" width="800" height="600" frameborder="0" scrolling="no"></iframe>


Each week corresponds to one Chapter in the zyBook.

"Week 1" in zyBooks is effectively Chapter 1 and so on.

We have the following course activities that need to be completed in zyBooks on a weekly basis: 
* **PA**{: .label .label-orange }(Participation Activities), 
* **CA**{: .label .label-blue }(Challenge Activities), 
* **LA**{: .label .label-green }(Lab Activities including zyLabs and Gradescope assignments).

All due times in our class are at **2:00PM Pacific time**.


<!--[Jump to the current week]({{ site.url }}{{ site.baseurl }}/calendar#week-1){: .btn .btn-blue }-->
{% for module in site.modules %}
{{ module }}
{% endfor %}
