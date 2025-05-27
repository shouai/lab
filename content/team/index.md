---
title: 团队
date: 2022-10-24

type: landing

sections:
  - block: team
    content:
      title: Meet the Team
      # Choose which groups/teams of users to display.
      #   Edit `user_groups` in each user's profile to add them to one or more of these groups.
      user_groups:
          - 教师团队
          - 学生团队
          - 毕业生团队
      #根据用户的姓（last_name）排序团队成员。
      sort_by: Params.last_name
      sort_ascending: true

    design:
      show_interests: false
      show_role: true
      show_social: true
---