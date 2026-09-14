---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2022-10-24
type: landing

sections:

  # =========================
  # PROFILE / EDUCATION / INTERESTS
  # =========================
  - block: resume-biography-3
    content:
      username: me
      text: ''
      button:
        text: Download CV
        url: uploads/resume.pdf
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      background:
        gradient_mesh:
          enable: true
      name:
        size: sm
      avatar:
        size: large
        shape: circle


  # =========================
  # MY RESEARCH
  # =========================
  - block: markdown
    content:
      title: '🔬 My Research'
      subtitle: ''
      text: |-
        I am interested in developing reliable and impactful AI solutions for real-world healthcare challenges, with a focus on responsible and practical AI research.

        I am open to research collaborations and academic opportunities.
    design:
      columns: '1'


   # =========================
  # LEADERSHIP
  # =========================
  - block: research-areas
    id: leadership
    content:
      title: '♟️ Leadership'
      subtitle: ''
      text: ''
      items:

        - name: 'Executive Member (Research)'
          description: |
            **CSTE Club, Noakhali Science and Technology University (NSTU)**

            *2024–2025*

            Contributed to organizing research activities, academic events, workshops, and collaborative initiatives while promoting research and innovation within the department.
          image: leadership/cste-research-2024-25.png
          cta:
            text: 'View on Facebook →'
            url: 'https://www.facebook.com/share/1CtXvzoZ7L/'

        - name: 'Public Relations Secretary'
          description: |
            **CSTE Club, Noakhali Science and Technology University (NSTU)**

            *2025–2026*

            Managed internal and external communications, promoted research and technical events, coordinated student engagement, and supported public relations and event promotion initiatives.
          image: leadership/cste-pr-secretary-2025-26.png
          cta:
            text: 'View on Facebook →'
            url: 'https://www.facebook.com/share/18y8DeovW7/'

    design:
      layout: cards
      columns: 2


  # =========================
  # VOLUNTEERING & ENGAGEMENT
  # =========================
  - block: markdown
    content:
      title: '🤝 Volunteering & Engagement'
      subtitle: ''
      text: |-
        ### Associate Member

        **United Nations Youth and Students Association of Bangladesh (UNYSAB)**  
        *19.0 Batch*

        Associate Member contributing to youth engagement and development-oriented activities.
    design:
      columns: '1'


  # =========================
  # FOOTER LINE
  # =========================
  - block: markdown
    content:
      title: ''
      subtitle: ''
      text: |-
        <div style="text-align: center; margin-top: 30px; padding: 20px 0;">
          © 2026 Hasna Hena Joti · Healthcare AI Researcher · CSTE, NSTU, Bangladesh
        </div>
    design:
      columns: '1'
---
