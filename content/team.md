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


  - block: markdown
    content:
      title: 团队成员
      text: |
        ## 王五
        **毕业年份**: 2022  
        **职位**: 毕业后就职于自然资源部第三海洋研究所，主要从事遥感数据处理工作。  
        王五在实验室期间参与了多个科研项目，尤其是在 SAR 图像分类与变化检测方向积累了丰富经验。

        ## 李四
        **毕业年份**: 2022  
        **职位**: 毕业后进入某科技公司，从事人工智能相关工作。  
        李四曾获优秀研究生奖学金，并参与多个项目的研发工作。

        ## 张三
        **毕业年份**: 2022  
        **职位**: 毕业后进入高校从事教学工作。  
        张三专注于人工智能与机器学习领域，并致力于培养下一代AI人才。

    design:
      view: single-column  # 单列展示内容
      spacing:
        padding: ["2rem", "2rem", "2rem", "2rem"]
---
