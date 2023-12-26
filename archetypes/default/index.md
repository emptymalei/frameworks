---
date: "{{ .Date }}"
title: "{{ replace .File.ContentBaseName `-` ` ` | title }}"
summary: ""
images: # Create a folder in /static/images/colors that has the same name as this current markdown file and place the images there. We only need the file name here. If this is not clear, please refer to existing colors as references.
  # - path:
tags:
  - ""
links:
  - name: ""
    link: ""
author:    # the person who submitted this tool to KausalFlow
draft: false
---