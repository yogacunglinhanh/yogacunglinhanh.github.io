---
layout: page
title: Our Instructors
permalink: /instructors/
---

# Meet Our Instructors

Our diverse team of certified yoga instructors brings a wealth of experience and knowledge to every class.

{% for instructor in site.instructors %}
  <div class="instructor-card">
    <h2><a href="{{ instructor.url }}">{{ instructor.title }}</a></h2>
    <p><strong>{{ instructor.role }}</strong></p>
    <p><strong>Specialties:</strong> {{ instructor.specialties }}</p>
    <a href="{{ instructor.url }}" class="btn">Read Bio</a>
  </div>
  <hr>
{% endfor %}
