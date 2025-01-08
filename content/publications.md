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
        |  **2023** |                     0 |                        0 |                0 |                   5 |
        |  **2022** |                     0 |                        0 |                0 |                  10 |
        |  **2021** |                     0 |                        0 |                0 |                  10 |
        | **2011~2020** |                 0 |                        0 |                0 |                 127 |
        | **2001~2010** |                 0 |                        0 |                0 |                  72 |
        | **1996~2000** |                 0 |                        0 |                0 |                  38 |

        

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
        publication_type: 'international-journal'
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
        publication_type: 'international-conference'
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