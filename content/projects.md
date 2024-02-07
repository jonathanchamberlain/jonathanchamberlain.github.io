---
title: 'Experience'
date: 2023-10-24
type: landing

design:
  # Section spacing
  spacing: '5rem'

# Page sections
sections:
  - block: projects
    content:
      title: Selected Academic Projects
      text: This is a selection of projects I have been involved with as a researcher, mentor, and student
      # Upload project images to your `assets/media/` folder and reference the filename in the `image` option
      items:
        - title: Advance Reservation Simulator
          description: |
              - Formulated queuing game to describe incentive to pay for compute resource reservations in advance.
              - Evaluated game across varying scheduling policies.
              - Constructed simulation tool utilizing Python SimPy package to model user agent purchasing decision in AR scheduling.
              - Leveraged techniques to evaluate queuing statistics for tagged \emph{ghost} user agents without impacting simulation results.
          # image: panda.png
          url: https://sites.bu.edu/nislab/strategic-management-of-advance-reservations/
        - title: Evaluation of Shared Spectrum Economics
          description: |
              - Established queuing game based model for priority upgrade purchase problem in cognitive radio settings.
              - Developed tool using Python SimPy package to simulate user agent behavior under a two tier priority system.
              - Extended SimPy tool to simulate behavior under the Citizens Broadband Radio Service (CBRS) with incumbent traffic present.
              - Supervised undergraduate students performing cognitive radio traffic monitoring experiments on CBRS frequencies.
          # image: panda.png
          url: https://sites.bu.edu/nislab/5G-shared-spectrum/
        - title: Interoperable Container Runtime
          description: |
              - Prototyped Python application for automating Docker container compliance with standard security benchmarks.
              - Implemented checks related to container image and build file benchmarks.
          # image: robot.png
          url: https://github.com/BU-NU-CLOUD-F19/Interoperable_Container_Runtime
        - title: Bare Metal Marketplace
          description: |
              - Co-mentored small team of students in Cloud Computing course working on a project to implement a Bare Metal Marketplace.
              - Guided development of software to facilitate second price auctions for allocating nodes in bare metal Open Cloud Exchange.
          # image: nlp.png
          url: https://github.com/BU-CLOUD-S20/A-Bare-Metal-Marketplace
---
