---
layout: home
---

# Chips & Compilers Symposium at MLSys '22

Modern machine learning systems call for scalable and efficient solutions to both gigantic model training and flexible model inference.
This requires joint design and optimization between hardware and software to take full advantage of the provided resource.
We have observed active development in this field in the past few years, ranging from machine learning specific hardware and compiler, to customized optimization towards modern machine learning workloads.
This symposium aims to bring together experts from the field of computer architecture and compilers to share first-hand experiences, lessons, and best practices, of designing ML workload specific chips and compilers.
Like last year, the symposium will consist of invited talks by domain experts from both academia and industry.



## Speakers

{% assign speakers = site.staffers | where: 'role', 'Speaker' %}
{% for staffer in speakers %}
{{ staffer }}
{% endfor %}

<div style="clear: both;"></div>

## Organizers

{% assign organizers = site.staffers | where: 'role', 'Organizer' %}
{% for staffer in organizers %}
{{ staffer }}
{% endfor %}

<div style="clear: both;"></div>

## Agenda

{% for module in site.modules %}
{{ module }}
{% endfor %}

## See also

- [MLSys 2022 Main Website](https://mlsys.org/)
- [Chips and Compilers Symposium 2021](https://chips-compilers-mlsys-21.github.io/)
