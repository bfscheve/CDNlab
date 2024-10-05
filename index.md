---
---

# Welcome to the CDN Lab @ University of Wisconsin-Madison! 
We are the Computational Developmental Neuroscience Laboratory at the University of Wisconsin, Madison. We use functional magnetic resonance imaging and computational techniques to understand brain development from late childhood throughout adolescence. We study topics that fall under the banners of affective, social, and cognitive development, and are particularly interested in phenomena related to emotion and emotion regulation, risk-taking and other forms of decision-making, and social behavior as it involves specific individuals. The overarching goal of this research is to better understand what drives development in everyday real-world contexts. It is our hope that this work helps identify factors that allow youths to grow into happy and healthy adults. The lab is part of the Department of Psychology, housed within the College of Letters & Science.

{% include section.html %}

## Learn more

{% capture text %}

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
  image="images/Fig1.png"
  link="research"
  title="Our Papers"
  text=text
%}

{% capture text %}

Our research fundamentally concerns how youths acquire necessary cognitive, affective and social skills, utilizing diverse data sets (functional magnetic resonance imaging (fMRI), capture of naturalistic written text, and ecological momentary assessment) and advanced computational techniques.

{%
  include button.html
  link="projects"
  text="See our research"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/research.png"
  link="projects"
  title="Our Research"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

{%
  include button.html
  link="team"
  text="Meet the lab"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="team"
  title="Our Team"
  text=text
%}
