---
title: Testimonials
layout: default
permalink: testimonials
---

# Testimonials

<ul class="testimonials-grid clearfix">
{% for slide in site.data.testimonials.data %}
  <li style="height: 147px;">
    <div class="testimonial">
      <div class="testi-image">
        <a href="#"><img src="https://www.countryflags.io/{{slide.country_code}}/shiny/64.png" alt="Customer Testimonails"></a>
      </div>
      <div class="testi-content">
        <p>{{slide.testimonial}}</p>
        <div class="testi-meta">
          {{slide.fullname}}
          <span>{{slide.org}}</span>
        </div>
      </div>
    </div>
  </li>
{% endfor %}
</ul>