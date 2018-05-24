---
layout: default
title: Duckietown
permalink: index.html
---

<!--
<div style='float: right; text-align: left; margin-left: 2em'>
    <iframe width="300" height="220" src="https://www.youtube.com/embed/-TwocCeJUe8" frameborder="0" allowfullscreen>
    </iframe>
</div>
 -->

**Duckietown is a robotics education and outreach effort.**

The project started as a graduate class in 2016; as of 2017, about 20 other
universities have used the materials produced, as well as hundreds of self-guided
learners.

The most tangible goal of the project is to provide a **low-cost educational
"experience"** for learning autonomy.

Our platform consists of the "Duckiebots", simple autonomous robots, and the
"Duckietowns", the infrastructure in which the Duckiebots navigates.

In addition to the **hardware** and **software**, we build a set of **learning
modules** that can be used at various levels of education.


### Current status of the project

Duckietown has graduated from being one class to an international initiative.
We are in the process of creating the second version of the class and the
materials, preparing for a large publicity initiative in early 2018. There are
many ways in which [you can help](help.html).

<!--
<p class='more-information'>For more information, see the <a href="http://book.duckietown.org/master/duckiebook/what_is_duckietown.html#sec:what-is-duckietown">section <em>What is Duckietown?</em></a> in the Duckietown book.</p> -->

Duckietown is a distributed open-source project.
The main development efforts are hosted by
ETH Zürich (Switzerland), University of Montréal (Canada),
National Chiao Tung University (Taiwan), Toyota Technological Institute at Chicago (USA).


<div id='logos'>
    <!-- <img id='mit' src='media/logos/800px-MIT_logo.svg.png'/> -->
    <img id='eth' src='media/logos/eth_logo_kurz_pos-cropped.png'/>
    <img id='nctu' src='media/logos/1200px-NCTU_emblem.svg.png'/>
    <img id='udem' src='media/logos/1280px-Universite_de_Montreal_logo.svg.png'/>
    <img id='ttic' src='media/logos/ttic-new.png'/>
</div>

<style>
#logos img {  width: auto; margin-right: 1em;}

img#eth { height: 4em; }
img#udem { height: 4em; }
img#mit { height: 3em; }
img#nctu { height: 5em; }
img#ttic { height: 5em; }

</style>

### News

<ul id='news'>
  {% for post in site.posts %}
  {% if post.categories contains 'front-page' %}
    <li>
    {{ post.date | date_to_long_string }}
      <a href="{{ post.url }}">{{ post.title }}</a>
      <!-- {{ post.excerpt | remove: '<p>' | remove: '</p>' }} -->
      <a href="{{ post.url }}">(read more)</a>
    </li>
  {% endif %}
  {% endfor %}
</ul>

<style>
#news li p { display: inline; }
</style>
