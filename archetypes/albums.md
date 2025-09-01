+++
title = "{{ replace .Name "-" " " | title }}"
date = "{{ .Date }}"
draft = true
week = 0
chosenby = ""
genre = ""
origin = ""
release = 0
cover = "{{ lower .Name }}.jpg"
rym = ""
tags = [
    "tag1",
]
+++

This is a page about »{{ replace .Name "-" " " | title }}«.

![](../../images/covers/{{ lower .Name }}.jpg)

