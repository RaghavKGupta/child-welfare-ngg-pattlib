<section class="usa-hero" aria-label="Introduction";>
  <div class="grid-container">
    <div class="usa-hero__callout">
      {% if hero.callout %}
      <h1 class="usa-hero__heading">
        {% if hero.callout.alt %}
        <span class="usa-hero__heading--alt">{{ hero.callout.alt }}</span>
        {% endif %}
        {{ hero.callout.text | default: hero.callout }}
      </h1>
      {% endif %}
       {% if hero.image %} 
    <div class="hero-image"><img src="{{ hero.image }}" /></div>
  {% endif %}
      {{ hero.content | markdownify }}
      {% if hero.button %}
      <a class="usa-button"
        href="{{ hero.button.href | relative_url }}">
        {{ hero.button.text }}
      </a>
      {% endif %}
    </div>
  </div>
</section>
