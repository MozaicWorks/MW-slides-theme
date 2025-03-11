# Mozaic Works Slides Theme

This repo contains a theme for slides generated from markdown.

## How to use

* install the marp visual studio code extension
* go to settings -> Markdown > Marp: Themes or vscode://settings/markdown.marp.themes  
* add the following path: https://raw.githubusercontent.com/MozaicWorks/MW-slides-theme/refs/heads/master/marp-mozaicworks.css
* add the following header to the marp markdown file:

```
---
marp: true
theme: marp-mozaicworks
paginate: true
title: "FILE TITLE"
header: "PRESENTATION TITLE"
footer: "©Mosaic Works All rights reserved https://mozaicworks.com"
---
```

You can also copy the example from the file example.md in this repo.

For more information check out the [marp](https://marpit.marp.app/) documentation.

## Image caption, attribution, code notes

Any italic paragraph following an image or code is considered a note.