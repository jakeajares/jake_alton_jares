---
date: "2022-10-24"
sections:
- block: about.biography
  content:
    title: About me
    username: admin
  id: about
#- block: collection
#  content:
#    filters:
#      featured_only: true
#      folders:
#      - publication
#    title: Featured Publications
#  design:
#    columns: "2"
#    view: card
#  id: featured
- block: collection
  content:
    filters:
      exclude_featured: true
      folders:
      - publication
    title: Recent Publications
  design:
    columns: "2"
    view: citation
  id: recent_pubs
- block: contact
  content:
    autolink: true
    email: jjares@stanford.edu
    text: ""
    title: Contact
  design:
    columns: "2"
  id: contact
title: null
type: landing
---
