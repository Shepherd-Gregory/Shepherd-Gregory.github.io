---
layout: about
title: about
permalink: /
description: Postdoc Research Fellow, <a href="https://person.zju.edu.cn/xuyang94"> ZJU Homepage(CN)</a>

profile:
  align: right
  image: snowyoung.jpg

selected_projects: true
news: true  # includes a list of news items
selected_papers: false # includes a list of papers marked as "selected={true}"
social: true  # includes social icons at the bottom of the page

years: [2025, 2024, 2023, 2022, 2021, 2020]
---

<h2><font color="#0000dd">Brief bio</font></h2>

I am currently a Postdoctoral Research Fellow supervised by Prof. [Jiming Chen](https://person.zju.edu.cn/en/jmchen) at **Zhejiang University**, China. I received my D. Eng. degree at **Zhejiang University** (2023) under the supervision of Prof. [Meiqin Liu](https://scholar.google.com/citations?user=T07OWMkAAAAJ) and Prof. [Ronghao Zheng](https://scholar.google.com/citations?user=LxgdmqYAAAAJ).  I was also a visiting Ph.D. student with the **Robotics Institute, University of Technology Sydney (UTS)** supervised by Prof. [Shoudong Huang](https://www.uts.edu.au/staff/shoudong.huang) and Dr. [Liang Zhao](https://profiles.uts.edu.au/Liang.Zhao). 

<div class="row  align-items-center">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid " src="{{ '/assets/img/affiliations/compound.png' | relative_url }}" alt="" title="example image"/>
    </div>
</div>

---

<h2>Research interests</h2>

My research interests include active SLAM, autonomous exploration, informative path planning, and robot learning in robotics.  My current research projects mainly focus on **learning-based robot exploration in hazardous and complex environments** using ground robots. Welcome to reach out via email: [garryhsu0901@gmail.com](mailto:garryhsu0901@gmail.com)(Permanent)/[xuyang94@zju.edu.cn](mailto:xuyang94@zju.edu.cn) (Academic).

---

<div class="news">
  {% if page.news %}
    {% include news.html %}
  {% endif %}


</div>

---

<h2>Academic services</h2>

**Editorial Services**: **ICRA 2025**, Associate Editor;  **RO-MAN 2024**, Associate Editor.

<b>Conference Services</b>: ICRA 2024, Session Co-Chair (SLAM); ICUS 2024, PC Member/Invited Session Chair.

<b>Membership</b>: IEEE, IEEE Robotics and Automation Society (RAS), CAA.

<b>Journal Reviewer</b>: IEEE Trans. Autom. Sci. Eng., IEEE Robot. Autom. Lett., IEEE Trans. Cogn. Develop. Syst., IEEE Trans. Intell. Transport. Syst., IEEE Trans. Intell. Vehicle., IEEE Trans. Instrum. Meas., IEEE Trans. Indus. Inform., IEEE/CAA Journal of Autom. Sin., Robot. Auton. Syst., Meas. Sci.  Tech., IEEE Sensor J.

<b>Conference Reviewer</b>: ICRA, IROS, AIM, ICONIP(International Conference on Neural Information Processing), CCC(China Control Conference), CCDM(China Conference on Data Mining)

---

<h2>Awards</h2>

- National Postdoctoral Program for Innovative Talents (10 in automation nationwide), 2024
- Chinese National Scholarship for Ph.D. Students (2%), Oct. 2022
- Chinese Scholarship Council for Joint Ph.D. Students, Jul. 2022
- Academic Rising Stars of Ph.D. Students, Zhejiang University, Aug. 2022
- Outstanding Graduate Student of Zhejiang University, Oct. 2022


---

<h2>Talks and presentations</h2>

- **ICRA 2024 (Yokohama, Japan)** - CARE: Confidence-rich autonomous robot exploration using Bayesian kernel inference and optimization. [Video](https://youtu.be/xM2NbAQnvgs)

- 2024-04-27: Online talk & session chair at PRE-ICRA 2024. (Invited by CAA TC on Hybrid Intelligence) 

- 2023-05-18: On-site talk at [MiLab](https://milab.westlake.edu.cn/) of Westlake University. (Invited by Prof. [Donglin Wang](https://milab.westlake.edu.cn/index.html))~

- 2022-10-15: Online talk at PRE-IROS 2022. (Invited by CAA TC on Hybrid Intelligence) 

- **IROS 2022 (Kyoto, Japan)** - Confidence-rich localization and mapping based on particle filter for robotic exploration. [Video](https://youtu.be/t7awYSnC2dw)

- **IROS 2021 (Prague, Czech)** - CRMI: Confidence-rich mutual information for information-theoretic mapping, Video here: [Youtube](https://youtu.be/pUcGST2W_m8), [Bilibili](https://www.bilibili.com/video/BV1vQ4y1e77y?share_source=copy_web)

<h2>Posts and blogs</h2>

See all posts here: [`Posts`](/projects)

{% if page.selected_projects -%}
  <!-- Projects -->
  <div>
    {%- assign sorted_projects = site.projects | where: "selected", true | sort: "importance" -%}
    <div class="projects">  
      <div class="grid">
        {%- for project in sorted_projects -%}
        {% include projects.html %}
        {%- endfor %}
      </div>              
    </div>
  </div>
{%- endif %}