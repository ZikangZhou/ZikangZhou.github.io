---
permalink: /
title: "About Me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am currently a third-year Ph.D. student at the Department of Computer Science, City University of Hong Kong (CityU), supervised by [Prof. Jianping Wang](https://scholar.google.com/citations?user=bow_liAAAAAJ&hl=en). Before joining CityU, I obtained my Bachelor's degree in Computer Science and Technology at Nanjing University (NJU). I am interested in machine learning applications for autonomous driving, including but not limited to **object detection**, **trajectory prediction**, and **motion planning**.

# Education

- 2020 - Present &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; Ph.D. in Computer Science, City University of Hong Kong
- 2016 - 2020 &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; BSc in Computer Science and Technology, Nanjing University

# Publications

<table style="width:100%;border:0px;border-spacing:0px;border-collapse:separate;margin-right:auto;margin-left:auto;">
<tbody>
  {% for post in site.publications reversed %}
    {% if post.show %}
      {% include archive-single.html %}
    {% endif %}
  {% endfor %}
</tbody>
</table>

# Awards

- Outstanding Academic Performance Award, City University of Hong Kong, 2022

# Professional Services

- Reviewer for CVPR 2023

# Teaching

- Tutor for CS2360 Java Programming, Semester A, 2022/23, City University of Hong Kong
- Tutor for CS2360 Java Programming, Semester A, 2021/22, City University of Hong Kong
