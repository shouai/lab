---
title: '团队'
date: 2024-05-19
type: landing

design:
  spacing: '5rem'

sections:
  - block: markdown
    content:
      title: 教师团队
      text: |
        ## 王五
        ![王五的照片](/static/images/ww.png)
        **毕业年份**: 2022  
        **职位**: 毕业后就职于自然资源部第三海洋研究所，主要从事遥感数据处理工作。  
        王五在实验室期间参与了多个科研项目，尤其是在 SAR 图像分类与变化检测方向积累了丰富经验。

        ## 李四
        ![李四的照片](/static/images/ww.png)
        **毕业年份**: 2022  
        **职位**: 毕业后进入某科技公司，从事人工智能相关工作。  
        李四曾获优秀研究生奖学金，并参与多个项目的研发工作。

        ## 张三
        ![张三的照片](/static/images/ww.png)
        **毕业年份**: 2022  
        **职位**: 毕业后进入高校从事教学工作。  
        张三专注于人工智能与机器学习领域，并致力于培养下一代AI人才。

    design:
      view: article-grid
      columns: 3
      spacing:
        padding: ["2rem", "2rem", "2rem", "2rem"]
      custom_css: |
        .markdown h2 {
          font-size: 2rem; /* Larger font for titles */
          font-weight: bold;
        }
        .markdown p {
          font-size: 1rem; /* Smaller font for content */
        }
        /* 图片自适应 */
        .markdown img {
          width: 100%; /* 图片宽度自适应容器宽度 */
          height: auto; /* 保持图片比例 */
          max-width: 300px; /* 限制最大宽度，以适应屏幕 */
          margin-bottom: 1rem; /* 图片下方间距 */
        }

  - block: markdown
    content:
      title: 学生团队
      text: |
        ## 王五
        ![王五的照片](/static/images/ww.png)
        **毕业年份**: 2022  
        **职位**: 毕业后就职于自然资源部第三海洋研究所，主要从事遥感数据处理工作。  
        王五在实验室期间参与了多个科研项目，尤其是在 SAR 图像分类与变化检测方向积累了丰富经验。

        ## 李四
        ![李四的照片](/static/images/ww.png)
        **毕业年份**: 2022  
        **职位**: 毕业后进入某科技公司，从事人工智能相关工作。  
        李四曾获优秀研究生奖学金，并参与多个项目的研发工作。

        ## 张三
        ![张三的照片](/static/images/ww.png)
        **毕业年份**: 2022  
        **职位**: 毕业后进入高校从事教学工作。  
        张三专注于人工智能与机器学习领域，并致力于培养下一代AI人才。

    design:
      view: article-grid
      columns: 3
      spacing:
        padding: ["2rem", "2rem", "2rem", "2rem"]
      custom_css: |
        .markdown h2 {
          font-size: 2rem;
          font-weight: bold;
        }
        .markdown p {
          font-size: 1rem;
        }
        .markdown img {
          width: 100%;
          height: auto;
          max-width: 300px; /* 确保每个图片的最大宽度 */
          margin-bottom: 1rem;
        }

  - block: markdown
    content:
      title: 毕业生团队
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
      view: single-column
      spacing:
        padding: ["2rem", "2rem", "2rem", "2rem"]
      custom_css: |
        .markdown h2 {
          font-size: 2rem;
          font-weight: bold;
        }
        .markdown p {
          font-size: 1rem;
        }
        .markdown img {
          width: 100%;
          height: auto;
          max-width: 300px;
          margin-bottom: 1rem;
        }

---
