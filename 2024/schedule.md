---
layout: page
title: Schedule
nav_order: 1
description: Advanced Data Systems (COSI 167A)
banner_image: /assets/css/schedule.jpg
banner_heading: "Schedule"
banner_description: "Course Schedule and Important Dates"
---

{% for schedule in site.modules %}
{{ schedule }}
{% endfor %}