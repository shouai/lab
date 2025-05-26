---
title: '团队'
date: 2024-05-19
type: landing

design:
  # Section spacing
  spacing: '5rem'
  
sections:
  - block: markdown
    content:
      title: lab团队

  - block: collection
    id: teachers
    content:
      title: 教师团队
      filters:
        folders:
          - team
    design:
      view: article-grid
      columns: 3

  - block: collection
    id: students
    content:
      title: 学生团队
      filters:
        folders:
          - team
    design:
      view: article-grid
      columns: 4

  - block: collection
    id: graduates
    content:
      title: 毕业学生
      filters:
        folders:
          - team
    design:
      view: article-grid
      columns: 1
---
