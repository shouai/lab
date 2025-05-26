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
          - team/teachers
    design:
      view: article-grid
      columns: 2

  - block: collection
    id: students
    content:
      title: 学生团队
      filters:
        folders:
          - team/students
    design:
      view: article-grid
      columns: 1

  - block: collection
    id: graduates
    content:
      title: 毕业学生
      filters:
        folders:
          - team/graduates
    design:
      view: article-grid
      columns: 1
---
