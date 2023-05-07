---
title: "{{ replace .TranslationBaseName "-" " " | title }}"
subtitle: ""
date: {{ .Date }}
lastmod: {{ .Date }}
draft: true
author: ""
authorLink: ""
description: ""
license: ""
images: [""]

tags: ["", "", ""]
categories: [""]

featuredImage: ""
featuredImagePreview: ""

hiddenFromHomePage: false
hiddenFromSearch: false
twemoji: false
lightgallery: false
ruby: false
fraction: false
fontawesome: true
linkToMarkdown: false
rssFullText: false

toc:
  enable: false
  auto: true
code:
  copy: false
  maxShownLines: 50
math:
  enable: false
  # ...
mapbox:
  # ...
share:
  enable: false
  # ...
comment:
  enable: false
  # ...
library:
  css: []
  js: []
seo:
  images: [""]
  # ...
---

<!--more-->

---

<div style="text-align:justify">

... without footnote ...

</div>

{{< style "text-align:justify" >}}

... contains footnote ...

{{< /style >}}
