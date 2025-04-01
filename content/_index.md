---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: resume-biography
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text:
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: Depositphotos_17624521_XL.jpg
          filters:
            brightness: 0.4
          size: cover
          position: center
          parallax: false
  - block: stats
    content:
      items:
        - statistic: "10"
          description: |
            Publications
        - statistic: "29"
          description: |
            Citations
        - statistic: "3"
          description: |
            h-index
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
      # Reduce spacing
      spacing:
        padding: [0, 0, 0, 0]
  - block: markdown
    content:
      title: 'I am a PhD candidate engaging in research on the economics of cloud computing and cognitive radio networks'
      subtitle: ''
      text: |-
        
        My research interests lie in the intersection between Network Systems and Security, especially wireless systems; the economic impacts of Dynamic Spectrum Co-Existence, and the policy implications in making different design choices. In particular, within the internet space wireless connectivity is an essential pillar for expansion of high speed internet service and ensuring that communities are not left behind due to accidents of geography and/or topography. However, considerations of uses such as remote sensing for climatology monitoring or radio astronomy for space science research make equitable sharing a delicate balancing act. My published works include a Policy Track Runner-Up award for Best Paper at the 2024 IEEE DySpan conference for preliminary work done in concert with collaborators at the Ohio State ElectroScience Laboratory establishing the economic feasibility of such sharing for wholesale commercial markets yielding priority to mission critical Earth Exploration Satellite Service-passive radiometers. 
        
        Additionally I have been working with the research team at the FROOT Lab at the University of Maryland, College Park on problems related to monitoring of cloud computing clusters in mobile networks, with an eye towards security applications. Specifically, looking at new ways to model attacks on scalable container networks where the attacker objective is to force the provider to consume resources in an excessive manner via Economic Denial of Sustainability attacks.

        In addition to my published works, during my graduate student career I have been involved with Boston University’s Student Association of Graduate Engineers (SAGE) in various executive board roles, have served on a graduate student advisory committee providing feedback for graduate student focused university initiatives and proposed policy update to the Associate Provost for Graduate Affairs, and served on the organizing committee for the 10th and 11th BU CISE Graduate Student Workshops in 2024-25.

        **Research Interests:** Queuing Theory, Game Theory, Wireless Communications, Spectrum Allocation and Dynamic Spectrum Co-Existence, Passive-Active User Interactions, Wide Area Networks, Mobile Edge Computing, Scalable Networks, Systems Security, Public Policy
        
    design:
      columns: '1'
  - block: collection
    content:
      title: Recent News
      subtitle: ''
      text: ''
      # Page type to display. E.g. post, talk, publication...
      page_type: post
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: date-title-summary
      # Reduce spacing
      spacing:
        padding: [0, 0, 0, 0]
---
