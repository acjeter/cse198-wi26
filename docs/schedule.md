---
layout: default
title: Weekly Schedule
nav_order: 3
permalink: /docs/schedule.html
---

# Weekly Schedule
{: .no_toc }

Below is the week-by-week schedule for CSE 198. Please note that exact topics may shift.

| Week | Date | Phase / Topic | Slides | Notes | Due |
|:-----|:-----|:--------------|:-------|:------|:----|
{%- for item in site.data.schedule %}
| **{{ item.week }}** | {{ item.dates }} | {{ item.topic }} | {% if item.slides and item.slides != "" %}[Link]({{ item.slides }}){% else %}-{% endif %} | {{ item.notes }} | {{ item.due }} |
{%- endfor %}

{: .note-title }
> **Note**
>
> All deadlines are typically 11:59 PM unless otherwise stated.
