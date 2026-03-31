---
title: Online Hosted Instructions
permalink: index.html
layout: home
---

# Content Directory

Hyperlinks to each of the lab exercises are listed below.

> **Note**: To complete these exercises, you will need a [Microsoft 365 subscription](https://www.microsoft.com/microsoft-365) with access to Microsoft 365 Copilot.

This content supports the [MS-4004: Empower your workforce with Copilot for Microsoft 365 Use Cases](https://learn.microsoft.com/training/courses/ms-4004) course on Microsoft Learn.

## Labs

{% assign labs = site.pages | where_exp:"page", "page.url contains '/Instructions/Labs' and page.lab" | sort: "url" -%}
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
