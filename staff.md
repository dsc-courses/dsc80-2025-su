---
layout: page
title: 👩‍🏫 Staff
description: A listing of all the course staff members.
nav_order: 6
---

# 👩‍🏫 Staff

## Instructor

<div class="staffer">
  <img class="staffer-image" src="/assets/staff-images/biving_sadler.jpg" alt="Bivin Sadler">

  <div>
    <h3 class="staffer-name">
      <a href="https://datascience.smu.edu/about/leadership-and-faculty/bivin-sadler/">Bivin Sadler</a>
    </h3>

    <!-- Contact Information -->
    <p>
      <a href="mailto:bisadler@ucsd.edu">bisadler@ucsd.edu</a><br>
    </p>

    <!-- Instructor Paragraph -->
    <p>
    Originally from Dallas Texas, Dr. Bivin Sadler finished a BS in mathematics magna cum laude from Texas Tech University before beginning his professional career in Scottsdale, Arizona, at Motorola. He worked as a statistician and software engineer for 2.5 years, working primarily on a companywide tool to predict when software projects could be released with optimal statistical properties (Six Sigma). Upon completion of the project, he moved to San Diego, and while playing professional beach volleyball for two years, finished a master’s degree in applied math at San Diego State University. He then moved back to Dallas to earn a PhD in statistics from SMU and finished his degree in 2014 after winning the Walsh Award for the top score on the qualifying exam taken after the third year of coursework.

    Dr. Sadler was hired as part of the faculty at SMU after graduation and began a dual appointment teaching both undergraduate and graduate classes in the statistics department and online with the newly formed Master of Science in Data Science (MSDS) program. Academically, he has presented his work in item response theory at various conferences and is currently working on several domestic and international consulting projects. He became a full-time member of the MSDS faculty in August 2018 and, in addition to consulting projects and teaching, is working on developing new courses in time series and business analytics.
    </p>
  </div>
</div>


## Staff

{% assign tas = site.staffers | where: 'role', 'TA' %}
{% for staffer in tas %}
{{ staffer }}
{% endfor %}

<!-- {% assign staff = site.staffers | where: 'role', 'Tutor' %}
<div class="role">
  {% for staffer in staff %}
  {{ staffer }}
  {% endfor %}
</div> -->
