---
title: "团队"
date: 2024-05-19
type: landing

sections:
  - block: markdown
    content:
      title: 我们的团队
      text: 欢迎来到我们的团队页面！这里展示了团队成员的介绍和我们的工作成果。

  - block: collection
    content:
      title: 教师团队
      filters:
        folders:
          - team/teachers
    design:
      view: article-grid
      fill_image: true
      columns: 3
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
      columns: 3
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
