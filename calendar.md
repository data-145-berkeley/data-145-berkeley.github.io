---
layout: page 
title: Weekly Calendar
description: Lecture, Discussion and OH schedules
nav_order: 2
---

{: .warning }
⚠️ The content on this site is archived and retained exclusively for reference. Updates will be made when the course if offered in the future.

# Weekly Calendar

{% for calendar in site.calendars %}
  {{ calendar }}
{% endfor %}
