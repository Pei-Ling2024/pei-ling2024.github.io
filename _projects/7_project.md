---
layout: page
title: Can DNNs reflect scene typicality?
description:
img: assets/img/good_beach.png
importance: 1
category: work
related_publications: false
---

# Goal

<span style="font-size:24px">
This project aims to test whether the information extracted from deep neural networks (DNNs) can reflect human scene typicality. Similar to the project [What Makes a Good Scene Good Using DNNs?](https://pei-ling2024.github.io/projects/1_project/), this project investigates the category information extracted from DNNs but focuses on scene typicality.
</span>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/good_beach.png" title="good beach" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/bad_beach.png" title="bad beach" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The beach on the left or upper is more typical than the beach on the right or lower. Both beaches were generated using DALL-E.
</div>

<hr style="height:2px;background:grey">

# Background

<span style="font-size:24px">
Typicality is a prominent property in human category literature. Typicality is a property showing that members in the same category are not equally representive to the category. 
</span>

<hr style="height:2px;background:grey">

# Method

<span style="font-size:24px">
The first step we took is to calculate the correlations between the feature spaces from DNNs and human category space. To obtain the human category space, participants performed a same-different categorization task. Using a Multidimensional Scaling (MDS) visualization technique, we constructed the human category space (e.g., see Results) based on the responses to the same/different task. Next, we applied pre-trained neural networks (Zhou et al., 2017) to the same set of natural images and the resulting category representation were constructed by applying MDS on the layer activations. We then use the feature spaces of the neural network model to predict the human category space generated from categorization task.  
</span>

<hr style="height:2px;background:grey">

# Results

<span style="font-size:24px">

</span>
