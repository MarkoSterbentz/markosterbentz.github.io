---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "1rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
    # design:
    #   css_class: light
    #   background:
    #     color: '#f5f5f5'
        # image:
        #   # Add your image background to `assets/media/`.
        #   filename: stacked-peaks.svg
        #   filters:
        #     brightness: 1.0
        #   size: cover
        #   position: center
        #   parallax: false
  # - block: markdown
  #   content:
  #     title: '📚 My Research'
  #     subtitle: ''
  #     text: |-
  #       Placeholder text.
  #   design:
  #     columns: '1'
  - block: markdown
    id: news
    content:
      title: 'News'
      subtitle: ''
      text: |-
        - **June 2025:** I'm excited to be starting an internship at IBM Research for the summer working on LLMs for data research.
        - **November 2024:** I presented the <a href="https://arxiv.org/abs/2406.12069">Satyrn paper</a> at <a href="https://2024.emnlp.org/">EMNLP 2024</a>.
        - **September 2024:** Our paper <a href="https://arxiv.org/abs/2406.12069">Satyrn: A Platform for Analytics Augmented Generation</a> was just accepted to <a href="https://2024.emnlp.org/">EMNLP 2024</a>. See you in Miami!
        - **June 2024**: I partcipated in the CASMI workshop "AI Safety: A Domain-Focused Approach to Anticipating Harm." <a href="https://casmi.northwestern.edu/documents/ai-safety-a-domain-focused-approach-to-anticipating-harm.pdf">Read the full report</a>.
        - **July 2023**: I participated in the CASMI workshop on "<a href="https://casmi.northwestern.edu/news/articles/2023/measuring-safety-in-artificial-intelligence-positionality-matters.html">Sociotechnical Approaches to Measurement and Validation for Safety in AI</a>."
        - **June 2023**: Attended <a href="https://facctconference.org/2023/">FAccT 2023</a>! Here's an <a href="https://casmi.northwestern.edu/news/articles/2023/ai-ethics-debate-at-chicago-conference,-precursor-to-casmis-next-workshop.html">article which includes some of my and my colleagues' thoughts</a>.
        - **June 2023**: Cameron Barrie and I gave a demonstration of our research at the "Exploring Opportunities at the Intersection of Healthcare and AI" event. <a href="https://ai.northwestern.edu/news-events/articles/2023/using-ai-chatgpt-to-augment-the-future-of-healthcare.html">Read more here</a>!
    design:
      columns: '1'
  # - block: collection
  #   id: papers
  #   content:
  #     title: Featured Publications
  #     filters:
  #       folders:
  #         - publication
  #       featured_only: true
  #   design:
  #     view: article-grid
  #     columns: 2
  - block: collection
    id: papers
    content:
      title: Publications
      filters:
        folders:
          - publication
    design:
      view: citation
      # background:
      #   color: '#f5f5f5'

  # - block: markdown
  #   id: experience
  #   content:
  #     title: Experience
  #     spacing: 1rem
  #     text: |
  #       <div class="experience-section" style="font-family: Arial, sans-serif; margin: 20px auto; width: 90%; min-width: 400px;">
  #           <div class="job" style="margin-bottom: 20px; padding-bottom: 15px; border-bottom: 1px solid #ddd;">
  #               <h3 style="font-size: 1.4em; margin-bottom: 5px;">Research Assistant</h3>
  #               <span style="display: block; font-size: 1.1em; margin-bottom: 5px;">Northwestern University</span>
  #               <span style="font-size: 0.9em; color: #555;">January 2019 - Present</span>
  #           </div>
  #           <div class="job" style="margin-bottom: 20px; padding-bottom: 15px; border-bottom: 1px solid #ddd;">
  #               <h3 style="font-size: 1.4em; margin-bottom: 5px;">Research Intern</h3>
  #               <span style="display: block; font-size: 1.1em; margin-bottom: 5px;">Lawrence Livermore National Laboratory</span>
  #               <span style="font-size: 0.9em; color: #555;">June 2020 - December 2021</span>
  #           </div>
  #           <div class="job" style="margin-bottom: 20px; padding-bottom: 15px; border-bottom: 1px solid #ddd;">
  #               <h3 style="font-size: 1.4em; margin-bottom: 5px;">Research Intern</h3>
  #               <span style="display: block; font-size: 1.1em; margin-bottom: 5px;">Idaho National Laboratory</span>
  #               <span style="font-size: 0.9em; color: #555;">January 2020 - May 2020</span>
  #               <p style="margin-top: 10px; line-height: 1.5;"></p>
  #           </div>
  #       </div>
  - block: resume-experience
    id: experience
    content:
      username: admin
    design:
      date_format: 'January 2006'
      show_education: false
  - block: collection
    id: projects
    content:
      title: Projects
      text: ""
      filters:
        folders:
          - project
        # exclude_featured: false
    design:
      view: article-grid
      columns: 3
      color: '#f5f5f5'
  - block: collection
    id: teaching
    content:
      title: Teaching
      text: ""
      filters:
        folders:
          - teaching
        # exclude_featured: false
    design:
      view: article-grid
      columns: 2
  # - block: collection
  #   id: talks
  #   content:
  #     title: Recent & Upcoming Talks
  #     filters:
  #       folders:
  #         - event
  #   design:
  #     view: article-grid
  #     columns: 1
  # - block: collection
  #   id: news
  #   content:
  #     title: Recent News
  #     subtitle: ''
  #     text: ''
  #     # Page type to display. E.g. post, talk, publication...
  #     page_type: post
  #     # Choose how many pages you would like to display (0 = all pages)
  #     count: 5
  #     # Filter on criteria
  #     filters:
  #       author: ""
  #       category: ""
  #       tag: ""
  #       exclude_featured: false
  #       exclude_future: false
  #       exclude_past: false
  #       publication_type: ""
  #     # Choose how many pages you would like to offset by
  #     offset: 0
  #     # Page order: descending (desc) or ascending (asc) date.
  #     order: desc
  #   design:
  #     # Choose a layout view
  #     view: date-title-summary
  #     # Reduce spacing
  #     spacing:
  #       padding: [0, 0, 0, 0]
  - block: cta-card
    demo: true # Only display this section in the Hugo Blox Builder demo site
    content:
      title: 👉 Build your own academic website like this
      text: |-
        This site is generated by Hugo Blox Builder - the FREE, Hugo-based open source website builder trusted by 250,000+ academics like you.

        <a class="github-button" href="https://github.com/HugoBlox/hugo-blox-builder" data-color-scheme="no-preference: light; light: light; dark: dark;" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star HugoBlox/hugo-blox-builder on GitHub">Star</a>

        Easily build anything with blocks - no-code required!
        
        From landing pages, second brains, and courses to academic resumés, conferences, and tech blogs.
      button:
        text: Get Started
        url: https://hugoblox.com/templates/
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
---
