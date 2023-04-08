---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 40

title: Experience
subtitle:

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: System Analyst/Programmer 3
    company: University of Washington
    company_url: 'https://uw.edu'
    # company_logo: org-gc
    location: Tacoma, Washington
    date_start: '2023-03-16'
    date_end: ''
    description: |2-
      * Developing and facilitating training on Docker image creation and containerized workflows using Biodepot-workflow-builder (Bwb)
      * Automation of various tasks using shell scripts and containerized microservices

  - title: Research Assistant
    company: University of Washington
    company_url: 'https://uw.edu'
    # company_logo: org-gc
    location: Tacoma, Washington
    date_start: '2023-01-01'
    date_end: '2023-03-15'
    description: |2-
      * Developed Docker containerized workflow and tools for gathering performance metrics to allow for cost analysis/budgeting of cloud infrastructure.
      * Developed Terraform module and Ansible playbook to provision and configure infrastructure on IBM Cloud.

  - title: DevOps Engineer
    company: BioDepot LLC
    company_url: 'https://biodepot.io'
    # company_logo: org-gc
    location: Seattle, Washington
    date_start: '2021-09-01'
    date_end: '2022-12-31'
    description: |2-
      * Developed web application with a Python/Flask back-end and React front-end to rapidly provision AWS EC2 instances for running Docker containerized bioinformatics workflows.
      * Developed Terraform module incorporating Ansible to provision and configure remote servers on AWS.
      * Developed GitHub Actions for automating release of Docker images.

  - title: Software Engineering Intern
    company: BioDepot LLC
    company_url: 'https://biodepot.io'
    # company_logo: org-gc
    location: Seattle, Washington
    date_start: '2020-10-01'
    date_end: '2021-09-01'
    description: '* Developed bioinformatics workflows utilizing Docker containers and shell scripts.'

  - title: Tutor
    company: Tacoma Community College
    company_url: 'https://tacomacc.edu/'
    # company_logo: org-gc
    location: Tacoma, Washington
    date_start: '2018-09-01'
    date_end: '2023-03-15'
    description: '* Providing drop-in tutoring for algebra, trigonometry, calculus, and computer science.'
        
  - title: Hardware Test Engineer
    company: Extreme Engineering Solutions Inc
    company_url: 'https://www.xes-inc.com'
    # company_logo: org-x
    location: Verona, Wisconsin
    date_start: '2010-12-01'
    date_end: '2017-02-01'
    description: |2-
      * Developed in-house test framework enabling rapid development of functional and programming processing utilizing Linux, shell scripts, terminal macros, and batch scripts.
      * Primary trainer on test procedure software and documentation development.
      * Created and revised a total of 587 acceptance test procedures.

  - title: Electronics Technican
    company: Extreme Engineering Solutions Inc
    company_url: 'https://www.xes-inc.com'
    # company_logo: org-x
    location: Verona, Wisconsin
    date_start: '2006-10-01'
    date_end: '2010-12-01'
    description: |2-
      * Programmed, tested, and troubleshooted single board computers (SBC) and systems.
      * Electronic debug and repair at the component level using microscopes, oscilloscopes, and multimeters.

design:
  columns: '2'
---
