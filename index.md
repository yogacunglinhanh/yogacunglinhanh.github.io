---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
title: Yoga cho mẹ bầu
---

# Find Your Balance with Peaceful Path Yoga

Our studio offers a range of yoga classes designed to meet you wherever you are in your yoga journey. From beginners to advanced practitioners, our experienced instructors create a supportive environment for growth and healing.

## Featured Courses

{% for course in site.courses limit:3 %}
  <div class="course-card">
    <h3><a href="{{ course.url }}">{{ course.title }}</a></h3>
    <p>{{ course.description | truncate: 150 }}</p>
    <p><strong>Level:</strong> {{ course.level }}</p>
    <a href="{{ course.url }}" class="btn">Learn More</a>
  </div>
{% endfor %}

## Why Choose Our Yoga Studio?

- **Expert Instructors**: All our teachers are certified with years of experience
- **Variety of Styles**: From Hatha to Vinyasa, Yin to Restorative
- **Personalized Approach**: Small class sizes for individual attention
- **Inclusive Community**: Welcoming environment for practitioners of all levels

[View All Classes](/courses/) | [Meet Our Instructors](/instructors/)
