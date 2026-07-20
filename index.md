---
---

# The Taylor Lab

We are interested in the molecular mechanisms of ageing specicaly through studying C. elegans. 

{% include section.html %}

## Highlights

{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

{%
  include button.html
  link="research"
  text="See our publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="research"
  title="Our Research"
  text=text
%}

{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

{%
  include button.html
  link="projects"
  text="Browse our projects"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="projects"
  title="Our Projects"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

{%
  include button.html
  link="members"
  text="Meet our members"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="members"
  title="Our Members"
  text=text
%}

{% include section.html %}

## Our Funders

{% capture content %}

{% include figure.html image="images/BBSRC.jpg" caption="BBSRC" link="https://www.ukri.org/councils/bbsrc/" %}
{% include figure.html image="images/NRPDTP.jpg" caption="NRP DTP" link="https://biodtp.norwichresearchpark.ac.uk/" %}

{% endcapture %}

{% include grid.html style="logos" content=content %}
