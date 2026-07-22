---
---


We are interested in the molecular mechanisms of ageing  and proteostasis specicaly through studying the nematode,C. elegans. 

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
  link="news"
  text="Current News"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="news"
  title="Our News"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

{%
  include button.html
  link="members"
  text="Meet the Team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/groupphoto.jpg"
  link="members"
  title="Our Members"
  text=text
%}

{% include section.html %}

## Our Funders
{: .funders-heading }

{% capture content %}

{% include figure.html image="images/BBSRC.jpg" caption="BBSRC" link="https://www.ukri.org/councils/bbsrc/" %}
{% include figure.html image="images/NRPDTP.jpg" caption="NRP DTP" link="https://biodtp.norwichresearchpark.ac.uk/" %}

{% endcapture %}

{% include grid.html style="logos" content=content %}
