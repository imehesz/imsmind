---
layout: post
title: ImageMagick
tags:
- dev
- linux
---

[ImageMagick](http://www.imagemagick.org) never fails to amaze me. Recently I realized that **Google** has stopped supporting [Picasa for Linux](http://www.omgubuntu.co.uk/2012/04/google-officially-drop-picasa-for-linux), which was a great tool to upload photos to your **Picasa** albums, and could resize them on the fly! So I needed something similar that can be easily executed for multiple images at once.

With the command below you can resize all the files to 800x600 (keeping aspect ratio!)

`mogrify -resize 800x600 -format jpg *`
