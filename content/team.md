---
title: '团队'
date: 2024-05-19
type: landing

design:
  # Section spacing
  spacing: '5rem'
  
sections:

  - block: collection
    id: teachers
    content:
      title: 教师团队
      subtitle: ''
      text: ''
      # Page type to display. E.g. post, talk, publication...
      page_type: teachers
      # Choose how many pages you would like to display (0 = all pages)
      count: 0
      # Choose how many pages you would like to offset by 该设置表示从第一个内容开始显示，不进行偏移。如果你想跳过前几篇内容，可以调整此值。
      offset: 0
    design:
      view: article-grid
      fill_image: true
      columns: 3
      spacing:
        padding: ["2rem", "2rem", "2rem", "2rem"]

  - block: collection
    id: students
    content:
      title: 学生团队
      filters:
        folders:
          - students
    design:
      view: article-grid
      fill_image: true
      columns: 4
      spacing:
        padding: ["2rem", "2rem", "2rem", "2rem"]


  - block: collection
    id: graduates
    content:
      title: 毕业学生
      filters:
        folders:
          - graduates
    design:
      view: article-grid
      fill_image: false
      columns: 1
      spacing:
        padding: ["2rem", "2rem", "2rem", "2rem"]
---
