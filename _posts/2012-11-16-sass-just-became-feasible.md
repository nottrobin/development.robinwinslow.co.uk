---
title: Sass just became feasible
description: Now that Chrome Developer Tools and Firebug support Sass debugging, CSS pre-processors have a viable future.
layout: post
image_url: https://upload.wikimedia.org/wikipedia/commons/thumb/9/96/Sass_Logo_Color.svg/1280px-Sass_Logo_Color.svg.png
tags:
  - dev
  - CSS
  - front-end
---

I've been interested in CSS pre-processors for a while. They solve the inherent CSS problem of repeatable code blocks, and thus enable [grid systems](http://semantic.gs/) that don't [litter markup with "styling" classes](http://webdesignernotebook.com/css/are-css-frameworks-evil/).

It seems to me that [LESS](http://lesscss.org/) and [Sass](http://sass-lang.com/) always had one Achilles heel - debugging. Right clicking on an element that is styled incorrectly and inspecting it is absolutely essential to the process of styling a web page, and without that, these tools had no future. I now believe that this problem is behind us.

In addition to the [existing solutions](http://stackoverflow.com/questions/9865302/less-sass-debugging-in-chrome-dev-tools-firebug), Webkit now has [built-in support](http://trac.webkit.org/changeset/123768) for Sass debugging, and the option is now included in Chrome Developer Tools. Read more about it on [bricss.net](http://bricss.net/post/33788072565/using-sass-source-maps-in-webkit-inspector) or [benfrain.com](http://benfrain.com/add-sass-compass-debug-info-for-chrome-web-developer-tools/).

As a side-note - there is a bit of a [battle between LESS and Sass](http://stackoverflow.com/questions/8411066/less-vs-sass-vs). I always preferred LESS because it seemed more cross-platform, and closer to actual CSS. However this development seems to suggest that tools are being developed faster for Sass. So it's now looking to me as though Sass will prevail.
