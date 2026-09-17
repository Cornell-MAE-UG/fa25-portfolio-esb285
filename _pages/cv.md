---
layout: default
title: Elise Boisson - Curriculum Vitae
permalink: /cv/
cv_sections:
  - title: Education
    entries:
      - Cornell University, B.S. in Mechanical Engineering (Expected 2027)
      - Relevant coursework: mechanics of materials, thermodynamics, fluid mechanics, design, CAD/CAE, and experimental analysis
  - title: Courses
    entries:
      - MAE 3270: Mechanics of Materials
      - Fluid mechanics and thermal systems coursework
      - CAD and finite-element analysis coursework
      - Design and prototyping courses with hands-on engineering projects
  - title: Research
    entries:
      - Mechanical engineering research and analytical work focused on design validation, materials, and system performance
      - Experience combining hand calculations, simulations, and experimental documentation to evaluate engineering solutions
  - title: Projects
    entries:
      - Designing a Wrench - Advanced CAD and ANSYS analysis for a structural design project
      - Fluid Mechanics Dissection Video - Dehumidifier disassembly and fluid systems analysis
      - Independent and team-based engineering design work centered on prototyping, testing, and technical communication
  - title: Jobs / Experience
    entries:
      - Student engineering work involving CAD, analysis, and technical documentation
      - Mechanical design and research support through project-based coursework and hands-on design work
  - title: Clubs / Leadership
    entries:
      - Cornell engineering community involvement through design-focused and technical student activities
      - Collaboration on interdisciplinary projects requiring communication, documentation, and problem solving
  - title: Skills
    entries:
      - "CAD: Fusion 360, Autodesk tools"
      - "Analysis: ANSYS, MATLAB, finite-element and mechanical design analysis"
      - "Design: prototyping, iteration, technical documentation, and presentation"
      - "Tools: Microsoft Office, basic reporting, image and video documentation"
---
## Curriculum Vitae

<section class="cv-pdf" aria-labelledby="cv-pdf-title">
  <h2 id="cv-pdf-title">PDF version</h2>
  <object data="{{ "/assets/Elise_Boisson_Resume_F26.pdf" | relative_url }}" type="application/pdf" title="Elise Boisson curriculum vitae">
    <p>Your browser cannot display the PDF inline.
      <a href="{{ "/assets/Elise_Boisson_Resume_F26.pdf" | relative_url }}">Download the CV PDF</a>.
    </p>
  </object>
</section>

**Email:** [esb285@cornell.edu](mailto:esb285@cornell.edu) | **Phone:** +917 378 3001

---

{% for section in page.cv_sections %}
### {{ section.title }}
{% for entry in section.entries %}
- {{ entry }}
{% endfor %}
{% endfor %}

---
