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

{% assign labs = site.pages | where_exp:"page", "page.url contains '/Instructions/Labs'" %}
| Lab | Level | Duration |
| --- | --- | --- |
{% for activity in labs  %}| [{{ activity.lab.title }}{% if activity.lab.type %} - {{ activity.lab.type }}{% endif %}]({{ site.github.url }}{{ activity.url }}) | {{ activity.lab.level }} | {{ activity.lab.duration }} |
{% endfor %}
