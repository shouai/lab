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
    content:
      title: 教师团队
      filters:
        folders:
          - team/teachers
    design:
      view: article-grid
      fill_image: true
      columns: 2
      spacing:
        padding: ["2rem", "2rem", "2rem", "2rem"]

  - block: collection
    content:
      title: 学生团队
      filters:
        folders:
          - team/students
    design:
      view: article-grid
      fill_image: true
      columns: 1
      spacing:
        padding: ["2rem", "2rem", "2rem", "2rem"]

  - block: collection
    content:
      title: 毕业学生
      filters:
        folders:
          - team/graduates
    design:
      view: article-grid
      fill_image: false
      columns: 1
      spacing:
        padding: ["2rem", "2rem", "2rem", "2rem"]
---
