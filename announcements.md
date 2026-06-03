---
layout: page
title: Announcements
nav_exclude: true
description: A feed containing all of the class announcements.
---

{: .warning }
⚠️ The content on this site is archived and retained exclusively for reference. Updates will be made when the course if offered in the future.

# Announcements

{% assign announcements = site.announcements | reverse %}
{% for announcement in announcements %}
{{ announcement }}
{% endfor %}
