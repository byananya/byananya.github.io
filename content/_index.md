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

  - block: markdown
    id: venture
    content:
      title: Venture / Startup
      text: |
        **Pulse AI** &nbsp;·&nbsp; Founder &nbsp;·&nbsp; Stealth

        Pulse AI is building in the space of AI-driven identity outreach, grounded in the same research problems I study academically — trustworthy AI, digital identity, and how people and institutions navigate AI-mediated interactions.

        - **Role:** Founder — TBD
        - **Traction / Outcome:** TBD
        - **Research connection:** Building Pulse AI surfaced real-world failure modes in AI identity systems that academic benchmarks miss — directly shaping my PhD research agenda
    design:
      columns: '1'

#  - block: collection
#    id: publications
#    content:
#      title: Selected Publications & Preprints
#      text: ''
#      filters:
#        folders:
#          - publication
#        featured_only: true
#      count: 6
#    design:
#      view: citation
#      columns: '1'

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
    id: talks
    content:
      title: Talks & Media
      text: |
        TBD
    design:
      columns: '1'

  - block: markdown
    id: beyond
    content:
      title: When I'm not building
      text: |
        {{< icon name="music" pack="fas" >}} **Classical Dance**

        I'm a trained Bharatanatyam dancer. The precision and discipline of classical form — learning to embody abstract emotion through codified movement — is something I carry into research: rigor as a vehicle for expression.

        {{< icon name="utensils" pack="fas" >}} **Cooking & Baking**

        I also enjoy cooking haute cuisine, finding joy in the craft of transforming simple ingredients into something refined and intentional. Baking, with its precise ratios and patient processes, feels like a natural complement — equal parts science and artistry.
    design:
      columns: '1'

  - block: contact
    id: contact
    content:
      title: Contact
      text: 'Feel free to reach out for research collaborations, speaking invitations, or general inquiries.'
      email: 'TBD'
      contact_links:
        - icon: twitter
          icon_pack: fab
          name: Twitter / X
          link: 'https://twitter.com/TBD'
        - icon: google-scholar
          icon_pack: ai
          name: Google Scholar
          link: 'https://scholar.google.com/citations?user=TBD'
        - icon: github
          icon_pack: fab
          name: GitHub
          link: 'https://github.com/TBD'
        - icon: linkedin
          icon_pack: fab
          name: LinkedIn
          link: 'https://www.linkedin.com/in/TBD'
    design:
      columns: '1'
---
