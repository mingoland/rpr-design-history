---
layout: collection
title: Content design
description: Content design decisions on BEIS RPR
pagination:
  data: collections.content-design
  reverse: true
  size: 50
permalink: "content-design/{% if pagination.pageNumber > 0 %}page/{{ pagination.pageNumber + 1 }}{% endif %}/"
override:tags:
  - post
eleventyComputed:
  eleventyNavigation:
    key: "{{ title }}"
    excerpt: "{{ description }}"
    parent: home
    order: 2
---