---
# Possible Widgets:
#   team
#   contact
#   images
#   siginup
#   last-post
widget: ""
active: true
date: {{ .Date }}

title: "{{ replace .Name "-" " " | title }}"
subtitle: ""

# folder: "" #used by team and post widget

# Order that this section will appear in.
weight: 100
---