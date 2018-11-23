---
# Possible Widgets:
#   team, contact, images, last-post, text, images
widget: ""
active: true
date: {{ .Date }}

title: "{{ replace .Name "-" " " | title }}"
#subtitle: ""

# Team widget configs
# folder: ""

# Images widget configs
#image1:
#   - path: ""
#   - alt: ""
#image2:
#   - path: ""
#   - alt: ""
#image3:
#   - path: ""
#   - alt: ""

# Recent posts widget configs
# n_posts: 3

# Order that this section will appear in.
weight: 100
---