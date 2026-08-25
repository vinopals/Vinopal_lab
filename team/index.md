---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

We are a research group based at the Centre for Nanomaterials and Biotechnology (CENAB), Faculty of Science, Jan Evangelista Purkyně University in Ústí nad Labem.  
Our research primarily focuses on the fascinating biology of tardigrades.
We also have an expertise in various aspects of the cytoskeleton, neuroscience, cell and molecular biology, and biochemistry.

{% include section.html %}

## Principal Investigator

{% include list.html data="members" component="portrait" filter="role == 'principal-investigator'" %}

## Postdocs

{% include list.html data="members" component="portrait" filter="role == 'postdoc'" %}

## PhD Students

{% include list.html data="members" component="portrait" filter="role == 'phd'" %}

## Master Students

{% include list.html data="members" component="portrait" filter="role == 'master'" %}

## Bachelor Students

{% include list.html data="members" component="portrait" filter="role == 'bachelor'" %}

## Internal Collaborators (CENAB)

{% include list.html data="members" component="portrait" filter="role == 'internal-collaborator'" %}

{% include section.html %}

## Alumni

{% include list.html data="members" component="portrait" filter="role == 'alumni'" %}
