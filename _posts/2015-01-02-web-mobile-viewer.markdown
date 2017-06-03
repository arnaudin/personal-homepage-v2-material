---
layout: project
title:  "Web & Mobile Viewer"
categories: professional
image: img/post-simulation-viewer-hero.jpg
permalink: /projects/simulation-viewer/
blurb: Making the simulation workflow more connected, collaborative, and interactive.
---
The design feedback loop provided by simulation is a part of a collaborative and interactive process. The Simulation Viewer is a step towards making results broadly sharable and available anywhere, along with additional collaboration features such as annotation and commenting. 

#### Problem

A research team was formed to test the hypothesis that simulation collaboration workflows had not kept pace with the increasing and cross-functional role that simulation plays throughout the product design process. Technology in the workplace had also been rapidly evolving, yet we were not leveraging potential web and mobile capabilities. 

#### Approach

The research team consisted of two researchers, and three designers from different simulation products. We would travel to a variety of customer sites to interview and observe users in their workplaces. Being the [CFD]({% post_url 2015-01-10-autodesk-cfd %}) lead I accompanied the researchers on visits to those customers, and assisted with interviews. Through dozens of interactions, we were able to identify patterns to map common and specific collaboration workflows. We also developed a new set of three personas with results collaboration in mind.

#### Solution

With our understanding of the current state, we identified gaps and opportunities for improvements or new products. At a high level my focus shifted to addressing the needs of making analysis approachable to non-technical stakeholders, providing connected access to project collaboration tools, and allowing [remote monitoring for simulations]({% post_url 2015-01-04-mobile-job-monitor %}). 

One of the most common workflows we observed was sharing screenshots, videos, or 3D visualizations of simulation results. This was inconsistent, fragmented, and become more painful as the information density increased. The following highlights show a web and mobile results viewer that enables an engineer to quickly and easily share 3D simulation visualizations with clients and colleagues. 

I designed UI, interactions, and visual components for the simulation layer of the viewer, which was built on top of existing Autodesk 3D viewing technology. 

##### Vision

![Web Vision Story]({{ site.url }}/img/post-viewer-vision-web.png)
{: .post-fullwidth-image}

![Mobile Vision Story]({{ site.url }}/img/post-viewer-vision-mobile.png)
{: .post-fullwidth-image}

![Tablet Vision Story]({{ site.url }}/img/post-viewer-vision-tablet.png)
{: .post-fullwidth-image}

##### Design

**Browser-based Viewer** 
{: .mdl-color-text--grey-600}

![Browser-based Simulation Viewer]({{ site.url }}/img/post-viewer-web.png)
{: .post-fullwidth-image}

**Mobile Viewer** 
{: .mdl-color-text--grey-600}

![Mobile Simulation Viewer]({{ site.url }}/img/post-viewer-mobile-legend.png)
{: .post-vertical-image}

**Simulation legend** 
<br>
Exploring visual styles for use in the viewer
{: .mdl-color-text--grey-600}

![Legend Visual Design Alternatives]({{ site.url }}/img/post-viewer-legend-alternatives.png)
{: .post-fullwidth-image}

Exploring visual styles in context
{: .mdl-color-text--grey-600}

![Legend Visual Design Alternatives]({{ site.url }}/img/post-viewer-legend-context.png)
{: .post-fullwidth-image}

##### Outcome

Our work on this project was integrated into the A360 web viewer, A360 mobile app, and Autodesk Labs Sim 360 project.
