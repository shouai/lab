---
title: "团队"
date: 2024-05-19
type: landing
---

# 我们的团队

欢迎来到我们的团队页面！这里展示了团队成员的介绍和我们的工作成果。

## 教师团队
以下是我们的教师团队成员：

- block: collection
  content:
    title: 教师团队
    filters:
      folders:
        - team/teachers  # 设置教师文件夹路径
  design:
    view: article-grid
    fill_image: true
    columns: 3  # 以三列网格展示
    spacing: '2rem'  # 调整内容之间的间距

## 学生团队
以下是我们的学生团队成员：

- block: collection
  content:
    title: 学生团队
    filters:
      folders:
        - team/students  # 设置学生文件夹路径
  design:
    view: article-grid
    fill_image: true
    columns: 3  # 以三列网格展示
    spacing: '2rem'  # 调整内容之间的间距

## 毕业学生
以下是我们的毕业学生团队成员：

- block: collection
  content:
    title: 毕业学生
    filters:
      folders:
        - team/graduates  # 设置毕业生文件夹路径
  design:
    view: article-grid
    fill_image: false  # 不显示图片
    columns: 1  # 以单列展示
    spacing: '2rem'  # 调整内容之间的间距
