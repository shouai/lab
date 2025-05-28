---
title: 论文
type: landing

sections:
  - block: collection
    id: papers
    content:
      title: 精选出版物
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: article-grid
      columns: 2  #将内容分为两列

  - block: collection
    content:
      title: 全部论文
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
---
