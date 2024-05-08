---
title: 'Projects'
date: 2023-10-24
type: landing

design:
  # Section spacing
  spacing: '20rem'
  view: showcase
  flip_alt_rows: true
  


# Page sections
sections:
  - block: resume-projects
    content:
      title: Selected Projects
      text: These are a selection of the academic projects I have been involved with as part of my graduate studies.
      # Upload project images to your `assets/media/` folder and reference the filename in the `image` option
      items:
        - title: Facilitating Novel Modalities for Spectrum Sharing between Earth-Observing Microwave Radiometers and Commercial Users
          description: Working with collaborators at Ohio State's [ElectroScience Labratory](https://electroscience.osu.edu/), this interdisciplinary project seeks to establish sharing frameworks in the high band (beyond 6 GHz) portions of wireless spectrum. I have performed statistical analyses of [radiometer trace data](https://github.com/nislab/passive-radiometer-trace-data) to determine available transmission windows for commercial use, establishing a joint queuing- and game-theoretic model covering a variety of scenarios for customer behavior and sharing frameworks.
          image: icons/satellite-solid
          url: https://www.nsf.gov/awardsearch/showAward.do?AwardNumber=2229104
        - title: The Interplay of Markets and Security in 5G Shared Spectrum Services 
          description:  This project aims to address the intertwiining of economics and security frameworks in areas of spectrum where flexible sharing is possible, such as the mid-band 3.5 GHz portion governed by the [Citizens Broadband Radio Service (CBRS)](https://www.fcc.gov/wireless/bureau-divisions/mobility-division/35-ghz-band/35-ghz-band-overview). I established a joint queuing- and game-theoreitc based model for the priority upgrade purchase problem in cognitive radio settings, and developed tools using Python's SimPy package to simulate user agent behavior under both a two tier priority system and CBRS-type systems with incumbent traffic present. I also have supervised undergradate students' work perofrming radio traffic monitoring experiments, as well as had the opportunity to present my work directly to the CTO team of a CBRS Spectrum Access Administrator.
          image: icons/tower-cell-solid
          url: https://sites.bu.edu/nislab/5G-shared-spectrum/
        - title: Strategic Management of Advance Reservations in Cloud and Network Services
          description: This project investigates the impact of advance reservation of resources by users in cloud systems. I formulated a queuing game model to describe the incentive to pay for compute resource reservations in advance, and evaluated the game across varying preemption scheduling policies based on reservation priority. Using SimPy, I constructed a simulation tool to model user agent purchasing decisions, leveraging techniques to evaluate queue statistics for tagged ghost user agents to determine system behavior without impacting the results.
          image: icons/network-wired-solid
          url: https://sites.bu.edu/nislab/strategic-management-of-advance-reservations/
---
