---
title: People
date: 2022-10-24

type: landing

#---------------------------------------------------------------------------------

sections:

#---------------------------------------------------------------------------------

  - block: about.biography
    id: id-professor
    content:
      title: |-
        **Professor**
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: Changdon Kee

#---------------------------------------------------------------------------------

  - block: people
    id: id-member
    content:
      title: |-
        **Member**
      # Choose which groups/teams of users to display.
      #   Edit `user_groups` in each user's profile to add them to one or more of these groups.
      user_groups:
          - Postdoc
          - Ph.D Student
          - M.S Student
      sort_by: Params.grad_year
      sort_ascending: true
    design:
      show_interests: false
      show_role: true
      show_social: true

#---------------------------------------------------------------------------------

  - block: people
    id: id-alumni
    content:
      title: |-
        **Alumni**
        </br>
        </br>
      # Choose which groups/teams of users to display.
      #   Edit `user_groups` in each user's profile to add them to one or more of these groups.
      user_groups:
          - Ph.D
          - M.S
      sort_by: Params.grad_year
      sort_ascending: true
    design:
      show_interests: false
      show_role: true
      show_social: true


---