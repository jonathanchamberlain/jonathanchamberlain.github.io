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
        - statistic: "7"
          description: |
            Publications
        - statistic: "15"
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
        
        My thesis research focuses on the allocation of network resources, particularly the economic impact of user agent behavior in dynamic enviornments on priority assignment and scheduling of jobs. My interest in these areas in general, and the economics of communications systems in specific, stems from a desire to leverage resource sharing to improve access to communications networks for all. This especially holds in the internet space, where wireless connectivity is an essential pillar for expansion of high speed internet services.
        
        In addition to my published works, during my graduate student career I have been involved with Boston University’s Student Association of Graduate Engineers (SAGE) in various executive board roles, have served on a graduate student advisory committee providing feedback for graduate student focused University initiatives and proposed policy update to the Associate Provost for Graduate Affairs, and served on the organizing committee for the 10th BU CISE Graduate Student Workshop.

        **Research Focuses:** 
        Operations Research, Game Theory, Queuing Theory, Cloud Computing, and Network Security.

        **Collaborators:** 
          * [Prof. David Starobinski](https://people.bu.edu/staro/), Boston University: Thesis advisor, NISLAB co-Principal Investigator  
          * [Prof. Ari Trachtenberg](https://people.bu.edu/trachten/), Boston University: NISLAB co-Principal Investigator  
          * [Prof. Zaoxing "Alan" Liu](https://zaoxing.github.io/), University of Maryland: Computer Science professor, researcher in large-scale networked systems and security   
          * [Prof. Joel T Johnson](https://ece.osu.edu/johnson-joel), The Ohio State University: ElectroScience Labratory affilaite, researcher in remote sensing and microwave radiometry  
          * [Prof. Oran Krieger](https://okrieg.github.io/), Boston University and Mass Open Cloud Alliance: researcher focused on open cloud technologies, provided oversight to Bare Metal Marketplace project I co-mentored   
          * [Dr. Asser Tantawi](https://www.linkedin.com/in/assertantawi/), IBM Research: researcher in cloud computing technology, supervisor during summer internship  
          * [Dr. Zhenpeng Shi](https://www.linkedin.com/in/zpshi12/), Huawei: BU NISLAB Alum and collaborator on shared buy-in economics  
          * [Zeying Zhu](https://zzylol.github.io/), University of Maryland: PhD Candidate supervised by Prof. Liu, research focused on performance and security improvements to monitoring tools such as Prometheus   
          * Nicholas Brendle, The Ohio State University: Graduate student supervised by Prof. Johnson  
          * Jilin Zheng, Boston University: NISLAB Undergraduate Research Assistant, working on problems related to scaling in Kubernetes   
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
