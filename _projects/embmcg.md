---
layout: page
title: Extremal Minimal Bipartite Matching Covered Graphs
description: Part of my masters thesis
img: assets/img/12.jpg
importance: 1
category: work
related_publications: true
---

A bipartite matching covered graph is minimal if deletion of any edge results in a graph that is not matching covered. For a minimal BMCG, as we have deleted all the edges that we can possibly remove while retaining the matching covered property, one may hope to find _lots_ of vertices of _small_ degree. It is well-known that any MCG is 2-connected. So any vertex has degree at least 2. As it turns out, there are _lots_ of vertices of degree 2, which we will distinguish from the rest of the verties. Let 
$V_2$ be the set of vertices of degree 2
$V_3$ be the rest of the vertices (i.e. of degree at least 3). 

In the same spirit, we define the following:
$2$-edge : edge joining vertices of degree 2.
$3$-edge : edge joining vertices of degree at least 3.   

The following bounds were proved by Lovasz and Plummer. 

Every time you have a bound, an important question erupts immediately. Firstly, is the bound tight? Is there any example that satisfies the bound with equality (if not, one may hope to improve the bound further). These examples, that satisfy a bound with equality are called _extremal_. 

Now, every time you have a tight bound, another important question comes to the spotlight. What are all the extremal examples? This is exactly what we do. For each of the bounds, we characterize all the extremal examples.

To state the characterization, we will first introduce an operation which we call isomorphic leaf matching.

A tree is a holin tree if ...

Thm: 

## Easy Direction

## Difficult Direction

We want to prove that all extremal graphs look like something. This seems pretty hard, until you realize that you can play the uni reverse card. We will use induction. 

### Balanced 2-cut property

### Balanced 2-cut induction tool


Every project has a beautiful feature showcase page.
It's easy to include images in a flexible 3-column grid format.
Make your photos 1/3, 2/3, or full width.

To give your project a background in the portfolio page, just add the img tag to the front matter like so:

    ---
    layout: page
    title: project
    description: a project with a background image
    img: /assets/img/12.jpg
    ---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>

You can also put regular text between your rows of images, even citations {% cite einstein1950meaning %}.
Say you wanted to write a bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, _bled_ for your project, and then... you reveal its glory in the next row of images.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div>

The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

{% raw %}

```html
<div class="row justify-content-sm-center">
  <div class="col-sm-8 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm-4 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
```

{% endraw %}
