---
title: Home
nav:
  order: 1
  tooltip: Home page
---
{% capture text %}
<h2>Our team</h2>
The Nemudryi Lab opened in September 2024 in the [Department of Biochemistry & Molecular Biology](https://biochem.med.ufl.edu/profile/nemudryi-artem/) at the [UF College of Medicine](https://med.ufl.edu).

Our team is growing, and we actively seek new members. **[Contact us](contact) if you are interested in joining!**

{%
  include button.html
  link="team"
  text="Meet our team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

<h2>Our research</h2>
We use computational biology and cutting-edge molecular techniques to understand the mechanisms of antiviral immunity across the domains of life and translate this understanding into innovative molecular tools.

{%
  include button.html
  link="research"
  text="Learn about our research"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}


{% endcapture %}

{%
  include feature.html
  image="/news/images/2025_lab_photo.jpg"
  link="team"
  flip=true
  style="bare"
  text=text
%}





