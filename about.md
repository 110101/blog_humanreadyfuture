---
title: About
layout: about
---
<div class="shortabout typeset">
  <h4>About</h4>
  <div class="h_underline"></div>
</div>

Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

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
