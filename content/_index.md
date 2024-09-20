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
        - statistic: "8"
          description: |
            Publications
        - statistic: "23"
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
        
        My thesis research lies in the areas of Network Economics and Security, particularly the dynamics of spectrum sharing and leveraging the intersection of technology and economics to explore user agent behavior under varying policies. My interest in these areas stems from a desire to use technology to drive policy in an informed way to enhance resource sharing and improve access to communications networks for all, while protecting incumbent users utilizing spectrum for key scientific purposes. This especially holds in the internet space, as wireless connectivity is an essential pillar for expansion of high speed internet services, which is an absolute necessity for participating in the modern economy.  
        
        In addition to my published works, during my graduate student career I have been involved with Boston University’s Student Association of Graduate Engineers (SAGE) in various executive board roles, have served on a graduate student advisory committee providing feedback for graduate student focused university initiatives and proposed policy update to the Associate Provost for Graduate Affairs, and served on the organizing committee for the 10th BU CISE Graduate Student Workshop.

        **Research Interests:** Operations Research, Game Theory, Queuing Theory, Decision Theory, Wireless Communications, Spectrum Allocation Policy, Passive-Active User Interactions, Cloud Computing, and Network Security.
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
