---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'The ICU Census: The Critical Care Management System for an Oncologic ICU'
subtitle: ''
summary: ''
authors:
- Thomas A. Nahass
- Yekaterina D. Tayban
- Gleb Kirnicinii
- Neil A Halpern
tags: []
categories: []
date: -01-01
lastmod: 2023-01-25T10:50:10-05:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2023-01-25T15:50:10.486037Z'
publication_types:
- '0'
abstract: Introduction Management of the various aspects of critically ill patients
  requires precision and attention to detail. The ICU Census (``Census'') is a custom
  database system for the management of logistical, clinical, and reporting mechanisms
  as they relate to patient care in a specialized oncologic medical-surgical ICU.  We
  report the design and implementation of the Census. Design The Census is a MS SQL
  backend with an ASP.NET frontend, with various .NET windows service connections
  to a multitude of interfaces. ICU admissions, consults, rapid responses, inter-hospital
  ICU transfers are tracked and recorded through the standardized forms that can then
  be viewed in aggregate through the ICU Greaseboard located on screens throughout
  the ICU and any computer logged into the secured network. The data that is collected
  during a patient's ICU stay ranges from procedures or interventions to novel clinical
  trial therapeutics for a patient's cancer care. These items are retrospectively
  reviewed for research on critically ill cancer patients.  Reporting Each morning,
  an aggregated rounding report for each ICU team is automatically produced as a PDF
  document and sent to the ICU team. This report organizes the lab, medication, and
  procedural data by organ systems for each patient. There are multiple ICU, respiratory
  therapy, and pharmacy workflows that utilize the Census to aggregate data in Tableau
  Dashboards. Additional ICU reports for mortality, admission and discharge data,
  demographic data, and procedures can be easily produced.  Conclusion The management
  of patient flow coordination and critically ill patients can be effectively managed
  through the ICU Census. The automation of the manual inputs is underway and we plan
  to release the design as open source for other ICUs that are interested in the design.
publication: ''
---
