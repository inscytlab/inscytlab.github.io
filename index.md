---
---

# Welcome to the InSCyTLab

The Intelligent Software and Cybersecurity Technologies Research Lab (InSCyTLab) comprises a team of researchers from the Information Technology Discipline in the [Faculty of Science and Engineering](https://www.scu.edu.au/science-and-engineering/) at [Southern Cross University](https://www.scu.edu.au/) in Australia. We are located on the beautiful Gold Coast Campus next to the [Coolangatta airport](http://www.goldcoastairport.com.au). We conduct research on new artificial intelligence technologies to support the development and operation of secure software systems and develop applications to solve real-world problems.

<!-- {%
  include button.html
  type="docs"
  link="https://greene-lab.gitbook.io/lab-website-template-docs"
%}
{%
  include button.html
  type="github"
  text="On GitHub"
  link="greenelab/lab-website-template"
%} -->

{% include section.html %}

![My image](images/campus.jpg)

## Highlights

{% capture text %}

Our research covers the broad areas of software engineering (SE), cybersecurity, and artificial intelligence (AI), especially topics intersecting these areas such as DevSecOps, software dependability and security, AI4SE, AI for cybersecurity, and security and privacy of AI systems. We are interested in CI/CD, modern code review, logging, code vulnerability detection, malicious behaviour recognition for malware, learning-based intrusion/anomaly detection, trustworthy AI, and human-AI interaction.

{%
  include button.html
  link="research"
  text="See our publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/research.png"
  link="research"
  title="Our Research"
  text=text
%}

{% capture text %}

We conduct research projects to address emerging issues in and innovate new technologies for SE, cybersecurity, and AI. We also develop applied projects to tackle real-world challenges such as in education, health, environmental sustainability, energy, and agriculture using state-of-the-art AI, SE, and cybersecurity technologies. Our projects are funded by government agencies, industries, and non-for-profit organisations.

{%
  include button.html
  link="projects"
  text="Browse our projects"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/projects.png"
  link="projects"
  title="Our Projects"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

The core team of InSCytLab comprises four experienced researchers and practitioners with collective expertise in software engineering, artificial intelligence, cybersecurity, and system development from the Discipline of Information Technology in the Faculty of Science and Engineering at Southern Cross University. Our team also includes research students and external collaborators. We share a common interest in research innovation for improving and securing software development and systems through developing new artificial intelligence technologies.

{%
  include button.html
  link="team"
  text="Meet our team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/team.png"
  link="team"
  title="Our Team"
  text=text
%}
