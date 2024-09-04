---
date: '{{ .Date }}'
draft: true
title: '{{ replace .File.ContentBaseName `-` ` ` | title }}'
description: 'Desc Text.'
tags: ['vlog', 'video', 'youtube']
categories: ['vlog', 'video']
author: 'Ruben Storm'
showToc: true
TocOpen: false
hidemeta: false
comments: false
disableShare: false
disableHLJS: false # to enable|disable highlightjs - true|false
hideSummary: false
searchHidden: false # Hide or show in search
ShowReadingTime: true
ShowBreadCrumbs: true
ShowPostNavLinks: true
ShowWordCount: true
ShowRssButtonInSectionTermList: true
UseHugoToc: true
cover:
    image: "<image path/url>" # image path/url
    alt: "<alt text>" # alt text
    caption: "<text>" # display caption under cover
    relative: false # when using page bundles set this to true
    hidden: true # only hide on current single page
---

Text

{{< youtube w7Ft2ymGmfc >}}

## Literatur
*Hier habe ich ein paar Links zu Amazon mit Literatur zum Thema des Vlogs. Wenn du den Link verwendest, werde ich damit ein bisschen unterstützt. Der Link ist nur auf Amazon Deutschland verfügbar.*

[Literatur One][LiteraturOne]
[Literatur Two][LiteraturTwo]
[Literatur Three][LiteraturThree]

## Links
*Hier habe ich Links mit Referenzen und weiteren Informationen zum Thema im Vlog.*

[Youtube Video][YoutubeVideo]
[Youtube Kanal][YoutubeKanal]
[Foto Album][ImageGallery]
[Informationen zum Ort][LocationInformation]


[LiteraturOne]: http
[LiteraturTwo]: http
[LiteraturThree]: http

[YoutubeKanal]: http
[YoutubeVideo]: http
[ImageGallery]: http
[LocationInformation]: http
