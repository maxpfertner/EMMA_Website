---
title: Temporal accessibility of workplaces by time of day
author: Maximilian Pfertner
date: '2020-06-26'
slug: changes-in-accessibility-during-a-workday
categories: []
tags:
  - r
  - opentripplanner
  - methodology
  - isochrone
  - accessibility
  - workplace
  - temporal
subtitle: ''
summary: ''
authors: []
lastmod: '2020-06-26T11:41:32+02:00'
featured: no
image:
  caption: ''
  focal_point: ''
  preview_only: no
projects: []
---

The release of the official nation-wide GTFS dataset for Germany has been a game changer for all kinds of public transport analysis recently. Within EMMA, we use a filtered version of this dataset for the region in OpenTripPlanner. The timetable-based accuracy of the data allows a very detailed look at the changes in accessibility over time due to variations in the public transport supply. We would like to illustrate this using TUM's main campus in the center of Munich and the Garching Campus, which is north of the City, connected with a subway line.

{{< figure src="/post/img/2020-06-26_stammgelaende.gif" title="TUM Stammgelänge in Maxvorstadt" lightbox="true" >}}

The blue area shows the area from where you could reach the TUM campus within 30 minute with public transport at the given time of day (on a Wednesday). You can see some headway-related flickering during the day, but between the early morning until the late evening, the accessibility is relatively stable. A dense network of multiple public transport lines, from buses, to trams, subways, and regional trains ("S-Bahn") ensures a good accessibility of this location during most of the day. 
How does a similar map look for the example of Garching?

{{< figure src="/post/img/2020-06-26_garching.gif" title="TUM Campus Garching-Hochbrück" lightbox="true" >}}

As you might have expected, the isochrones are generally smaller, and much more narrow in the North-South corridor. This is where the subway runs, the dominating public transport supply in the area. The effect of some bus lines is visible with the "islands" that appear on the map from time to time. Interestingly, there are some periods at night where there is no public transport at all on the campus.  

How can we quantify and visualize these results?  

The following graph shows the number of people who can reach the locations by time of day - again within 30 minutes of public transport (and a max. walk distance of 800m).

{{< figure src="/post/img/2020-06-26_graph.png" title="Comparison of both locations" lightbox="true" >}}

The striking difference in absolute numbers is not unexpected, given the locations. Some observations beyond this:
- The night shutdown from 2:00 - 5:00 is affecting Garching more than the main campus, where some supply is available 24/7.
- You can identify (in the main campus mainly) the increased supply during the peak hours (roughly 7:00- 9:00  and 16:00 - 19:00)  

What does this imply for workplace locations?

First, one has to understand that on the Garching Campus, there are mainly university buildings and other research institutions, but no housing at all. Thus, effects like the complete shutdown of public transport at night does not have a negative impact on this location at the moment. However, it does show that in the case of structural changes to the locations, adaptions will be necessary. 
Within EMMA, we can repeat a similar analysis in more depth e.g. for workplace locations, where a 24/7 accessibility is important (such as hospitals, factories with night shifts, ...) and generate recommendations for the further development. Stay tuned! 

- 





