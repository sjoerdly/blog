---
ID: 296
post_title: 'The difference between the &#8216;forecast&#8217; and the &#8216;Sprint Backlog&#8217; in Scrum'
author: Sjoerdly
post_excerpt: ""
layout: post
permalink: >
  http://sjoerdly.com/difference-between-forecast-sprint-backlog-scrum/
published: true
post_date: 2018-06-29 22:31:49
---
There is a difference between the <em>forecast</em> and the <em>Sprint Backlog</em> in Scrum. Exactly what this difference is, has eluded me for some time, and it may very well be unclear to you too. The difference may seem subtle, but can have real practical benefits as you will learn below.

&nbsp;

<h2>The way I used to look at forecast &amp; Sprint Backlog</h2>
&nbsp;

&nbsp;

In the slides of the Scrum courses I teach, the results of the Sprint Planning are listed as: <em>Sprint Goal</em>; <em>f</em><em>orecast</em>; <em>Sprint Backlog</em>. Ever since the PSPO TTT I've had the unsettling feeling that I should have a better grasp on the reason for separately listing the words <em>forecast </em>and <em>Sprint Backlog </em>there<em>. </em>In my mind they were always just different words for the same thing. To me, both were different words to describe the current 'best' plan that the Development Team has for achieving the Sprint Goal. Creating transparency on the forecasted functionality as a list of Product Backlog Items (PBI's). These are most often directly pulled from the top of the Product Backlog.

&nbsp;

&nbsp;

In the Scrum Guide, the word <em>forecast</em> is used in the first sentence of the <a href="http://www.scrumguides.org/scrum-guide.html#events-planning">Sprint Planning</a> chapter:

&nbsp;

&nbsp;

<blockquote class="wp-block-quote">
The Development Team works to forecast the functionality that will be developed during the Sprint.

</blockquote>
&nbsp;

&nbsp;

It is also mentioned when describing the <a href="http://www.scrumguides.org/scrum-guide.html#artifacts-sprintbacklog">Sprint Backlog</a>:

&nbsp;

&nbsp;

<blockquote class="wp-block-quote">
The Sprint Backlog is a forecast by the Development Team about what functionality will be in the next Increment and the work needed to deliver that functionality into a "Done" Increment.

</blockquote>
&nbsp;

&nbsp;

This does not clarify a lot regarding the relation of the Sprint Backlog and the Forecast. At least it did not for me, until now.

&nbsp;

&nbsp;

<h2>The moment of insight; reading the Scrum.org Glossary</h2>
&nbsp;

&nbsp;

So what happened? Today I was reading <a href="https://www.scrum.org/resources/scrum-glossary">the Scrum Glossary</a> and through its descriptions the distinction finally clicked. The Forecast (emphasis mine):

&nbsp;

&nbsp;

<blockquote class="wp-block-quote">
<strong>Forecast (of functionality):</strong>&nbsp;the <em>selection of items</em> from the Product Backlog a Development Team deems feasible for implementation in a Sprint.

</blockquote>
&nbsp;

&nbsp;

And the Sprint Backlog (emphasis mine):

&nbsp;

&nbsp;

<blockquote class="wp-block-quote">
<strong>Sprint Backlog:</strong>&nbsp;an overview of the development work to realize a Sprint&rsquo;s goal, typically a <em>forecast of functionality</em> and <em>the work needed to deliver</em> that functionality. Managed by the Development Team.

</blockquote>
&nbsp;

&nbsp;

So here we have it. The forecast is part of the Sprint Backlog. The Sprint Backlog consists of the forecast (of functionality) <em>plus the work needed to deliver that functionality</em>. The forecast is made transparent through the Product Backlog Items selected during Sprint Planning by the Development Team. The Sprint Backlog expands this by additionally making transparent the work that is expected to turn these PBI's into a 'Done' Increment (releasable &amp; usable).

&nbsp;

&nbsp;

<img class="wp-image-346" src="http://sjoerdly.com/wp/wp-content/uploads/2018/08/forecast.jpg" alt="wooden brown tiles with letters spelling forecast" />
 Forecast by <a href="http://www.thebluediamondgallery.com/wooden-tile/f/forecast.html">Nick Youngson CC BY-SA 3.0</a>

&nbsp;

&nbsp;

<h2>A practical application using the difference between forecast &amp; Sprint Goal</h2>
&nbsp;

&nbsp;

As an added bonus, we could use the <em>forecast</em> explicitly as a summary of the complete set of functionality that is believed to fulfill or reach the Sprint Goal. This means we have a <em>Sprint Goal</em>, plus a <em>forecast summary</em> to describe the <em>what</em> and <em>how</em> of the current Sprint. The <em>Sprint Backlog</em> then describes the plan and details the changes to the Increment that are thought to be needed to <em>reach the Sprint Goal</em> and <em>realize the forecast</em>.

&nbsp;

&nbsp;

An example:

&nbsp;

&nbsp;

<ul>
<li><strong>Sprint Goal</strong>: Drastically improve accessibility of Shopping Cart for the visually impaired</li>
<li><strong>Forecast summary</strong>: Changing visuals to be color-blind compatible AND HTML structure to be screen reader proof and support keyboard&nbsp; navigation.</li>
<li><strong>Sprint Backlog</strong>:
<ul>
<li>Update button elements to be colorblind compatible (either by better images or changing to pure css)
 &nbsp;
&nbsp;

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
&nbsp;

&nbsp;

I hope this helps clarify some potential confusion and maybe the use of an explicit forecast even helps to better communicate with Stakeholders about what to expect in a Sprint Review.

&nbsp;

&nbsp;

<em>Is this useful, or do you have more questions about this topic? I'd love to hear your comments below! </em>

&nbsp;