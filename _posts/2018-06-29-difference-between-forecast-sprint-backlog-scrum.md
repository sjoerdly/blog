---
ID: 296
post_title: 'The difference between the &#8216;Forecast&#8217; and the &#8216;Sprint Backlog&#8217; in Scrum'
author: Sjoerdly
post_excerpt: ""
layout: post
permalink: >
  http://sjoerdly.com/difference-between-forecast-sprint-backlog-scrum/
published: true
post_date: 2018-06-29 22:31:49
---
In the slides of the Scrum courses I teach, the results of the Sprint Planning are listed as: Sprint Goal; Forecast; Sprint Backlog. It has been bothering me for some time now that I had no real grasp on the reason for separately listing the words <em>Forecast </em>and <em>Sprint Backlog. </em>Since in my mind they were just different words for the same thing: The current 'best' plan that the Development Team has for achieving the Sprint Goal, making transparent the forecasted functionality as a list of Backlog Items (most often directly pulled from the top of the Product Backlog).

In the Scrum Guide, the word <em>forecast</em> is used in the first sentence of the <a href="http://www.scrumguides.org/scrum-guide.html#events-planning">Sprint Planning</a> chapter, and also mentioned when describing the <a href="http://www.scrumguides.org/scrum-guide.html#artifacts-sprintbacklog">Sprint Backlog</a>:
<blockquote>The Development Team works to forecast the functionality that will be developed during the Sprint.</blockquote>
&nbsp;
<blockquote>The Sprint Backlog is a forecast by the Development Team about what functionality will be in the next Increment and the work needed to deliver that functionality into a "Done" Increment.</blockquote>
This does not clarify a lot regarding the relation of the Sprint Backlog and the Forecast. At least not until now.

However, today I was reading <a href="https://www.scrum.org/resources/scrum-glossary">the Scrum Glossary</a> and now it finally clicked.
<blockquote><strong>Sprint Backlog:</strong> an overview of the development work to realize a Sprint’s goal, typically a forecast of functionality and the work needed to deliver that functionality. Managed by the Development Team.

<strong>Forecast (of functionality):</strong> the selection of items from the Product Backlog a Development Team deems feasible for implementation in a Sprint.</blockquote>
So here we have it. The Forecast is part of the Sprint Backlog. The Sprint Backlog consists of the Forecast (of functionality) <em>plus the work needed to deliver that functionality</em>. So Product Backlog Items selected during Sprint Planning by the Development <em>AND</em> their plan describing the work to turn these PBI's into a 'done' Increment (releasable &amp; usable).

As an added bonus, we could summarize the Forecast explicit as a summary of the complete set of functionality that is believed to fulfill or reach the Sprint Goal. This means we have Sprint Goal plus Forecast summary to describe the <em>what</em> and <em>how</em> of the current Sprint. And the Sprint Backlog to describe the plan for changes to the Increment to reach the goal and realize the forecast.

An example:
<ul>
 	<li><strong>Sprint Goal</strong>: Drastically improve accessibility of Shopping Cart for the visually impaired</li>
 	<li><strong>Forecast summary</strong>: Changing visuals to be color-blind compatible AND HTML structure to be screen reader proof and support keyboard  navigation.</li>
 	<li><strong>Sprint Backlog</strong>:
<ul>
 	<li>Update button elements to be colorblind compatible (either by better images or changing to pure css)
<ul>
 	<li>research best accessible option that is still pretty for non-impaired users</li>
 	<li>Optionally create new images</li>
 	<li>Update code (and/or images)</li>
 	<li>Run accessibility tests on button elements</li>
 	<li>Validate other DoD items</li>
</ul>
</li>
 	<li>Refactor HTML to latest standards (which better support accessibility out of the box)
<ul>
 	<li>X</li>
 	<li>Y</li>
 	<li>Z</li>
</ul>
</li>
 	<li>Add ARIA tags to HTML where needed
<ul>
 	<li>etc</li>
</ul>
</li>
 	<li>Improve HTML structure to support logical tab order</li>
 	<li>Add labeling to inputs to support screen readers</li>
 	<li>Support text zooming better (currently some layout breaks when using browser zoom)</li>
</ul>
</li>
</ul>
I hope this helps clarify some potential confusion and maybe the use of an explicit forecast even helps to better communicate with Stakeholders about what to expect in a Sprint Review.

<em>Is this useful, or do you have more questions about this topic? I'd love to hear your comments below!</em>