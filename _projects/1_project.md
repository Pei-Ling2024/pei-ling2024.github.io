---
layout: page
title: What makes a good scene good?
description:
img: assets/img/animal.png
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

<hr style="height:2px;background:grey">

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
Past research on human categorization has mainly focused on artificial objects (e.g., letters) with clear and distinct feature sets. Recently, with improvements in computational power, many studies have shifted to understanding objects in real-life pictures. In the current project, we further extend the exploration to natural scenes (e.g., beach, city, highway) that contain both objects and the relationships among them.
</span>

<hr style="height:2px;background:grey">

# Method
To investigate the complex real-life scenes, we leverage the ability of deep neural network models (DNNs) extracting category information. DNNs have demonstrated superior classification performance in the past decate. Several studies have also shown the correlations between the DNN layer activations and nural activities (Yamin et al., 2014). 



<hr style="height:2px;background:grey">

# Results
Following is a category space derived from 
<iframe
  src="https://beckaplab.web.illinois.edu/PL_data/Same-different.html"
  style="width:100%; height:500px;"
></iframe>

<iframe
  src="https://beckaplab.web.illinois.edu/PL_data/placenet_cluster.html"
  style="width:100%; height:500px;"
></iframe>


<hr style="height:2px;background:grey">

# Implications




<hr style="height:2px;background:grey">

# Presentations and Publications
This project has been presented at [Vision Science Society Annual Meeting in 2023](https://jov.arvojournals.org/article.aspx?articleid=2791846) and also presented at the proseminar at Psychology Department at University of Illinois at Urbana-Champaign.


