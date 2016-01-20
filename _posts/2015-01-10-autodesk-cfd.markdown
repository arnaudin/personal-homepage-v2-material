---
layout: project
title:  "Autodesk CFD"
categories: professional
image: img/autodesk_cfd.png
permalink: /projects/cfd/
blurb: Autodesk CFD is a professional-level yet easy-to-use computational fluid dynamics (CFD) tool for engineers. It is founded on the philosophy of simulating early and often, and is used for fluid flow & heat transfer simulation in a wide range of industries. 
---
Autodesk CFD is a professional-level yet easy-to-use computational fluid dynamics (CFD) tool for engineers; in other words, an approachable fluid flow & heat transfer simulation tool. It is designed upon the philosophy of simulating product and architectural design performance early and often in the design cycle, which enables engineers to explore more variation virtually, before building a physical prototype. Ultimately this results in cheaper and better performing real-world designs.

I have been the UX lead for Autodesk's computational fluid dynamics (CFD) apps since 2011, supporting the following releases:

- Autodesk Simulation CFD 2012
- Autodesk Simulation CFD 2013
- Autodesk Simulation CFD 2014
- Autodesk Simulation CFD 2015
- Autodesk CFD 2016

**Autodesk CFD**
{: .meta mdl-color-text--grey-600}

![Simulation CFD]({{ site.url }}img/post-cfd-setup-ui.png)
{: .post-fullwidth-image}

Prior to that I was involved in the design, testing, and release of eight consecutive on-time quarterly releases of CFdesign simulation software.

In this role I have owned the user experience, with responsibilities including:

- User research
- Product design strategy, planning, & facilitation
- UI, interaction design, and prototyping
- Visual Design
- Front-end development
- Usability testing
- Design evangelism 

A general sampling of work follows. 

#### UI Redesign

A project illustrating a wide span of responsibilities would be a UI redesign that I led, from a menu/toolbar navigation paradigm to ribbon UI. Our hypothesis was that a well-considered ribbon UI would:

* Increase usability across all user types
* Increase learnability for new and infrequent users
* Increase familiarity of the product for existing Autodesk customers

**Classic navigation paradigm**
{: .mdl-color-text--grey-600}

![Simulation CFD]({{ site.url }}img/post-cfd-classic-menu-ui.png)
{: .post-fullwidth-image}

##### Research

Undertaking a large-scale UI redesign, we had to ask ourselves a number of questions:

* How are users interacting with the product or competing products? What is working? What isn't?
* What are the workflows and dataflows in a typical organization?
* Do we have an accurate model of our users (i.e. personas)? 
* What are the big usability issues with the product?
* Who are the stakeholders? What are the business goals?

**Ethnographic research and customer visits**
{: .mdl-color-text--grey-600}

![Onsite Customer Visit]({{ site.url }}img/post-cfd-ethnographic-s.jpg)
{: .post-fullwidth-image}

**Mapping workflows and dataflows**
{: .mdl-color-text--grey-600}

![CFD Workflow Mapping]({{ site.url }}img/post-cfd-workflow-1s.png)
{: .post-fullwidth-image}

**Creating and updating personas**
{: .mdl-color-text--grey-600}

![CFD Persona]({{ site.url }}img/post-cfd-persona-clark-s.png)
{: .post-fullwidth-image}

**Card sorting**
{: .mdl-color-text--grey-600}

![Card Sorting]({{ site.url }}img/post-cfd-card-sort-s.png)
{: .post-fullwidth-image}

##### Strategy

**Working session to arrive at design principles**
{: .mdl-color-text--grey-600}

![Design Principles]({{ site.url }}img/post-cfd-principles-s.jpg)
{: .post-fullwidth-image}

**Creating a multi-year UI plan and supporting architecture**
{: .mdl-color-text--grey-600}

![App Layout]({{ site.url }}img/post-cfd-app-layout.png)
{: .post-fullwidth-image}

##### UI and Interaction Design

**Sketching potential ribbon patterns**
{: .mdl-color-text--grey-600}

![Sketching UI Concepts]({{ site.url }}img/post-cfd-ribbon-sketch.jpg)
{: .post-fullwidth-image}

**Wireframing concepts and information architecture**
{: .mdl-color-text--grey-600}

Based on card sorting and stakeholder reviews, I began wireframing the more promising patterns. These were tested with internal experts. 

![Wireframing UI Concepts]({{ site.url }}img/post-cfd-ribbon-wire-clean.png)
{: .post-fullwidth-image}

**Prototyping**
{: .mdl-color-text--grey-600}

The quickest and most direct path forward was getting the layout into Expression Blend (more recently merged with Visual Studio). WPF allowed the front and back-end code to be separated, so I could work directly on layout, interactions, and visual design in an environment that directly mimicked what a user could see. Further, I could drop the layout files into an install and immediately have a fully working prototype. This was essential to delivering the project on time, and led to ultra-fast iteration.

![Prototyping UI Concepts]({{ site.url }}img/post-cfd-blend-proto.png)
{: .post-fullwidth-image}

**Prototyping button interactions and evaluating visuals**
{: .mdl-color-text--grey-600}

![Prototyping Interactions]({{ site.url }}img/post-cfd-blend-proto-button.png)
{: .post-fullwidth-image}

**Prototyping responsiveness and resize behavior**
{: .mdl-color-text--grey-600}

![Prototyping Interactions]({{ site.url }}img/post-cfd-resize-interactions.png)
{: .post-fullwidth-image}

##### Visual Design

**Visual design iteration**
{: .mdl-color-text--grey-600}

While a visual design language previously existed, I was responsible for icons and layout in our product.

![Design Variations]({{ site.url }}img/post-cfd-visual-ribbon-variations.png)
{: .post-vertical-image}

##### Usability Testing

The project team was small and under a tight timeline, so early usability testing was coducted with internal experts. The WPF framework allowed us to make changes almost immediately when issues were identified. 

As we entered beta we tested the more stable designs with end-users, eventually arriving at the final design (context panels not shown). For this design every test case performed better in terms of task time, and overall satisfaction and system usability scores were higher. 

![Design Variations]({{ site.url }}img/post-cfd-ribbon-tabs-rtm.png)
{: .post-fullwidth-image}

**Feedback**
{: .mdl-color-text--grey-600}

Nothing speaks like positive user feedback:

> I've used a lot of software since entering the product research field. Some were not too difficult to figure out, while others did require a bit of study to get running. Autodesk Simulation CFD 2013 is one of the easiest I've encountered.
> 
> Anyone fresh into a new piece of software can feel a bit out of sorts, but CFD is laid out in my favorite manner: a progressive ribbon. By this I mean a ribbon layout that works from left to right in the general order that parallels the standard workflows expected.
> 
> The interesting thing to note here is that I never studied how to manipulate planes in CFD. I just followed my instincts, and the tools were there. Nice job usability.
>
> John Evans, [designandmotion.com](https://designandmotion.net/autodesk/simulation-cfd-getting-up-to-speed-fast/)
