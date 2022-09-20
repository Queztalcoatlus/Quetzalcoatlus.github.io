---
layout: post
title: "Ojibwe Verb Conjugator"
subtitle: "A conjugator API that translates conjugation parameters and the stem to conjugated verb forms"
background: '/img/posts/ojibwe-verb-conjugator/interface.png'
---

# Project Introduction

[UBC MDS-CL Program Post](https://masterdatascience.ubc.ca/why-data-science/data-stories/preserving-cultural-heritage-help-ojibwe-verb-conjugator)

# Example Conjugation
An example input to the conjugator is "INDEP+POS+PAST+onjise+4SG". The tags carry the following grammatical information:  
- +3SG: 3rd person plural
- +3PL: 3rd person plural
- +4SG: 4th person singular
- +3PL: 4th person plural

The conjugated verb form returned by the API is "gii-onijiseni". The following graph shows the underlying finite state transducer.

![vii-fst](/portfolio/img/posts/ojibwe-verb-conjugator/vii-fst.jpeg)

# Redesigned Interface
The redesigned interface calls our API with conjugation parameters and verb stem and populate the results with conjugated forms.

![Interface](/portfolio/img/posts/ojibwe-verb-conjugator/interface.png)

# API Call Flowchart
![Flowchart](/portfolio/img/posts/ojibwe-verb-conjugator/flowchart.jpg)