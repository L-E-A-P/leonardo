---
---
layout: default
---

<main id="main" class="main-content" aria-label="Content">
  <article>
    {% include page-image.html %}
    <div class="page-wrapper">
      <header class="page-header">
        {% if page.id %}
          {% assign title = page.title | markdownify | strip_html %}
        {% else %}
          {% assign title = page.title %}
        {% endif %}
        {% if page.link %}
          <h1 id="page-title" class="page-title"><a href="{{ page.link }}">{{ title }} <span class="link-arrow">&rarr;</span></a></h1>
        {% else %}
          <h1 id="page-title" class="page-title">{{ title }}</h1>
        {% endif %}
      </header>
      <div class="page-content">
        {{ content }}

        {% if page.share %}
          {% include social-share.html %}
        {% endif %}
      </div>
    </div>
  </article>
</main>

---


![gnam_ccbclarinet](https://github.com/L-E-A-P/alice/assets/114301020/e306d03a-82f3-462f-b05b-ee24f3ecd494)


