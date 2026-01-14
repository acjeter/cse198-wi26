---
layout: default
title: Weekly Schedule
nav_order: 3
permalink: /docs/schedule.html
---

# Weekly Schedule
{: .no_toc }

Below is the week-by-week schedule for CSE 198. Please note that exact topics may shift.

| Week | Phase / Topic | Notes | Due |
|:-----|:--------------|:------|:----|
{%- for item in site.data.schedule %}
| **{{ item.week }}** | {{ item.topic }}<br>_{{ item.dates }}_ | {{ item.notes }} | {{ item.due }} |
{%- endfor %}

{: .note-title }
> **Note**
>
> All deadlines are typically 11:59 PM unless otherwise stated.
