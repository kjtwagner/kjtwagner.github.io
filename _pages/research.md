---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

## Improved Lattice and Coordinate Choices for Cross-Correlation Search for Sco X-1

Scorpius X-1 is a low-mass x-ray binary (LMXB) source that is rapidly spinning and is a promising source for continuous gravitational wave emission. As a neutron star with a low-mass companion, it's high x-ray emission indicates a high accretion rate. Resulting nonaxisymmetric deformations can lead to gravitational wave emission at twice the rotation frequency of the star. This source is currently being observed by detectors at LIGO, Virgo, and KAGRA. The signal received depends on the parameters of the system, and the sensitivity of a search for the signal in the data depends on a use of accurate values for those parameters. The search becomes less sensitive if incorrect values are used.

The fractional loss of signal-to-noise ratio can be written as a distance metric on parameter space, which we divide into small sections that we can assume flat space and constant metric values. This allows us to place a lattice over sections of parameter space, where points on the lattice are templates that search the space for a signal at discrete points. This then becomes the sphere covering problem - we need to ensure that all points in parameter space are covered, but the use of additional templates causes computing cost to increase.

I have worked to find three different ways to decrease the number of templates needed to cover the parameter space while maintaining search sensitivity. *Stay tuned for the paper coming soon!*

### References
<https://arxiv.org/pdf/1504.05890.pdf>
