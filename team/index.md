---
title: Team
nav:
  order: 2
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

## Current Members

{% include list.html data="members" component="portrait" filter="role == 'principal-investigator' and group != 'alum'" %}
{% include list.html data="members" component="portrait" filter="role == 'postdoc' and group != 'alum'" %}
{% include list.html data="members" component="portrait" filter="role == 'phd' and group != 'alum'" %}
{% include list.html data="members" component="portrait" filter="role == 'undergrad' and group != 'alum'" %}


## Alumni
{% include list.html data="members" component="portrait" filter="group == 'alum'" %}

## Collaborators
{% include list.html data="members" component="portrait" filter="group == 'collaborator'" %}