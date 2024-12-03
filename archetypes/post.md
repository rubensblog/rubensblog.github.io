---
date: '{{ .Date }}'
draft: true
title: '{{ replace .File.ContentBaseName `-` ` ` | title }}'
description: 'Desc Text.'
tags: ['post']
categories: ['blog']
author: 'Ruben Storm'
# author: ['Me', 'You'] # multiple authors
showToc: false
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
    image: "" # image path/url
    alt: "<alt text>" # alt text
    caption: "<text>" # display caption under cover
    relative: false # when using page bundles set this to true
    hidden: false # only hide on current single page
---
