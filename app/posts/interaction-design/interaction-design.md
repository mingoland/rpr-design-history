---
layout: collection
title: Interaction and visual design
description: Design decisions on interaction and visual design
pagination:
  data: collections.interaction-design
  reverse: true
  size: 50
permalink: "interaction-design/{% if pagination.pageNumber > 0 %}page/{{ pagination.pageNumber + 1 }}{% endif %}/"
override:tags:
  - post
eleventyComputed:
  eleventyNavigation:
    key: "{{ title }}"
    excerpt: "{{ description }}"
    parent: home
---