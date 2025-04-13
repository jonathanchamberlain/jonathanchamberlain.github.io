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
      title: 'I am a Computer Engineering and Operations Research investigator, specializing in techno-policy and economic aspects of Dynamic Spectrum Access planning'
      subtitle: ''
      text: |-

        My research interests lie in how the intersections between Network Systems and Security drive policy decisions within wireless spaces. With the interconnectivity of the modern world, access to wireless bandwidth is an essential pillar for ensuring access for rural communities to applications requiring broadband-class speeds, in addition to the various Smart City technologies ranging from Positive Train Control to Vehicle-to-Vehicle/Vehicle-to-Grid communication with to improve traffic flows and reduce congestion. Considerations of use however involve delicate balancing acts, carefully accounting for essential _Public Interest_ scientific uses: these include, but are hardly limited to, the Earth Exploration Satellite Service-passive remote sensors for weather forecasting and climate mointoring. Additionally, technology such as Mobile Edge Computing introduce side channels for attacks on cloud technologies to be executed such as Economic Denial of Sustainability.
        
        My published academic works as a member of BU NISLAB include a number of works published in collaboration with a team from the Ohio State ElectroScience Labortory establishing the economic feasibilty of sharing for wholesale commerical markets yielding priority to mission critical EESS-passive radiometers. This includes a 2024 IEEE DySpan paper which received the Runner-Up accoldate for Best Paper on the Policy Track. I also have engaged in active collaboration with the FROOT Lab at the University of Maryland, College Park on problems related to monitoring of cloud computing clusters in mobile networks. My particular focus has been on formalizing models on scalable container networks operating in Mobile Edge enviornments being targeted by the EDoS attack. This collaboration has yielded one accepted SIGMETRICS paper thus far. 
        
        As a graduate student I was involved in multiple service roles, including serving on the executive board of the Boston University Student Association of Graduate Engineers in various roles, membering on an advisory committee providing feedback for university initiatives and proposed policy updates to the Associate Provost for Graduate Affairs, and co-organized the 10th and 11th editions of the BU Center for Information and Systems Engineering Graduate Student Workshops in 2024-25. I also had the privalege of participating in the 2025 NSF NeTS Early Career Investigators workshop.

        **Research Interests:** Queuing Games, Wireless Communications, Dynamic Spectrum Access and Coexistence with Passive Users, Wide Area Networks, Mobile Edge Computing, Scalable Networks, Systems Security, Public Policy
        
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
