---
layout: page
title: Université de Montréal
longtitle: "Autonomous Vehicles"
permalink: classes/2017/17-Montreal/index.html
---


Welcome to the webpage for the class **Autonomous Vehicles** at [l'Université de Montréal][montreal] which is informally known as "Duckietown" (officially [IFT 6080 Sujets en exploitation des ordinateurs](https://admission.umontreal.ca/cours-et-horaires/cours/IFT-6080/)).

[montreal]: http://www.umontreal.ca/en/

<p class='under-construction'>
The site is just getting built now, please bear with me
</p>

<img src="/media/duckietown-nice.png" alt="Duckietown" style="height: 200px; width: 250px"/><img src="/media/classes/duckietown-mit.jpg" alt="MIT Duckietown" style="height:200px; width: 400px; border: 5px"/><img src="/media/duckiebot-side.png" alt="Duckiebot" style="height: 200px; width: 200px"/>


This class follows the [successful first edition at MIT in 2016](/classes/2016/16-MIT/index.html).

[Read the official description](description/)

[Read the tentative class schedule](schedule/)

**I am looking for people to help me and get involved in any way. Please read below [available positions](#positions)**


### For students interested in taking the class

There are only 12 spots available for the class this year. If you are interested to be in the class, please fill out [the application form][form]. Please be verbose with the long answer questions and include anything that might help you stand out. This class is a collaborative learning experience and I'm looking for a good mix of talents and personalities.

**I invite all to come to the first class Wed Sept. 6 @ 11:30 in rm. Z-210 Pavilion Claire-McNicoll. Decisions about admissions will be made following the first class**.

The official admissions process will require filling out a [university application form](https://admission.umontreal.ca/admission/cycles-superieurs/demande-dadmission/) if you a student at U de M and contacting Céline Bégin if you are not.

[form]: https://goo.gl/forms/Aqh1EY4B2AlENvLr2

There are no "prerequisites" for the course but a strong programming background, as well as any knowledge of basic probabilities, computer vision, or control will all help.

If you are not sure whether or not you would like to take the class I would encourage you to:
* [Have a look at the site for last year's class at MIT](/classes/2016/16-MIT/index.html)
* [Read our paper at ICRA about the project][duckietown-icra]
* [Read below about what makes this a special class](#special).


[duckietown-icra]: http://people.csail.mit.edu/lpaull/publications/Paull_ICRA_2017.pdf

**NB: You need to have your own laptop to take this course, and you need to be willing to install a fresh Ubuntu 16.04 partition on it for the duration of the class (I can help you with this)**

### For non-students who want to get involved {#positions}

## University Professors in the Montreal area

I am looking for excellent guest lectures to include in the class. The topic of the lectures is very flexible, but if you see something that is already [in the syllabus](description) then that's even better. Please [contact me asap][lpaull].

[lpaull]: http://people.csail.mit.edu/lpaull

## Postdocs in the Montreal area

Similarly to the above solicitation to professors, I am interested in having postdocs give guest lectures in their areas of expertise. Please [contact me asap][lpaull].

Additionally, I am looking for postdocs to act as mentors in the course project phase of the class. In the MIT version we had about 15 or so of these magical postdocs helping with the class. It is not impossible that you get your name on a paper out of it! (But no promises..). Please [contact me asap][lpaull].

## Anyone else that wants to help

We have many needs from small to large. Whatever your expertise, it is likely that we can use your help. Not least of all would other students who want to act as teaching assistants (I might be able to pay you). Please [contact me asap][lpaull].

### What makes this a special class? {#special}

This class is unique in many ways.

## Class philosophy

The best engineers are the ones who have solid theoretical foundations,
as well as practical experience in the domain of interest.

In autonomous robotics, it is important to get the "feeling" of what actually
makes a robot work, how the success or failure depends on subtle interaction
between many hardware and software components.

To obtain enlightenment, it is necessary to study a complete system
like Duckietown. The materials might be cheap, the appearance
might be playful, but the complexity of behaviors and representations
is comparable to those of deployed robotic systems.

<!-- Studying, and building from scratch, a complex system like the DuckeibotThe way to do this, is not to study every component in
isolation, but rather creating a complex system. -->

For more information about the class philosophy, please
refer to this paper:

<cite class='pub-ref-desc' id='bib:tani16duckietown'>
    <a href='https://eapsweb.mit.edu/people/jtani'>Jacopo Tani</a>, <a href='http://people.csail.mit.edu/lpaull/'>Liam Paull</a>, <a href='https://eapsweb.mit.edu/people/zuber/'>Maria Zuber</a>, <a href='http://danielarus.csail.mit.edu/'>Daniela Rus</a>, <a href='http://www.mit.edu/~jhow/'>Jonathan How</a>, <a href='https://marinerobotics.mit.edu/'>John Leonard</a>, and
    <a href="https://censi.science">Andrea Censi</a>.
    <strong class="title">Duckietown: an innovative way to teach autonomy.</strong>
    <span class="booktitle">In <em>EduRobotics 2016</em>. Athens, Greece, December 2016.</span>
    <span class="links"><span class="pdf"><a href="http://people.csail.mit.edu/lpaull/publications/Tani_EDU_2016.pdf">
    <img style='border:0; margin-bottom:-6px; width:17px; height: 17px' src='/media/pdf.png'/> pdf</a></span></span>
</cite>


### A personal experience

Each student gets their own personal Duckiebot and can bring it home.


### Collaboration with other world-class institutions

This class is offered at the same time at two others institutions:

- ETH Zurich, led by [Prof. Emilio Frazzoli][frazzoli], [Dr. Andrea Censi][censi], and [Dr. Jacopo Tani][tani].

[frazzoli]: http://www.idsc.ethz.ch/research-frazzoli.html
[censi]: https://censi.science/
[tani]: https://eapsweb.mit.edu/people/jtani

- At the Toyota Technological Institute at Chicago and the University of Chicago, led by [Prof. Matthew Walter][walter].

[walter]: http://ttic.uchicago.edu/~mwalter/

The three institutions will develop the autonomous fleets together. You will have the opportunity to work cooperatively with students from these other institutions. **NB: to the best of our knowledge this has never been done before - you will be a part of history.**


### Your code can live on

This class is a living thing, it will never be the same twice. The best projects from each year will be added to or replace existing code in the [duckietown codebase][software]. If you do a good job, your project will be what next year's students use and try and improve upon.

[software]: https://github.com/duckietown/Software




## Updates to this page

<ul id='news'>
  {% for post in site.posts %}
  {% if post.categories contains '17-Montreal' %}
    <li>
    {{ post.date | date_to_long_string }} -
      <strong>{{ post.title }}</strong> -
      {{ post.content }}
    </li>
  {% endif %}
  {% endfor %}
</ul>

<style>
#news li p { display: inline; }
</style>
