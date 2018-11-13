---
# Possible Widgets:
#   team
#   contact
#   images
#   siginup
widget: ""
active: true
date: {{ .Date }}

title: "{{ replace .Name "-" " " | title }}"
subtitle: ""

#
folder: ""

# Order that this section will appear in.
weight: 100
---