---
title: About
layout: about
---
<div class="shortabout typeset">
  <h4>About</h4>
  <div class="h_underline_main"></div>
</div>

Hello, I am Malte, a tech product strategist/product manager. My curiosity to understand how things work and the believe that the future will be better with the help of technology drive my passion for new technologies.

I am a graduated electrical engineer with roots in hardware development. Over the time I extended my skills to software development, product and business to a holistic view as I believe that technology alone doesn't fix things. Products can only be truly great when they support the users, the society and its ethical values. <a href="/humanreadyfuture/">#humanreadyfuture</a>

At the intersection of user/stakeholder needs, technology and business I can put my experience, talents and enthusiasm best at work to create and launch new products that make a difference in everyday life.

<div class="subabout">
  <div class="icontitle">
    <div class="hicon"><img height="25" width="25" src="/assets/postimages/focusicon.png"></div>
    <h6>Focus</h6>
    <div class="h_subunderline"></div>
  </div>
    {% capture my_include %}{% include_relative /_content/focus.md %}{% endcapture %}
    {{ my_include | markdownify }}
</div>
<div class="subabout">
  <div class="icontitle">
    <div class="hicon"><img height="25" width="25" src="/assets/postimages/progressicon.png"></div>
    <h6>Approach</h6>
    <div class="h_subunderline"></div>
  </div>
    {% capture my_include %}{% include_relative /_content/approach.md %}{% endcapture %}
    {{ my_include | markdownify }}
</div>

{% include site-fixedproject.html %}
