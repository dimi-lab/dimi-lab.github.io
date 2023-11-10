---
---
{% include section.html %}

DIMI lab: Data science and Informatics for Multiomics Integration.

{% include section.html %}

{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
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
  image="https://www.frontiersin.org/files/Articles/994467/fmed-09-994467-HTML-r1/image_m/fmed-09-994467-g001.jpg"
  link="research"
  title="Our Research"
  text=text
%}

{% capture text %}
With years of efforts, we have curated several high quality datasets consists of multi-modality of image and tabular data. 
We developed many tools to quantify tissue micro-anatomy, cell morphology, proteomics, transcriptomics 
and gene profiles of cancer cohorts to advance the understanding tumor development, metastasis and treatment response.

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
  image="images/projects/ov_tma_small.png"
  link="projects"
  title="Our Projects"
  style="bare"
  text=text
%}

{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

{%
  include button.html
  link="team"
  text="Meet our team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/events/social1.jpg"
  link="team"
  title="Our Team"
  text=text
%}
