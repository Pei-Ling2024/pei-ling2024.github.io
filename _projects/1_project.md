---
layout: page
title: What makes a good scene good?
description:
img: assets/img/12.jpg
importance: 1
category: work
related_publications: false
---

# Goal

<span style="font-size:24px">
This project aims to understand which features are considered more diagnostic of the categories from a human vision perspective. Humans can tell which items are more typical than others. For example, most people would agree that the first beach (on the left) is more typical than the second beach (on the right). Both beaches were generated using DALL-E. This project wants to investigate the diagnostic features underlying these decisions.
</span>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/good_beach.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/bad_beach.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

# Background

<span style="font-size:24px">
Categorization is a fundamental cognitive process that underlies many cognitive functions (e.g., separating spoiled food, finding your friends). Over the past sixty years, modern psychology has been exploring the structure of categories in the human mind. Understanding category structure involves studying how each member of a category is represented in our minds and arranged in some way. For instance, you might represent animals in terms of their size and whether they are predators. The space constructed by the dimensions of size and predator is the category space of the animal category.
</span>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/animal.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<span style="font-size:24px">
Past research on human categorization has mainly focused on artificial objects (e.g., letters) with clear and distinct feature sets. Recently, with improvements in computational power, many studies have shifted to understanding objects in real-life pictures. In the current project, we extend the exploration to natural scenes that contain both objects and the relationships among them.
</span>

<iframe
  src="https://codepen.io/team/codepen/embed/preview/PNaGbb"
  style="width:100%; height:300px;"
></iframe>

The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

{% raw %}

```html
<div class="row justify-content-sm-center">
  <div class="col-sm-8 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/6.jpg" title="example image"
    class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm-4 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/11.jpg" title="example image"
    class="img-fluid rounded z-depth-1" %}
  </div>
</div>
```

{% endraw %}
