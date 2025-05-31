+++
title = "{{ replace .Name "-" " " | title }}"
date = "{{ .Date }}"
draft = true
week = 0
chosenby = ""
genre = ""
origin = ""
release = 0
cover = ""
rym = ""
tags = [
    "tag1",
]
+++

This is a page about »{{ replace .Name "-" " " | title }}«.

![](../../images/covers/{{ replace .Name "-" " " | title }})

