---
# Leave the homepage title empty to use the site title
title: Publications
date: 2024-09-29
type: landing

#---------------------------------------------------------------------------------

sections:

#---------------------------------------------------------------------------------

  - block: markdown
    content:
      title: "Publications"
      text: |-
        </br>

        | Year | [International</br>Journal](#id-ij) | [International</br>Conference](#id-ic) | [Domestic</br>Journal](#id-dj) | [Domestic</br>Conference](#id-dc) |
        |-----------|:---------------------:|:------------------------:|:----------------:|:-------------------:|
        |  **2023** |                     3 |                        9 |                4 |                   5 |
        |  **2022** |                     1 |                        2 |                2 |                  10 |
        |  **2021** |                     2 |                        1 |                1 |                  10 |
        | **2011~2020** |                44 |                      100 |               42 |                 127 |
        | **2001~2010** |                38 |                       83 |               12 |                  72 |
        | **1996~2000** |                 9 |                       31 |               11 |                  38 |

        

        </br>

        {{% callout note %}}
         Quickly discover relevant content by [**filtering publications:** Click here](/publication).
        {{% /callout %}}

#---------------------------------------------------------------------------------

  - block: collection
    id: id-ij
    content:
      title: International</br>Journal
      text: |-

      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article-journal'
    design:
      view: citation   
      columns: '2'

#---------------------------------------------------------------------------------

  - block: collection
    id: id-ic
    content:
      title: International</br>Conference
      text: |-

      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article-conference'
    design:
      view: citation
      columns: '2'

#---------------------------------------------------------------------------------

  - block: collection
    id: id-dj
    content:
      title: Domestic</br>Journal
      text: |-

      count: 3
      filters:
        folders:
          - publication
        publication_type: 'domestic-journal'
    design:
      view: citation
      columns: '2'

#---------------------------------------------------------------------------------

  - block: collection
    id: id-dc
    content:
      title: Domestic</br>Conference
      text: |-

      count: 5
      filters:
        folders:
          - publication
        publication_type: 'domestic-conference'
    design:
      view: citation
      columns: '2'

---