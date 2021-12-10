---
layout: collection
title: Service design
description: Service design decisions on BEIS RPR
pagination:
  data: collections.service-design
  reverse: true
  size: 50
permalink: "service-design/{% if pagination.pageNumber > 0 %}page/{{ pagination.pageNumber + 1 }}{% endif %}/"
override:tags:
  - post
eleventyComputed:
  eleventyNavigation:
    key: "{{ title }}"
    excerpt: "{{ description }}"
    parent: home
    order: 3
---