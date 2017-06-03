---
layout: project
title:  "Autodesk CFD"
categories: professional
image: img/autodesk_cfd.png
permalink: /projects/cfd/
blurb: Autodesk CFD is a professional yet easy-to-use computational fluid dynamics (CFD) tool for engineers, founded on the philosophy of simulating designs early and often.
---
Autodesk CFD is a professional yet easy-to-use computational fluid dynamics (CFD) tool for engineers; in other words, an approachable fluid flow & heat transfer simulation tool. It is used to simulate everything from pumps & valves, to electronics cooling, to aero & hydrodynamics, to HVAC systems in buildings.

As a product, our CFD is designed to embrace the belief that simulating design performance virtually, early, and often in the design cycle will result in cheaper and better performing real-world designs, with a faster time to market.

#### Role

I have been the UX Design Lead for Autodesk's computational fluid dynamics (CFD) apps since 2011, supporting the following successful releases:

- Autodesk Simulation CFD 2012
- Autodesk Simulation CFD 2013
- Autodesk Simulation CFD 2014
- Autodesk Simulation CFD 2015
- Autodesk CFD 2016
- Autodesk CFD 2017

**Autodesk CFD**
{: .meta mdl-color-text--grey-600}

![Simulation CFD]({{ site.url }}/img/post-cfd-setup-ui.png)
{: .post-fullwidth-image}

In this role I have owned user experience and product design, supporting a majority of new development. Responsibilities include:

- User research
- Product design strategy, planning, & facilitation
- UI, interaction design, and prototyping
- Visual Design
- Front-end development
- Usability testing
- Design evangelism and cultural evolution

Prior to this work at Autodesk, I was involved in the design, testing, and release of eight consecutive on-time quarterly releases of CFdesign simulation software.

An example of a large scale UI redesign follows. 

#### UI Redesign

This full UI redesign from a menu/toolbar to ribbon interface is representative of a wide span of responsibilities. 

In addition to aligning with the Autodesk brand, our hypothesis was that a ribbon UI could:

* Increase usability across all user types (e.g. daily and infrequent)
* Increase learnability & discoverability for new and infrequent users (most common persona)
* Increase familiarity, and thus ease of adoption, for existing Autodesk customers who could benefit from adding simulation to their design workflows

**Classic menu/toolbar layout**
{: .mdl-color-text--grey-600}

![Simulation CFD]({{ site.url }}/img/post-cfd-classic-menu-ui.png)
{: .post-fullwidth-image}

##### Research

Before undertaking this potentially disruptive redesign, we had to ask a number of questions and choose appropriate methods.

* What mental model are users coming in with? What are the patterns among users?
* How are users interacting with our product or similar products? What is working? What isn't?
* How often are commands used? In what order?
* What are the workflows and dataflows in a typical organization?
* What are usability issues with the existing product?
* Who are the stakeholders? What are the business goals?

**Ethnographic research**
{: .mdl-color-text--grey-600}

![Onsite Customer Visit]({{ site.url }}/img/post-cfd-ethnographic-s.jpg)
{: .post-fullwidth-image}

**Workflows and dataflows**
{: .mdl-color-text--grey-600}

![CFD Workflow Mapping]({{ site.url }}/img/post-cfd-workflow-1s.png)
{: .post-fullwidth-image}

**Personas**
{: .mdl-color-text--grey-600}

![CFD Persona]({{ site.url }}/img/post-cfd-persona-clark-s.png)
{: .post-fullwidth-image}

**Card sorting**
{: .mdl-color-text--grey-600}

![Card Sorting]({{ site.url }}/img/post-cfd-card-sort-s.png)
{: .post-fullwidth-image}

##### Strategy

**Design principles**

A reminder to all in our "war room."

{: .mdl-color-text--grey-600}

![Design Principles]({{ site.url }}/img/post-cfd-principles-s.jpg)
{: .post-fullwidth-image}

**UI component architecture**
{: .mdl-color-text--grey-600}

![App Layout]({{ site.url }}/img/post-cfd-app-layout.png)
{: .post-fullwidth-image}

##### UI and Interaction Design

**Start low fidelity, explore broad concepts within the constraints**
{: .mdl-color-text--grey-600}

![Sketching UI Concepts]({{ site.url }}/img/post-cfd-ribbon-sketch.jpg)
{: .post-fullwidth-image}

Based on card sorting and stakeholder reviews, refining the more promising designs and validating with internal experts...

**Wireframes and Information Architecture**
{: .mdl-color-text--grey-600}

![Wireframing UI Concepts]({{ site.url }}/img/post-cfd-ribbon-wire-clean.png)
{: .post-fullwidth-image}

The next step was to create a prototype that could be rapidly tested and updated in an iterative fashion. With the chosen UI framework, I was able to work directly with the front-end code to create and modify the prototype which could then be tested and fed directly into the production pipeline. 

**Prototyping in Blend and Visual Studio**
{: .mdl-color-text--grey-600}

![Prototyping UI Concepts]({{ site.url }}/img/post-cfd-blend-proto.png)
{: .post-fullwidth-image}

**Prototyping interactions and evaluating visuals**
{: .mdl-color-text--grey-600}

![Prototyping Interactions]({{ site.url }}/img/post-cfd-blend-proto-button.png)
{: .post-fullwidth-image}

**Prototyping responsiveness and resize interactions**
{: .mdl-color-text--grey-600}

![Prototyping Interactions]({{ site.url }}/img/post-cfd-resize-interactions.png)
{: .post-fullwidth-image}

##### Visual Design

While a company-wide visual design system existed and some pieces could be re-used, I was ultimately responsible for icons and layout in our product.

**Visual design iteration**
{: .mdl-color-text--grey-600}

![Design Variations]({{ site.url }}/img/post-cfd-visual-ribbon-variations.png)
{: .post-vertical-image}

##### Usability Testing

Early usability testing was conducted with internal experts. The WPF framework allowed us to make changes almost immediately when issues were identified. 

As we neared beta we tested the more stable designs with users, eventually arriving at the final design (colored context panels not shown). For this design, every test case performed better than the previous menu/toolbar version in terms of task time; overall satisfaction and system usability scores were also higher. 

![Design Variations]({{ site.url }}/img/post-cfd-ribbon-tabs-rtm.png)
{: .post-fullwidth-image}

**Feedback**
{: .mdl-color-text--grey-600}

Finally, nothing is as satisfying as positive user feedback:

> I've used a lot of software since entering the product research field. Some were not too difficult to figure out, while others did require a bit of study to get running. Autodesk Simulation CFD 2013 is one of the easiest I've encountered.
> 
> Anyone fresh into a new piece of software can feel a bit out of sorts, but CFD is laid out in my favorite manner: a progressive ribbon. By this I mean a ribbon layout that works from left to right in the general order that parallels the standard workflows expected.
> 
> The interesting thing to note here is that I never studied how to manipulate planes in CFD. I just followed my instincts, and the tools were there. Nice job usability.
>
> John Evans, [designandmotion.com](https://designandmotion.net/autodesk/simulation-cfd-getting-up-to-speed-fast/)

#### Additional work

This particular project serves as a broad example of my approach and skillset. I have designed a majority of the new and redesigned features in the products listed above, so am happy to answer additional questions. For a list of what's new in each release, see the Autodesk Knowledge Network:

- [What's New in Autodesk® CFD 2017](https://knowledge.autodesk.com/support/cfd/learn-explore/caas/CloudHelp/cloudhelp/2017/ENU/SimCFD-WhatsNew/files/GUID-E68DA961-6B90-41D7-AFA0-FD771EDB60F9-htm.html)
- [What's New in Autodesk® CFD 2016](https://knowledge.autodesk.com/support/cfd/learn-explore/caas/CloudHelp/cloudhelp/2017/ENU/SimCFD-WhatsNew/files/GUID-A27F10AE-67C6-45CB-959F-0F2074F4D131-htm.html)
- [What's New in Autodesk® Simulation CFD 2015](https://knowledge.autodesk.com/support/cfd/learn-explore/caas/CloudHelp/cloudhelp/2017/ENU/SimCFD-WhatsNew/files/GUID-2426C8BE-99E3-4775-9691-6D788E46F365-htm.html)
