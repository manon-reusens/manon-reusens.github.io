---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D in Business Economics, KU Leuven, 2025
* Research stay University of Michigan, October-December 2024
* Research stay University of Melbourne, september 2022
* M.S. in Business engineering (Magna Cum Laude - 84%), KU Leuven, 2021
* B.S. in Business engineering (Magna Cum Laude - 77.5%), KU Leuven, 2019
* Exchange Semester at Brock university, 2018

Work Experience
======
* 2025-present: Senior Researcher and Research Manager of ACRAI
  * University of Antwerp
  * Project: Responsible AI
* 2025- present: Guest Lecturer
  * KU Leuven
  * Teaching Principles of Database Management
* 2021-2025: PhD Researcher
  * KU Leuven
  * Beyond Performance: Exploring the Multidimensional Capabilities and Risks of Large Language Models
  * Supervisor: Bart Baesens; Co-Supervisors: Wouter Verbeke and Seppe vanden Broucke
* Summer 2020: Internship
  * Infofarm
  * Duties included: Data Preparation and Modeling

Publications
======
## Journal Articles
{% assign journals = site.publications | where: "publication_type", "journal" %}
<ul>{% for post in journals reversed %}
  {% include archive-single.html %}
{% endfor %}</ul>

## Conference Papers
{% assign conferences = site.publications | where: "publication_type", "conference"  %}
<ul>{% for post in conferences reversed %}
  {% include archive-single.html %}
{% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Mentoring
======
In total, I have guided 19 master theses at the KU Leuven.
Two of these projects have led to a journal publication, and one of them led to a publication at EMNLP 2023.
Apart from this, I have also guided summer interns.

  
Languages
======
* Dutch 
* English 
* French 
* Turkish (notions)

Service and leadership
======
* March 2024: Co-organizer of the session *Samenwerking tussen het netwerk Statistiek Vlaanderen en de academische wereld* at the [Dag van het Netwerk Statistiek Vlaanderen](https://www.vlaanderen.be/statistiek-vlaanderen/dag-van-het-netwerk-statistiek-vlaanderen-op-21-maart-2024)
* 2023-2024: [Midzomerfestival - Fonds Mathieu Reusens](https://fonds.mathieureusens.be/midzomerfestival), Festival Organizer
* 2020-2021: [Symphonic Orchestra of the KU Leuven](https://usoleuven.be/), President
* 2019-2020: [Symphonic Orchestra of the KU Leuven](https://usoleuven.be/), Treasurer
* 2018-2019: [Symphonic Orchestra of the KU Leuven](https://usoleuven.be/), Public Relations
