---
layout: project
title:  "Mobile Job Monitor"
categories: professional
image: img/placeholder.png
permalink: /projects/jobmonitor/
blurb: With the ability to run many simulation jobs in parallel on the cloud, and with each taking up to hours to solve, it is desirable to monitor them on the go. Mobile Job Monitor provides a simple way to check progress and status.
---
#### Background and Hypothesis

It is now possible to run simulation jobs in parallel on secure clusters through a number of web-based simulation services. For example, in 2012 Autodesk Simulation launched a cloud simulation service under the "360" name. With this sort of access to large banks of on-demand computational power, many simulations can be solved in parallel to explore variations. 

One gap in these services is that cloud-based simulations can typically only be monitored from the source computer, yet can take many hours. A typical workflow is that an engineer may submit several jobs to solve before leaving the office, and will want monitor them as they run. 

Sim Job Monitor is a concept project I pursued individually to address this problem.  The premise is that a user should be able to monitor the progress of simulations that are currently solving no matter where they are. There should be an option for notifications when jobs complete or fail, with basic details and output available for review. 

I had a personal interest in learning more about Material Design and the Android SDK so I chose to design Job Monitor for Android. A production monitor may be more convincing in terms of market as a responsive website or iOS app. 

#### Screen Flow

![Proposed App Flow]({{ site.url }}img/post-job-monitor-flow.png)
{: .post-fullwidth-image}

#### Design Explorations

**Exploring themes and visual variations**
{: .mdl-color-text--grey-600}

![Design Variations]({{ site.url }}img/post-job-monitor-comp.png)
{: .post-fullwidth-image}

**Visualizing digital paper layers**
{: .mdl-color-text--grey-600}

![App Paper Layers]({{ site.url }}img/post-job-monitor-layers.png)
{: .post-fullwidth-image}

**Job detail concept**
{: .mdl-color-text--grey-600}

![Job Details]({{ site.url }}img/post-job-monitor-details.png)
{: .post-fullwidth-image}


<div class="mdl-grid">
  <div class="mdl-card mdl-cell mdl-cell--8-col mdl-cell--6-col-desktop">
	<div class="mdl-card__supporting-text meta mdl-color-text--grey-600">
	  <div>
	    <strong>Card view</strong>
		<span></span>
	  </div>
    </div>
	<div class="mdl-card__media mdl-color--white mdl-color-text--grey-600">
	  <a href="http://ryanarnaudin.com/img/post-job-monitor-card-2.png">
		<img style="width: 100%" src="http://ryanarnaudin.com/img/post-job-monitor-card-2.png">
	  </a>
	</div>
  </div>
  <div class="mdl-card mdl-cell mdl-cell--8-col mdl-cell--6-col-desktop">
    <div class="mdl-card__supporting-text meta mdl-color-text--grey-600">
	  <div>
	    <strong>Notification</strong>
		<span></span>
	  </div>
    </div>
	<div class="mdl-card__media mdl-color--white mdl-color-text--grey-600">
	  <a href="http://ryanarnaudin.com/img/post-job-monitor-push.png">
		<img style="width: 100%" src="http://ryanarnaudin.com/img/post-job-monitor-push.png">
	  </a>
	</div>
  </div>     
</div>

#### Prototyping

**Invision prototype to test app flow and usability**
{: .mdl-color-text--grey-600}

![Prototype with frame]({{ site.url }}img/post-job-monitor-invision-cropped.png)
{: .post-fullwidth-image}

**Android SDK Prototype**
{: .mdl-color-text--grey-600}

TODO: Screenshot


