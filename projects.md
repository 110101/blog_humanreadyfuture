---
layout: default
collectionpage: projects
pagination:
  enabled: true
---

{% if paginator.projects %}
  <section class="section  typeset">
    <ul class="list  list--posts">
      {% for page in paginator.projects %}
        <li class="item  item--post">
          <article class="article  article--post">
            <div class="heading">
              <h2><a href="{{ site.baseurl }}{{ page.url }}">{{ page.title }}</a></h2>
            </div>
            <div class="meta">
              {% include post-meta-short.html %}
            </div>
            <div class="text">
              {{ page.excerpt | markdownify | truncatewords: 300 }}
            </div>

            <a href="{{ site.baseurl }}{{ page.url }}">read more</a>
          </article>
        </li>
      {% endfor %}
    </ul>
    <!-- no pagination in the begining of the project -->
    <!-- {% include post-pagination.html %} -->
  </section>
{% else %}

  <section class="section  typeset">
    <div id="else"></div>
    <ul class="list  list--posts">
      {% for page in site.projects %}
        <li class="item  item--post">
          <article class="article  article--post">
            <div class="heading">
              <h2><a href="{{ site.baseurl }}{{ page.url }}">{{ page.title }}</a></h2>
            </div>
            {% include post-meta.html %}
            {{ page.excerpt | markdownify | truncatewords: 300 }}

          </article>
        </li>
      {% endfor %}
    </ul>
  </section>
{% endif %}

{% include site-inlinecontact.html %}
