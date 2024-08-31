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

tags: [""]
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

<!--

magick 90Q.jpg -strip \
               -sampling-factor 4:2:0 \
               -interlace Plane \
               -quality 50 \
               -define webp:alpha-compression=1 \
               -define webp:alpha-filtering=1 \
               -define webp:auto-filter=true \
               -define webp:lossless=false \
               -define webp:method=6 \
               -define webp:partition-limit=0 \
               -define webp:show-compressed=true \
               -define webp:thread-level=1 \
50Q.webp

-->

<div style="text-align:justify">

... without footnote ...

</div>

{{< style "text-align:justify" >}}

... contains footnote ...

{{< /style >}}
