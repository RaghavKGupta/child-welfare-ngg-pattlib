
{% assign title = page.summary-title %}
{% assign list = page.summary-list %}
<div
  class="usa-summary-box--gray"
  role="region"
  aria-labelledby="summary-box-key-information"
>
  <div class="usa-summary-box__body">
    <h3 class="usa-summary-box__heading" id="summary-box-key-information">
      {{title}}
    </h3>
    <div class="usa-summary-box__text">
      <ul class="usa-list">
      {% for item in list %}
        <li>
          {{item.item}}
        </li>
        {% endfor %}
      </ul>
    </div>
  </div>
</div>