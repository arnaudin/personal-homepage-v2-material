---
layout: project
title:  "Autodesk CFD"
categories: professional
image: img/autodesk_cfd.png
permalink: /projects/cfd/
blurb: Autodesk CFD is a professional-level yet easy-to-use computational fluid dynamics (CFD) tool for engineers. It is founded on the philosophy of simulating early and often, and is used for fluid flow & heat transfer simulation in a wide range of industries. 
---
Autodesk CFD is a professional-level yet easy-to-use computational fluid dynamics (CFD) tool for engineers; in other words, an approachable fluid flow & heat transfer simulation tool. It is designed upon the philosophy of simulating product and architectural design performance early and often in the design cycle, which enables engineers to explore more variation virtually, before building a physical prototype. Ultimately this results in cheaper and better performing real-world designs.

#### Role

I have been the UX Design lead for Autodesk's computational fluid dynamics (CFD) apps since 2011, supporting the following releases:

- Autodesk Simulation CFD 2012
- Autodesk Simulation CFD 2013
- Autodesk Simulation CFD 2014
- Autodesk Simulation CFD 2015
- Autodesk CFD 2016

**Autodesk CFD**
{: .meta mdl-color-text--grey-600}

![Simulation CFD]({{ site.url }}img/post-cfd-setup-ui.png)
{: .post-fullwidth-image}

In this role I have owned the user experience, with responsibilities including:

- User research
- Product design strategy, planning, & facilitation
- UI, interaction design, and prototyping
- Visual Design
- Front-end development
- Usability testing
- Design evangelism 

Prior, I was involved in the design, testing, and release of eight consecutive on-time quarterly releases of CFdesign simulation software.

I have supported a majority of new features over this time. An example of a large scale UI redesign follows. 

#### UI Redesign

This full UI redesign, from a menu/toolbar navigation paradigm to ribbon UI, represents a wide span of responsibilities. 

Our hypothesis was that a well-considered ribbon UI would:

* Increase usability across all user types
* Increase learnability & discoverability for new and infrequent users (a common persona in simulation)
* Increase familiarity and thus adoption for existing Autodesk customers who could benefit from adding simulation to their workflow

**Classic navigation paradigm, Simulation CFD 2013**
{: .mdl-color-text--grey-600}

![Simulation CFD]({{ site.url }}img/post-cfd-classic-menu-ui.png)
{: .post-fullwidth-image}

##### Research

Undertaking a large-scale UI redesign, we had to ask ourselves a number of questions, and choose the appropriate methods.

* How are users interacting with our product or similar products? What is working? What isn't?
* How often are commands used? In what order?
* What are the workflows and dataflows in a typical organization?
* Do we have an accurate model of our users (i.e. personas)? 
* What are the big usability issues with the product?
* Who are the stakeholders? What are the business goals?

**Ethnographic research**
{: .mdl-color-text--grey-600}

![Onsite Customer Visit]({{ site.url }}img/post-cfd-ethnographic-s.jpg)
{: .post-fullwidth-image}

**Workflows and dataflows**
{: .mdl-color-text--grey-600}

![CFD Workflow Mapping]({{ site.url }}img/post-cfd-workflow-1s.png)
{: .post-fullwidth-image}

**Personas**
{: .mdl-color-text--grey-600}

![CFD Persona]({{ site.url }}img/post-cfd-persona-clark-s.png)
{: .post-fullwidth-image}

**Card sorting**
{: .mdl-color-text--grey-600}

![Card Sorting]({{ site.url }}img/post-cfd-card-sort-s.png)
{: .post-fullwidth-image}

##### Strategy

**Design principles**
{: .mdl-color-text--grey-600}

![Design Principles]({{ site.url }}img/post-cfd-principles-s.jpg)
{: .post-fullwidth-image}

**UI component architecture**
{: .mdl-color-text--grey-600}

![App Layout]({{ site.url }}img/post-cfd-app-layout.png)
{: .post-fullwidth-image}

##### UI and Interaction Design

I started low fidelity, exploring broad concepts.

**Sketches of different ribbon paradigms**
{: .mdl-color-text--grey-600}

![Sketching UI Concepts]({{ site.url }}img/post-cfd-ribbon-sketch.jpg)
{: .post-fullwidth-image}

Based on card sorting and stakeholder reviews, I began wireframing the more promising patterns. These were reviewed with internal experts. 

**Wireframes and Information Architecture**
{: .mdl-color-text--grey-600}

![Wireframing UI Concepts]({{ site.url }}img/post-cfd-ribbon-wire-clean.png)
{: .post-fullwidth-image}

The quickest and most direct path forward was getting the layouts in XAML format in Expression Blend/Visual Studio. WPF allowed the front and back-end code to be separated, so I could work directly on layout, interactions, and visual design independently of development in an environment that directly mimicked what a user could see. 

Further, I could drop the layout files into a build from dev and immediately have a fully working prototype. This was essential to delivering the project on time, and refine the design through quick iteration.

**Prototyping**
{: .mdl-color-text--grey-600}

![Prototyping UI Concepts]({{ site.url }}img/post-cfd-blend-proto.png)
{: .post-fullwidth-image}

**Prototyping interactions and evaluating visuals**
{: .mdl-color-text--grey-600}

![Prototyping Interactions]({{ site.url }}img/post-cfd-blend-proto-button.png)
{: .post-fullwidth-image}

**Prototyping responsiveness and resize interactions**
{: .mdl-color-text--grey-600}

![Prototyping Interactions]({{ site.url }}img/post-cfd-resize-interactions.png)
{: .post-fullwidth-image}

##### Visual Design

While a company-wide visual design language existed, I was responsible for icons and layout in our product.

**Visual design iteration**
{: .mdl-color-text--grey-600}

![Design Variations]({{ site.url }}img/post-cfd-visual-ribbon-variations.png)
{: .post-vertical-image}

##### Usability Testing

Early usability testing was conducted with internal experts. The WPF framework allowed us to make changes almost immediately when issues were identified. 

As we neared beta we tested the more stable designs with end-users, eventually arriving at the final design (colored context panels not shown). For this design every test case performed better than the previous release in terms of task time; overall satisfaction and system usability scores were also higher. 

![Design Variations]({{ site.url }}img/post-cfd-ribbon-tabs-rtm.png)
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
