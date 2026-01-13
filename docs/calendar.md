---
layout: default
title: Calendar & Events
nav_order: 4
permalink: /docs/calendar.html
---

# Calendar & Events
{: .no_toc }

## Table of Contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Key Deadlines

Important deliverables throughout the quarter.

| Deliverable | Deadline | Notes |
|:------------|:---------|:------|
{% for d in site.data.deadlines %}
| **{{ d.deliverable }}** | {{ d.deadline }} | {{ d.notes }} |
{% endfor %}

---

## Outreach Events

Upcoming outreach opportunities. **RSVP on the HKN Portal is required.**

| Event | Date / Time | Location | Points | RSVP |
|:------|:------------|:---------|:-------|:-----|
{% for e in site.data.events %}
| **{{ e.name }}** | {{ e.date }}<br>{{ e.time }} | {{ e.location }} | {{ e.points }} | [Link]({{ e.link }}) |
{% endfor %}

> [!TIP]
> Visit the [HKN Outreach Portal](https://hknhub.ucsd.edu/) for the most up-to-date list of events and real-time availability.
