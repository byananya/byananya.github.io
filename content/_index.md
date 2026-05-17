---
title:
type: landing

design:
  spacing: '3rem'

sections:

  - block: about.biography
    id: about
    content:
      username: admin

  - block: markdown
    id: research
    content:
      title: Research
      text: |
        My work spans the following areas:

        **Trustworthy AI & AI Safety**\
        Auditing frameworks and evaluation benchmarks for the reliability, fairness, and robustness of large-scale AI systems — especially LLMs deployed in high-stakes settings.

        **Digital Identity & Synthetic Media**\
        How generative AI disrupts identity verification pipelines, and building detection and provenance systems in response.

        **Human-AI Interaction & Teaming**\
        How people collaborate with AI in consequential decisions, and what interaction designs preserve meaningful human agency.

        **AI Automation & Governance**\
        Audit trails, accountability mechanisms, and deployment governance for AI automation in regulated industries.

        **Generative Media & Misinformation**\
        How AI-produced content propagates through information ecosystems and shapes public discourse.
    design:
      columns: '1'

  - block: collection
    id: publications
    content:
      title: Selected Publications & Preprints
      text: ''
      filters:
        folders:
          - publication
        featured_only: true
      count: 6
    design:
      view: citation
      columns: '1'

  - block: collection
    id: projects
    content:
      title: Selected Projects
      text: ''
      filters:
        folders:
          - project
        featured_only: true
    design:
      view: compact
      columns: '1'

  - block: markdown
    id: teaching
    content:
      title: Teaching & Service
      text: |
        **Teaching**
        - Teaching Assistant, [Course Name], [Institution], [Term] *(placeholder)*
        - Guest Lecturer, [Course Name], [Institution], [Term] *(placeholder)*

        **Academic Service**
        - Reviewer: FAccT, NeurIPS, ICML, ACL *(placeholder — update with actual venues)*
        - Program Committee: [Conference Name] *(placeholder)*
        - Workshop Organizer: [Workshop Name @ Venue] *(placeholder)*
    design:
      columns: '1'

  - block: contact
    id: contact
    content:
      title: Contact
      text: 'Feel free to reach out for research collaborations, speaking invitations, or general inquiries.'
      email: ananya@example.com
      contact_links:
        - icon: twitter
          icon_pack: fab
          name: Twitter / X
          link: 'https://twitter.com/'
        - icon: google-scholar
          icon_pack: ai
          name: Google Scholar
          link: 'https://scholar.google.com/'
        - icon: github
          icon_pack: fab
          name: GitHub
          link: 'https://github.com/'
        - icon: linkedin
          icon_pack: fab
          name: LinkedIn
          link: 'https://www.linkedin.com/'
    design:
      columns: '1'
---
