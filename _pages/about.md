---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I'm a Ph.d candidate specializing in Artificial Intelligence at the [College of Computer Science](https://cs.cqu.edu.cn/en2025/Home.htm), [Chongqing University](https://english.cqu.edu.cn/). My research interests include aviation big data analytics, explainable artificial intelligence, data mining, causal discovery and so on. I was awarded the National Scholarship for Postgraduates in 2023, Excellent Master's Thesis of Chongqing in 2022, and has published some articles in top international academic journals/conferences, such as IEEE Transactions on Knowledge and Data Engineering(TKDE), IEEE Transactions on Intelligent Transportation Systems(TITS), Knowledge-Based Systems(KBS), The Visual Computer(TVC), Ubiquitous Intelligence & Computing(UIC), etc. I has carried out the reviewing task of the KDD, KBS, TAES, AESM, and CJOA.

Education
======
* Ph.D in College of Computer Science, Chongqing University, 2022-now
* M.S. in College of Computer Science, Chongqing University, 2018-2021
* B.S. in College of Information Science and Technology, Nanjing Forestry University, 2014-2018

Publications
======
{% assign pubs_by_year = site.publications | group_by_exp: "post", "post.date | date: '%Y'" %}
{% assign sorted_years = pubs_by_year | sort: "name" | reverse %}

{% for year_group in sorted_years %}
  <h2>{{ year_group.name }}</h2>
  <ul>
    {% for post in year_group.items %}
      {% include archive-single-cv.html %}
    {% endfor %}
  </ul>
{% endfor %}

[Email](mailto:leuio@foxmail.com)
