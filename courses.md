---
layout: page
title: Our Yoga Courses
permalink: /courses/
---

# Yoga Courses

Explore our range of yoga courses designed for all levels of experience.

{% for course in site.courses %}
  <div class="course-listing">
    <h2><a href="{{ course.url }}">{{ course.title }}</a></h2>
    <p>{{ course.description }}</p>
    <p><strong>Level:</strong> {{ course.level }} | <strong>Duration:</strong> {{ course.duration }}</p>
    <p><strong>Schedule:</strong> {{ course.schedule }}</p>
    <a href="{{ course.url }}" class="btn">Course Details</a>
  </div>
  <hr>
{% endfor %}

## Registration Information

Registration for all courses is available online or in person at our studio. Early bird discounts are available when you register at least 2 weeks in advance.

For questions or special accommodations, please [contact us](/contact/).
