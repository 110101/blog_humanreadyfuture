---
title: Contact
layout: about
---
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
