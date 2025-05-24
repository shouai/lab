---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/学院网站简历及海洋技术硕导简历-柳彬.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: markdown
    content:
      title: '📚 研究领域'
      subtitle: ''
      text: |-
        主要研究领域人工智能海洋学、遥感图像智能信息提取、深度学习，具体而言，包括但不仅限于：
        (1) 基于深度学习的海洋遥感图像智能分析，应用于海岸带水淹监测与预警、潮间带环境监测以及船舶探测和识别。
        (2) 基于深度学习的渔场预报、渔业资源预测及渔汛预报。
        (3) 基于国产自主边缘计算芯片的人工智能模型移植、推理优化和迁移学习。
        
        有志于从事人工智能海洋学、遥感图像智能信息提取、深度学习等领域研究的同学，包括但不限于：攻读硕士学位、毕业设计、大学生创新项目等，可以通过邮箱bliu@shou.edu.cn先联系我。希望你主动、自我激励、喜欢钻研并且积极进取，我们一起向前进步。 😃
    design:
      columns: '1'

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
      title: 最近出版物
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation

  - block: collection
    id: news
    content:
      title: 最近的新闻
      subtitle: ''
      text: ''
      # Page type to display. E.g. post, talk, publication...
      page_type: post
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: date-title-summary
      # Reduce spacing
      spacing:
        padding: [0, 0, 0, 0]

---
