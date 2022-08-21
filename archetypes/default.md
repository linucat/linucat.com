---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
draft: false
tags: ["all"]
categories: ["all"]
description: "Desc Text."
canonicalURL: "https://linucat.com/posts/{{.Name}}"
cover:
    image: "<image path/url>" # image path/url
    alt: "<alt text>" # alt text
    caption: "<text>" # display caption under cover
    relative: false # when using page bundles set this to true
    hidden: true # only hide on current single page
---

