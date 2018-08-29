---
title: Responsive images
---
Images in Bootstrap are made responsive with `.img-fluid`. `max-width: 100%;` and `height: auto;` are applied to the image so that it scales with the parent element.

###SVG images and IE 10

In Internet Explorer 10, SVG images with `.img-fluid` are disproportionately sized. To fix this, add `width: 100% \9;` where necessary. This fix improperly sizes other image formats, so Bootstrap doesn’t apply it automatically.


[learn more](https://getbootstrap.com/docs/4.1/content/images/#responsive-images)