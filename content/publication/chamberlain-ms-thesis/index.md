---
title: "Strategic Behavior and Revenue Management of Cloud Services with Reservation-based Preemption of Customer Instances"
authors:
- Jonathan Chamberlain
date: '2019-06-03T01:05:22Z'
doi: https://open.bu.edu/handle/2144/36027

# Schedule page publish date (NOT publication's date).
publishDate: '2024-05-08T16:03:01.708891Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['thesis']

# Publication name and optional abbreviated publication name.
publication: "Master's Thesis"
publication_short: ""
abstract: Cloud computing is a multi billion dollar industry, based around outsourcing the provisioning and maintenance of computing resources. In particular, Infrastructure as a Service (IaaS) enables customers to purchase virtual machines in order to run arbitrary software. IaaS customers are given the option to purchase priority access, while providers choose whether customers are preempted based on priority level. The customer decision is based on their tolerance for preemption. However, this decision is a reaction to the provider choice of preemption policy and cost to purchase priority. In this work, a non-cooperative game is developed for an IaaS system offering resource reservations. An unobservable $M|G|1$ queue with priorities is used to model customer arrivals and service. Customers receive a potential priority from the provider, and choose between purchasing a reservation for that priority and accepting the lowest priority for no additional cost. Customers select the option which minimizes their total cost of waiting. This decision is based purely on statistics, as customers cannot communicate with each other. This work presents the impact of the provider preemption policy choice on the cost customers will pay for a reserved instance. A provider may implement a policy in which no customers are preempted (NP); a policy in which all customers are subject to preemption (PR); or a policy in which only the customers not making reservations are subject to preemption (HPR). It is shown that only the service load impacts the equilibrium possibilities in the NP and PR policies, but that the service variance is also a factor under the HPR policy. These factors impact the equilibrium possibilities associated to a given reservation cost. This work shows that the cost leading to a given equilibrium is greater under the HPR policy than under the NP or PR policies, implying greater incentive to purchase reservations. From this it is proven that a provider maximizes their potential revenue from customer reservations under an HPR policy. It is shown that this holds in general and under the constraint that the reservation cost must correspond to a unique equilibrium.

tags:
- Cloud Computing
- Operations Research
- Advance Reservation
- Game Theory
featured: true

# links:
#- name: OpenBU
#  url: https://open.bu.edu/handle/2144/36027?show=full
url_pdf: https://open.bu.edu/ds2/stream/?#/documents/341503/page/1
url_code: ''
url_dataset: ''
url_poster: ''
url_project: https://sites.bu.edu/nislab/strategic-management-of-advance-reservations/
url_slides: ''
url_source: ''
url_video: ''

---