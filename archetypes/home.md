---
# Possible Widgets:
#   team, contact, images, last-post, text
widget:
active: true

title: {{ replace .Name "-" " " | title }}
subtitle:

# Uncomment the options required for each widget

# Team widget
# folder:

# Images widget
#image1:
#   - path:
#   - alt:
#image2:
#   - path:
#   - alt:
#image3:
#   - path:
#   - alt:

# Recent posts widget
# n_posts: 3
# type: list # list or card

# Timeline widget
# You can add as much itens as you wish

#events:
#  - title: Fase 1
#    image:
#      path: img/bg1.jpg
#      alt:
#    project_url:
#    date: 2016-01-10
#    description: |
#       * Text show on card
#       * it can be multiple lines
#       * and even Markdown

# Order that this section will appear in.
weight: 100
---