---
title: 'Projects'
permalink: /projects/
layout: splash

feature_row:
  - image_path: ./assets/images/pyleoclim_logo.png
    alt: 'Pyleoclim Logo'
    title: 'Pyleoclim'
    excerpt: 'Pyleoclim is a Python package designed for the analysis of paleoclimate data.'
    url: 'https://github.com/LinkedEarth/Pyleoclim_util'
    btn_label: "Learn More"
    btn_class: "btn--primary"

feature_row2:
  - image_path: ./assets/images/bifurcation_diagram.png
    alt: 'Bifurcation Diagram'
    title: 'Ammonyte'
    excerpt: 'Ammonyte is a python package designed for the non-linear timeseries analysis of paleoclimate data. It is an offshoot of the Pyleoclim python package.'
    url: "https://github.com/alexkjames/Ammonyte"
    btn_label: "Learn More"
    btn_class: "btn--primary"

feature_row3:
  - image_path: ./assets/images/event.png
    alt: 'Event Series'
    title: 'Paleoclimate Event Taxonomy'
    excerpt: 'The paleoclimate event taxonomy is a collection of paleoclimate timeseries with labelled events.'
    url: "https://github.com/alexkjames/Paleoclimate_Event_Taxonomy"
    btn_label: "Learn More"
    btn_class: "btn--primary"

---

{% include feature_row id="feature_row" type="left" %}

{% include feature_row id="feature_row2" type="right" %}

{% include feature_row id="feature_row3" type="left" %}