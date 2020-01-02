---
title: Customize the Favicon
date: 2019-08-10T16:34:00+00:00
categories:
- Blogging
- Tutorial
tags:
- favicon
toc: false

seo:
  date_modified: 2020-01-02 09:35:53 +0000
---
the image files of [Favicons](https://www.favicon-generator.org/about/) are placed in `assets/img/favicons/`. You may need to replace them with your own. So let's see how to customize these Favicons.

Whit a square image (PNG, JPG or GIF) in hand, open the site [_Favicon & App Icon Generator_](https://www.favicon-generator.org/) and upload your original image.

![upload-image](/assets/img/sample/upload-image.png)

Click button <kbd>Create Favicon</kbd> and wait a moment for the website to generate the icons of various sizes automatically.

![download-icons](/assets/img/sample/download-icons.png)

Download the generated package, unzip and delete the following two from the extracted files:

* browserconfig.xml
* manifest.json

Now, copy the rest image files (`.PNG` and `.ICO`) to cover the original one in folder `assets/img/favicons/`.

At last, don't forget to rebuild your site so that the icon becomes your custom edition.