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
        **[STARTUP_NAME]** &nbsp;·&nbsp; [YOUR_ROLE] &nbsp;·&nbsp; [STAGE]

        [STARTUP_NAME] [WHAT_IT_DOES]. The company is grounded in the same research problems I study academically — bridging trustworthy AI, digital identity, and human-AI interaction from theory to production systems.

        - **Role:** [YOUR_ROLE] — [KEY_RESPONSIBILITIES]
        - **Traction / Outcome:** [OUTCOME_OR_TRACTION]
        - **Research connection:** Building and deploying [STARTUP_NAME] surfaced real-world failure modes in [RESEARCH_AREA] that academic benchmarks miss — directly shaping my PhD research agenda

        [Website →]([WEBSITE]) &nbsp;·&nbsp; [Press →]([PRESS_LINK]) &nbsp;·&nbsp; [GitHub →]([GITHUB])
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
    id: talks
    content:
      title: Talks & Media
      text: |
        *[TALK_TITLE]*, [VENUE], [DATE] — [DESCRIPTION_OR_LINK]\
        *[INTERVIEW_OR_PRESS_TITLE]*, [OUTLET], [DATE] — [LINK]
    design:
      columns: '1'

  - block: contact
    id: contact
    content:
      title: Contact
      text: 'Feel free to reach out for research collaborations, speaking invitations, or general inquiries.'
      email: '[YOUR_EMAIL]'
      contact_links:
        - icon: twitter
          icon_pack: fab
          name: Twitter / X
          link: 'https://twitter.com/[YOUR_HANDLE]'
        - icon: google-scholar
          icon_pack: ai
          name: Google Scholar
          link: 'https://scholar.google.com/citations?user=[YOUR_SCHOLAR_ID]'
        - icon: github
          icon_pack: fab
          name: GitHub
          link: 'https://github.com/[YOUR_GITHUB]'
        - icon: linkedin
          icon_pack: fab
          name: LinkedIn
          link: 'https://www.linkedin.com/in/[YOUR_LINKEDIN]'
    design:
      columns: '1'
---
