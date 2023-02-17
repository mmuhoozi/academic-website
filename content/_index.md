---
date: "2022-10-24"
sections:
- block: about.avatar
  content:
    text: null
    username: admin
  id: about
- block: features
  content:
    items:
    - description: 60%
      icon: r-project
      icon_pack: fab
      name: R
    - description: 80%
      icon: chart-line
      icon_pack: fas
      name: Statistics
    - description: 90%
      icon: python
      icon_pack: fas
      name: Teamwork
    title: Skills
- block: experience
  content:
    date_format: Jan 2006
    items:
    - company: Baylor Uganda
      company_logo:
      company_url: "https://www.baylor-uganda.org/"
      date_end: ""
      date_start: "2021-03-03"
      description: |2-
          Responsibilities include:

          * Analyzing
          * Data collection
          * Writing
      location: Kampala
      title: Qualitative Data Officer
    - company: Makerere University center for Health and Population Research 
      company_logo: 
      company_url: ""
      date_end: "2021-12-31"
      date_start: "2019-01-01"
      description: Coordinated, supervised and analysed data from a range of studies.
      location: Iganga
      title: Research officer
    title: Experience
  design:
    columns: "2"
- block: accomplishments
  content:
    date_format: Jan 2021
    items:
    - organization_url: https://www.rstmh.org/
      date_end: ""
      date_start: "2021-01-02"
      description: "RSTMH & National Institute for Health Research (NIHR) 2021 Small Grants Programme. The small grant supported my work for estimating the economic burden of snakebites envenoming in Eastern Uganda."
      organization: RSHTM
      title: Estimating the economic burden of Snakebites
      url: ""
    - certificate_url: 
      date_end: ""
      date_start: "2021-01-01"
      description: This was a cost effectiveness Analysis of passive and active vaccine pharmacovigilance strategies done in a population based cohort for measles rubella mass vaccination. This was thesis work done as part of masters of health services research graduate program at school of public health.
      organization: Makerere University School of Public Health
      organization_url: https://sph.mak.ac.ug/
      title: Cost effectiveness of vaccinovigilance strategies
      url: ""
    - certificate_url: 
      date_end: "2022-12-21"
      date_start: "2020-07-01"
      description: "Maternal immunization is a successful and cost-effective public health strategy. It protects pregnant women and their infants from vaccine-preventable diseases. In this project, we explored maternal knowledge, attitudes, willingness, and beliefs towards maternal immunization among pregnant women in rural Uganda."
      organization: MUCHAP
      organization_url: https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0243834 
      title: Maternal vaccination in rural Uganda
      url: ""
    subtitle: null
    title: Research projects
  design:
    columns: "2"
- block: collection
  content:
    count: 5
    filters:
      author: ""
      category: ""
      exclude_featured: false
      exclude_future: false
      exclude_past: false
      folders:
      - post
      publication_type: ""
      tag: ""
    offset: 0
    order: desc
    subtitle: ""
    text: ""
    title: Recent Posts
  design:
    columns: "2"
    view: compact
  id: posts
- block: portfolio
  content:
    buttons:
    - name: All
      tag: '*'
    - name: Data Analysis
      tag: Data Analysis
    - name: Other
      tag: Demo
    default_button_index: 0
    filters:
      folders:
      - project
    title: Projects
  design:
    columns: "1"
    flip_alt_rows: false
    view: showcase
  id: projects
- block: markdown
  content:
    subtitle: ""
    text: '{{< gallery album="demo" >}}'
    title: Gallery
  design:
    columns: "1"
- block: collection
  content:
    filters:
      featured_only: true
      folders:
      - publication
    title: Featured Publications
  design:
    columns: "2"
    view: card
  id: featured
- block: collection
  content:
    filters:
      exclude_featured: true
      folders:
      - publication
    text: |-
      {{% callout note %}}
      Quickly discover relevant content by [filtering publications](./publication/).
      {{% /callout %}}
    title: Recent Publications
  design:
    columns: "2"
    view: citation
- block: collection
  content:
    filters:
      folders:
      - event
    title: Recent & Upcoming Talks
  design:
    columns: "2"
    view: compact
  id: talks
- block: tag_cloud
  content:
    title: Popular Topics
  design:
    columns: "2"
- block: contact
  content:
    address:
      city: Kampala
      country: Uganda
      country_code: UG
    email: muhoozimusi@gmail.com 
    form:
      formspree:
        id: null
      netlify:
        captcha: false
      provider: netlify
    office_hours:
    - Saturday 10:00 to 13:00
    - Sunday 09:00 to 10:00
    phone: 256 780 982 637
    subtitle: null
    text: In case you have any questions, do not hesitate to contact me.
    title: Contact
  design:
    columns: "2"
  id: contact
title: null
type: landing
---
