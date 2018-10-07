---
ID: 370
post_title: 'Simplifying CapEx &#038; OpEx in Scrum'
author: Sjoerdly
post_excerpt: ""
layout: post
permalink: >
  http://sjoerdly.com/simplifying-capex-opex-in-scrum/
published: true
post_date: 2018-10-07 11:58:11
---
<!-- wp:paragraph -->
<p>A really simple approach to CapEx &amp; OpEx financial accounting with Scrum. Why is this needed? The apparent mismatch between standard financial accounting practices and agile ways of working. Specifically CapEx and OpEx accounting, which is often a very important practice in (larger) organizations. This distinction seems to be at odds with having a more mixed flow of work compared to the days when we used to make a big design up front (BDUF). After reading the great article <a href="https://www.scrum.org/john-gillespie">by fellow PST John Gillespie</a> titled <a href="https://www.scrum.org/resources/blog/capex-or-opex-through-lean-lens?utm_source=sjoerdly.com">CapEx &amp; OpEx through a Lean lens</a> [1], I felt the need to rephrase in my own terms to give a practical starting point for Scrum Teams struggling with this concept which can lead to an administrative burden if we aren't careful.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p><em>Disclaimer: I am by no means a financial expert and the below article is just as much me trying to make sense of stuff as potentially helpful to practitioners in the wild. The proposed practices are by no means a panacea. Talk to your financial experts and work together to improve! The sources used are targeted at</em><em> software development </em>for INTERNAL use<em>. I am not aware how this would translate to SAAS or app development.</em><br/></p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p><em></em><br/></p>
<!-- /wp:paragraph -->

<!-- wp:heading -->
<h2>Difference between CapEx &amp; OpEx highly simplified</h2>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p>In short: CapEx is all development (innovation) work. OpEx is all 'preliminary' work, and all maintenance. So a super simplified way to track/account these is to budget all Product Owner activities as OpEx and all Development Team activities as CapEx. </p>
<!-- /wp:paragraph -->

<!-- wp:heading {"level":3} -->
<h3>Capital Expenses (CapEx)</h3>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p>Capital Expenses should account for all in-sprint development activities. So all cost incurred by the Development Team in creating the Done Increment should be under CapEx. Simply tracking all expenses like Development Team pay &amp; costs needed for specific Sprint Goals should suffice.<br/></p>
<!-- /wp:paragraph -->

<!-- wp:heading {"level":3} -->
<h3>Operational Expenses (OpEx)</h3>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p>Operational Expenses are a bit more complicated, since we want to account for both preliminary work as well as maintenance. Taking this approach there are rougly two types of work in Scrum:</p>
<!-- /wp:paragraph -->

<!-- wp:list {"ordered":true} -->
<ol><li>Maintenance work done by the Development Team. When a team has the full responsibility to build-ship-run, there's some maintenance to be done. Most of the time also some small rework/bugfixing even though we strive for high quality through technical excellence.<br/></li><li>All Product Backlog management activities. This includes all forms of refinement, stakeholder meetings (storymapping, business value estimation, etc) and whatever else you can think of.</li></ol>
<!-- /wp:list -->

<!-- wp:heading -->
<h2>Simple approach to tracking OpEx in a Scrum Development team</h2>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p>Since we can simply account for all Product Owner activities as OpEx, the biggest challenge lies in getting a clear insight in the OpEx part of the Development Team work. Luckily, there are some great practices that teams can apply to account for these kinds of costs in a lightweight manner. </p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>In Sprint Planning we also have to take into account the time spent on refinement and maintenance activities for the upcoming Sprint. How do most teams deal with this? By applying a simple rule of thumb to start with, and using the Inspect &amp; Adapt loop of Scrum to adjust when needed. </p>
<!-- /wp:paragraph -->

<!-- wp:heading {"level":3} -->
<h3>Maintenance accounting in Sprint</h3>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p>Most teams have a good sense of how much time of the Sprint is normally spent on maintencance work. This is kept 'free' in the Sprint when crafting the Sprint plan. Sometimes it is put on the Sprint Backlog for transparency. For any new team with no clue, this is mostly 10-20% of their planning. And as such, 10-20% of their cost should be shifted to OpEx.  <br/></p>
<!-- /wp:paragraph -->

<!-- wp:heading {"level":3} -->
<h3>Refinement accounting in Sprint</h3>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p>In Scrum, the act of <a href="https://www.scrumguides.org/scrum-guide.html#artifacts-productbacklog">Product Backlog</a> [2] refinement is defined as follows:</p>
<!-- /wp:paragraph -->

<!-- wp:quote -->
<blockquote class="wp-block-quote"><p>Product Backlog refinement is the act of adding detail, estimates, and order to items in the Product Backlog. This is an ongoing process in which the Product Owner and the Development Team collaborate on the details of Product Backlog items. <br/></p><cite><a href="https://www.scrumguides.org/scrum-guide.html#artifacts-productbacklog">https://www.scrumguides.org/scrum-guide.html#artifacts-productbacklog</a><br/></cite></blockquote>
<!-- /wp:quote -->

<!-- wp:paragraph -->
<p>Since the Development team is often needed for these refinement activities, we might choose to account for them as OpEx. If we do so, we can use guidance from the Scrum Guide again to define a starting point as a rule of thumb:</p>
<!-- /wp:paragraph -->

<!-- wp:quote -->
<blockquote class="wp-block-quote"><p>Refinement usually consumes no more than 10% of the capacity of the Development Team. </p><cite><a href="https://www.scrumguides.org/scrum-guide.html#artifacts-productbacklog">https://www.scrumguides.org/scrum-guide.html#artifacts-productbacklog</a><br/></cite></blockquote>
<!-- /wp:quote -->

<!-- wp:paragraph -->
<p>So for most teams, CapEx is about 70-80% of their Development Team cost, plus the in Sprint additional costs. 20-30% of their Development Team cost is OpEx, plus additional refinement cost.</p>
<!-- /wp:paragraph -->

<!-- wp:heading {"level":3} -->
<h3>Additional costs?</h3>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p>Examples of additional costs:</p>
<!-- /wp:paragraph -->

<!-- wp:list -->
<ul><li>Potential additional CapEx: specific tools or new technology is needed IN SPRINT to try something out or implement new functionality. <br/></li><li>Potential additional OpEx: costs related to user &amp; market research, refinement sessions, focus groups, travel to user locations, etc.</li></ul>
<!-- /wp:list -->

<!-- wp:heading -->
<h2>Tracking CapEx &amp; OpEx - pitfalls<br/></h2>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p>When accepting the compromise or reality of this kind of expense tracking, there are some pitfalls to watch out for. In the constant move towards more organizational agility, we should be aware of even more simple solutions, like just labelling everything OpEx. Also, while we are in the situation of tracking the different expenses, we should not create extra overhead for the people involved. Again, always striving for the most simple, frictionless implementation.<br/></p>
<!-- /wp:paragraph -->

<!-- wp:heading {"level":3} -->
<h3>In Agile accounting, all cost should be Operational </h3>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p>In discussing all this, you might have thought to yourself: "But in agile we want to keep things simple, and we don't discern between phases in product development!". A possible simplified end state is to see it as a sunk cost and since we never can truly be sure about the ROI of our work, we should account for it as 'gone'.  For more on this, read <a href="https://www.mitel.com/blog/why-more-cfos-shifting-it-investment-capex-opex">Why More CFO's are shifting their investment from CapEx to OpEx</a> [3]. And while that is true, it may be a requirement in your organization to account in this way. And it may very well be that the organization is not ready (yet) to completely put all cost under Operational Expense (OpEx) and be done with it.</p>
<!-- /wp:paragraph -->

<!-- wp:heading {"level":3} -->
<h3>We should track every hour of work under the right category</h3>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p>Using the guidelines and ideas laid out earlier in this article, it is a small step to forcing your team(s) to track every spent hour under the right category. While this seems sensible (we should have a precise and watertight financial administration) it is quite destructive for the effectiveness of a team. Since the teams are doing complex creative work (or we wouldn't need Scrum or Agile), they need the maximum possible attention for actually DOING the work and finding the best possible solution.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>How then to get it 'as right as possible'? First off, talk to your finance department about what is actually needed (by law) and find out what the leeway is in 'getting it precise'.  If you need more than a 'general' average split in your company you can apply various tactics. From reviewing the split after each sprint and correcting for actual spent time/cost, to having a labeling in the backlog, where items are tracked as 'innovation' (CapEx) or 'Maintenance'  (OpEx). Unforseen maintenance can be added to the Sprint Backlog as 'Maintenance'. Having a digital tracking tool helps for traceability and reporting here, but just keeping an excel up to date is possible too, depending on your business and market regulation/law.</p>
<!-- /wp:paragraph -->

<!-- wp:heading {"level":3} -->
<h3>Simply Refusing as this is not agile</h3>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p>This option is often tried out by inexperienced professionals or purists, who fail to apply the Scrum Values to this problem. Instead of collaborating with the people and departments involved from a place of Respect, Openness &amp; mutual Commitment to do the right thing for the Organization, they create tension, in- and out-group stress and diminish the potential mandate and self-organization. Because this <em>will</em> escalate and if this is the way your organization does their accounting, you will first need to <em>deal with</em> <em>it</em> in the most agile way possible (at that time) and establish trust. From that point on, you can collaborate to improve and simplify. </p>
<!-- /wp:paragraph -->

<!-- wp:heading -->
<h2>CapEx and OpEx in Scrum, a multitude of options and a journey to simplicity</h2>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p>In conclusion, there are a lot of options to figure out this accounting stuff when trying to do Scrum. In striving for simplicity, we should work together to find the simplest current possible solution and envision even simpler ways we could step towards as a future even more simple approach. </p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p><em>What are your experiences with CapEx &amp; OpEx in Scrum? Are there pitfalls you'd like to add, or different practical appraoches to add?  Do you have additional questions or improvements for this article? Let me know in the comments!</em></p>
<!-- /wp:paragraph -->

<!-- wp:list -->
<ul><li>[1] <a href="https://www.scrum.org/resources/blog/capex-or-opex-through-lean-lens">https://www.scrum.org/resources/blog/capex-or-opex-through-lean-lens</a></li><li>[2] <a href="https://www.scrumguides.org/scrum-guide.html#artifacts-productbacklog">https://www.scrumguides.org/scrum-guide.html#artifacts-productbacklog</a></li><li>[3] <a href="https://www.mitel.com/blog/why-more-cfos-shifting-it-investment-capex-opex">https://www.mitel.com/blog/why-more-cfos-shifting-it-investment-capex-opex</a></li></ul>
<!-- /wp:list -->

<!-- wp:paragraph -->
<p><a href="https://www.scrum.org/resources/blog/capex-or-opex-through-lean-lens"></a><br/></p>
<!-- /wp:paragraph -->