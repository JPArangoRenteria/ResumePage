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

# Skills
- **Languages:** Python, C/C++, Golang, Java, JavaScript, TypeScript, TCL, Bash, MATLAB, R
- **Frameworks:** React.js, Next.js, Flutter, Node.js
- **Tools:** Docker, Kubernetes, Jenkins, GitLab CI/CD, Git, Linux
- **Databases:** PostgreSQL, MySQL, Firebase, NoSQL
- **Networking:** TCP/IP, OSPF, BGP, MPLS, RSVP, LDP, Wireshark, IXIA, IPerf
- **Testing/Infra:** Regression testing, traffic simulation, automated test development

# Experience
{% for item in site.data.sections.experience %}
## {{ item.company }} | *{{ item.position }}*
*{{ item.location }}*  
*{{ item.duration }}*

{% for responsibility in item.responsibilities %}
- {{ responsibility }}
{% endfor %}
{% endfor %}

# Education
{% for item in site.data.sections.education %}
## {{ item.degree }} | {{ item.institution }}
*{{ item.location }}*  
*{{ item.duration }}*

{% endfor %}

# Projects
{% for item in site.data.sections.projects %}
## {{ item.name }}  
*{{ item.duration }}*  

{% for description in item.descriptions %}
- {{ description }}
{% endfor %}
{% endfor %}

# Languages
- English – Professional
- Spanish – Native
- French – Conversational
- Portuguese – Conversational

