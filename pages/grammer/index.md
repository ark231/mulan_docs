---
title: 文法目次
---
{% include breadcrumbs.html %}

{% assign nav_home = site.data.navigation_recursive | where: "title", "ホーム" %}
{% assign nav_grammer = nav_home[0].subnav | where: "title", "文法" %}
{% assign nav_grammer = nav_grammer[0].subnav %}

{% include subnavigation_recursive.html nav=site.data.navigation_recursive place="ホーム::文法" subnav_only=true %}
