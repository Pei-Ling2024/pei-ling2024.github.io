---
layout: page
title: Do DNNs share similar category space as humans?
description:
img: assets/img/animal.png
importance: 1
category: work
related_publications: false
---

# Goal

<span style="font-size:24px">
The goals of this project are two-fold: 1) to understand the contribution of different visual features of natural scenes to human category representation and 2) determine the similarity of that feature space to that of Deep Neural Networks (DNNs). It has been well-established that humans can tell which items are more typical than others. For example, most people would agree that the first beach (on the left) is more typical than the second beach (on the right). In this project, we use DNNs to investigate which category features are extracted in human category representation construction. 
</span>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/good_beach.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/bad_beach.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Both beaches were generated using DALL-E.
</div>

<hr style="height:2px;background:grey">

# Background

<span style="font-size:24px">
Categorization is a fundamental cognitive process that underlies many cognitive functions (e.g., separating spoiled food, finding your friends). Over the past sixty years, modern psychology has been exploring the structure of categories in the human mind. Understanding category structure involves studying how each member of a category is represented in our minds and arranged in some way. For instance, you might represent animals in terms of their size and whether they are predators. The space constructed by the dimensions of size and predator is the category space of the animal category in this example.
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

<span style="font-size:24px">
The first step we took is to calculate the correlations between the feature spaces from DNNs and human category space. To obtain the human category space, participants performed a same-different categorization task. Using a Multidimensional Scaling (MDS) visualization technique, we constructed the human category space (e.g., see Results) based on the responses to the same/different task. Next, we applied pre-trained neural networks (Zhou et al., 2017) to the same set of natural images and the resulting category representation were constructed by applying MDS on the layer activations. We then use the feature spaces of the neural network model to predict the human category space generated from categorization task.  
</span>

<hr style="height:2px;background:grey">

# Results

<span style="font-size:24px">
Followings are the category spaces from human categorization task (upper) and from the last layer of DNNs (lower). As shown in the space, results showed that the human category space constructed from the categorization task was not predicted well by any feature space produced from the models.
</span>

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

<span style="font-size:24px">
This work not only explores the limitations of DNNs as models of the human mind, but also provides possible directions to increase efficiency and robustness of DNNs by leveraging the mechanisms of the human minds
</span>

<hr style="height:2px;background:grey">

# Presentations and Publications

<span style="font-size:24px">
This project has been presented at [Vision Science Society Annual Meeting in 2023](https://jov.arvojournals.org/article.aspx?articleid=2791846) and also presented at the proseminar at Psychology Department at University of Illinois at Urbana-Champaign.
</span>
