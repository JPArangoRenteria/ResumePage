---
layout: resume
title: "Juan Pablo Arango"
permalink: /
---

# Profile
Software engineer with strong foundations in mathematics, communication engineering, and systems development. Experienced in embedded systems, networking, and full-stack development. Passionate about responsible AI and cross-functional collaboration in fast-paced environments.

# Contact Information
- **Location:** Keswick, Ontario
- **Phone:** 613-762-2123
- **Email:** [juanpablorenteria@cmail.carleton.ca](mailto:juanpablorenteria@cmail.carleton.ca)
- **GitHub:** [github.com/JPArangoRenteria](https://github.com/JPArangoRenteria)
- **LinkedIn:** [linkedin.com/in/juan-pablo-arango-0380b0191](https://linkedin.com/in/juan-pablo-arango-0380b0191)

# Experience
{% for job in site.data.sections.experience %}
## {{ job.company }} — {{ job.position }}  
*{{ job.start_date }} to {{ job.end_date }}*  
{{ job.location }}

<ul>
  {% for bullet in job.summary %}
  <li>{{ bullet }}</li>
  {% endfor %}
</ul>
{% endfor %}

# Education
{% for edu in site.data.sections.education %}
## {{ edu.school }}  
*{{ edu.degree }}*  
*{{ edu.start_date }} to {{ edu.end_date }}*  
{{ edu.location }}
{% endfor %}

# Skills
{% for skill_group in site.data.sections.skills %}
## {{ skill_group.name }}
<ul>
  {% for skill in skill_group.skills %}
  <li>{{ skill }}</li>
  {% endfor %}
</ul>
{% endfor %}

# Projects
{% for project in site.data.sections.projects %}
## {{ project.title }}  
*{{ project.start_date }} to {{ project.end_date | default: 'Present' }}*

<ul>
  {% for summary in project.summary %}
  <li>{{ summary }}</li>
  {% endfor %}
</ul>
{% endfor %}

# Languages
{% for language in site.data.sections.languages %}
- **{{ language.language }}:** {{ language.proficiency }}
{% endfor %}
