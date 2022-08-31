---
layout: single
permalink: /
author_profile: true
---

I'm a graduate student working with Julien Emile-Geay in the [Climate Dynamics Lab](https://climdyn.usc.edu/) at USC. My work is primarily concerned with using time series analysis to improve our understanding the history of abrupt events and dynamical shifts in Earth's climate. More specifically, I'm interested in applying tools from non-linear time series analysis and machine learning to paleoclimatoligcal questions. 

Currently my research is focused on automatically identifying "events" in paleoclimate time series records, with the intention of using clustering algorithms to constrain the spatial distribution of synchronous events. There are two main ways of we are approaching the definition of what an event is:

* By building an event taxonomy from well known paleoclimate events such as the Younger Dryas, Dansgaard-Oeschger events, Heinrich events, 8.2ka event, and others. The events described by our taxonomy will be used to create a corpus of synthetic paleoclimate events. This corpus will be then used to train a machine learning model to identify events in paleoclimate time series.
* By leveraging methods based on phase space reconstruction to examine regime changes in the systems underlying the formation of paleoclimate time series. In this case, transitions between regimes will be labelled as events.