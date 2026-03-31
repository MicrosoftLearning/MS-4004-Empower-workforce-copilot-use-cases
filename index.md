---
title: Online Hosted Instructions
permalink: index.html
layout: home
---

This page lists lab exercises associated with the Microsoft skilling course [MS-4004: Empower your workforce with Microsoft 365 Copilot Use Cases](https://learn.microsoft.com/en-us/training/courses/ms-4004) on [Microsoft Learn](https://learn.microsoft.com).

<hr>

## Labs

{% assign labs = site.pages | where_exp:"page", "page.url contains '/Instructions/Labs'" | where_exp:"page", "page.lab.title" | sort: "url" -%}
{% assign current_module = "" -%}
{% for activity in labs -%}
{% assign relative_url = activity.url | remove: "/Instructions/Labs/" -%}
{% assign module_folder = relative_url | split: "/" | first -%}
{% if module_folder != current_module -%}
{% assign current_module = module_folder -%}
{% assign module_num = module_folder | slice: 0, 3 -%}
{% assign module_desc = module_folder | slice: 4, 200 | replace: "-", " " | capitalize -%}
{% assign total_duration = 0 -%}
{% for p in labs -%}
{% assign p_rel = p.url | remove: "/Instructions/Labs/" -%}
{% assign p_mod = p_rel | split: "/" | first -%}
{% if p_mod == module_folder -%}
{% assign d = p.lab.duration | split: " " | first | plus: 0 -%}
{% assign total_duration = total_duration | plus: d -%}
{% endif -%}
{% endfor %}

### {{ module_num }}: {{ module_desc }} ({{ total_duration }} min)

| Lab | Level | Duration |
| --- | --- | --- |
{% endif -%}
| [{{ activity.lab.title }}{% if activity.lab.type %} - {{ activity.lab.type }}{% endif %}]({{ site.github.url }}{{ activity.url }}) | {{ activity.lab.level }} | {{ activity.lab.duration }} |
{% endfor %}
