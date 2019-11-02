---
layout: project
order: 1
title: Microsoft 365 &ldquo;What&rsquo;s New&rdquo;
preview: Informing without disrupting.
permalink: /microsoft
cover: /assets/images/projects/microsoft/cover.png
thumbnail: /assets/images/projects/microsoft/thumbnail.mp4
intro: New features are shipped weekly to the M365 Admin Center, and at that frequency, how do we educate users on all of them? Beyond simply directing them to an article that they may or may not read, there had to be a way to teach users without disrupting their work. </br> </br> I designed a new way of contextual alerting for the M365 Design System.
nexturl: /hvf/
nexttitle: HVF Labs
---

## My role

This summer (2019), I worked on the M365 Design Direction team. The Design Direction team is responsible for defining the visual language and creating the design system used by all the other M365 design teams. 

Though hired on as a UX Design Intern, I was able to focus my efforts on developing my motion design and visual design skills, thanks to support from my manager [Karina Dion](https://www.linkedin.com/in/karina-dion-2496707/), and my mentor [Sungwon Chang](https://www.linkedin.com/in/sungwon-chang-87a7a658/).

##  What did I work on?

I was tasked with improving the What’s New experience in the M365 Admin Dashboard. What’s New was a link in the toolbar that directed users to an article outlining new features and updates, and we wanted to educate users in a better way.

## What’s the problem?

Here’s what happens when a user clicks on What’s New:

<div class="image"><video class="shadow" autoplay muted loop playsinline><source src="/assets/images/projects/microsoft/problem.mp4" type="video/mp4"></video><h5>A new tab opens when a user clicks “What’s New”</h5></div>
We already knew at this point that the click-rate for the What’s New link was low, and in general, users don’t like clicking on things that take them out of the experience. 

The solution of using a carousel to highlight updates and new features is actually more disruptive than helpful, and in some cases, the carousel content is outdated.

### An interesting thought

What if What’s New didn’t just live in the top toolbar? What if it’s actually everywhere? This way of thinking was what drove the project moving forward, and I tried to think about What’s New as something contextual, rather than only applicable to one location.

## Early explorations

I asked my PM, “What are some “must-knows” for the user?” and prioritized which screens I would design based on the answer.

### New things on a dashboard

When new features are released for the admin dashboard, they’ll be highlighted and the user has the option to add or dismiss the card.

<div class="image"><img class="shadow" src="/assets/images/projects/microsoft/early1.png"><h5>A new feature on the dashboard would be highlighted by a coloured card</h5></div>
### New things in the panel

When new features are released in the side panel, they’re tagged “New” so that the user is aware.

<div class="image"><img class="shadow" src="/assets/images/projects/microsoft/early2.png"><h5>New features in a panel would be labelled with a tag</h5></div>
### New things on a page

In pages other than the main dashboard, new features are highlighted in a big card so that users can learn about it.

<div class="image"><img class="shadow" src="/assets/images/projects/microsoft/early3.png"><h5>New features on a page would be featured by a big banner</h5></div>
## These weren’t bad, but...

The problem with each of my explorations were that they only solved the What’s New problem for that particular screen. There was no consistency, and this was hard to work into a system. We took a step back after this to think about how What’s New can fit in everywhere.

## The hypothesis:

We believe that contextually showing what’s new is better, as we can focus on new additions without being disruptive.

### Why contextual?

- We can alert users without disrupting their workflow
- We can use each alert as a teaching opportunity
- This can become a system of alerting, recognizable by colour, motion, iconography, and copy.

With our hypothesis in place, we went to tackle this problem starting from the top toolbar, designing while keeping in mind how we can apply what we make to other parts of M365.

## Make fast, test fast

I used motion and colour to create two alerts for a new card, so that we could test this in front of existing M365 customers.

### Using a sweep to draw attention

A large sweeping motion draws attention to the item with new features, before shrinking out of view but leaving behind a persistent indicator (which will disappear upon interaction).

<div class="image"><video class="shadow" autoplay muted loop playsinline><source src="/assets/images/projects/microsoft/early4.mp4" type="video/mp4"></video><h5>Similar motion accompanies the new item within the panel, reinforcing a system</h5></div>
### Using a call-out 

A call-out with copy describing the new feature appears first, and after a small delay, a dot badge follows. The delay is meant to allow users time to shift their attention over to the area of interest, so that they can notice the dot badge appearing.

<div class="image"><video class="shadow" autoplay muted loop playsinline><source src="/assets/images/projects/microsoft/early5.mp4" type="video/mp4"></video><h5>The dot badge appears as a consistent element in the panel, reinforcing a system</h5></div>
### What did users think?

> “[I chose] the Sweep flow [for visual appeal] just because of the slide out. I’m so used to seeing a little dot [badge] and [the badge] is not that noticeable. It’s much better with the slide out.”
>
> <p class="quotee">— Participant 10</p>
>“Had I been looking down at the lower left corner [of my screen], I might not have caught the Call-out as easily as the Sweep.”
> 
><p class="quotee">— Participant 4</p>

<div class="image"><img src="/assets/images/projects/microsoft/comparisons.png"></div>
We didn’t scrap the badge option. We inferred from the user testing comments that just a badge is not enough, and that an attention grabber (like the sweep) to go along with it can help draw attention, and reinforce a system.

## Further refinements

After taking in the feedback, I went ahead and made version two to get ready for testing. 

### A new colour

The previous prototypes used a teal colour, but that was a colour M365 used for data viz. I picked a new colour that would be solely used for this alerting system, and made sure it was WCAG AA compliant. 

<div class="image">
<div class="img-grid-around bg">
<div class="image"><img src="../assets/images/projects/microsoft/colour.png"></div>
<div class="image"><img src="../assets/images/projects/microsoft/darkcolour.png"></div>
</div>
<h5>Dark mode colours by Karina Dion</h5>
</div>

### A combination

I took into consideration that M365 as a product lives on the web, and therefore, everything on M365 lives in a container. This would allow for a system to be applied everywhere, as long as the containers are similar in spacing and size.

Because M365 is a web product, we took into consideration the fact that everything lives in a container. This would allow for a system to be applied everywhere, because the containers are similar in spacing and size.

With containers as a constraint in mind, I decided to limit the sweep to the element we want to draw attention to. A dot badge would follow, and stay persistent, until the user interacts with the new feature. A dot badge is something that everyone in this day and age is accustomed to seeing as "new", so I leveraged that knowledge in my design.

<div class="image"><video class="shadow" autoplay muted loop playsinline><source src="/assets/images/projects/microsoft/final1.mp4" type="video/mp4"></video><h5>The alert consists of drawing attention, followed by notification</h5></div>
### Working elsewhere

I created another motion study, showing the application of this system on the side navigation and in a different page. This was to show that this works elsewhere, and that the colour and badging can be used to create a recognizable contextual alerting system.

<div class="image"><video class="shadow" autoplay muted loop playsinline><source src="/assets/images/projects/microsoft/final2.mp4" type="video/mp4"></video><h5>While the side navigation items are a different width, the spacing and height are similar enough to allow this system to work</h5></div>
### Stress test

I put a bunch of dot badges on the dashboard, to show that it won’t overwhelm a user. As a precaution, we also set a time of 45 days before the dots disappear, if the user doesn’t dismiss them. This time period was decided based on the longest time between logins, which happened to be 6 weeks. Further tweaking, if needed, will be done based on future feedback.

<div class="image"><img class="shadow" src="/assets/images/projects/microsoft/stress1.png"><h5>Multiple badges on the dashboard</h5></div>
<div class="image"><img class="shadow" src="/assets/images/projects/microsoft/stress2.png"><h5>Showing that the purple badge can live alongside existing badges of different colours</h5></div>
### Copy  is important too!

The sweeping motion and dot badge draws attention to the new feature, and the call-out does the educating. The copy written in the call-out doesn’t only educate users on what the new feature is. In some cases, where a feature could be buried 2 or 3 levels deep in a page, the call-out is there to educate users on where it is.

<div class="image"><img class="shadow" src="/assets/images/projects/microsoft/verbiage.png"><h5>In this case, the dot badge would be extremely redundant if it was displayed on each user panel</h5></div>
##  How did the new design do?

Our user researchers are amazing, turning this around right before I gave my final presentation. 

> “It’s cool that it kinda flashes over [Add Card] and becomes a small circle and let’s you know, ‘Hey, you can click here.’”
>
> <p class="quotee">— Participant 2</p>
>“I like that it’s not too much of a distraction, but it’s enough to get your attention. It changes the colour of the Add Card button and then it changes the text colour and shows that dot. So I think it stands out.”
> 
><p class="quotee">— Participant 7</p>

The feedback was positive, and shows that our hypothesis is on the right track. It looks like contextual alerting is better for showing and educating users on what’s new.

## What’s next?

Before leaving Microsoft, I put forth some next steps for my project.

### 1. Fabric implementation

Fabric is a design system. The plan is to implement this as a component into Fabric as a third option for alerting that’s less intrusive than the current coachmark approach. This will live as a more refined, elegant way of grabbing the user’s attention.

### 2. Apply to Admin Center

This will be implemented and used anywhere on the M365 Admin Center where contextual alerting is needed.

### 3. Think about What’s New as destination

While What’s New is currently an article, soon to be a contextual alerting system, for future-thinking, it could potentially be a destination, where users can go somewhere central for their information. Perhaps this could include a community aspect, or a blog, but the idea is to create a direct communication link to and from our users.

<div class="image"><img class="shadow" src="/assets/images/projects/microsoft/whatsnewpanel.png"><h5>Moving the article into a panel to prevent disrupting a user in the middle of their workflow</h5></div>
<div class="image"><img class="shadow" src="/assets/images/projects/microsoft/whatsnewpage.png"><h5>A destination with more than just news</h5></div>
## Some other work I did

While What’s New was my main project at Microsoft, I tried to get my feet wet by working on a few smaller projects with different teams and individuals. I wanted to learn as much as I could during my 12 short weeks, and what better way to do that than to try out different things?

### M365 Banner Illustrations

I created some different illustrations for the first-run experience banner on Admin Dashboard. I played with the idea of comparing setting up Admin Center to setting up an actual office, and was able to start a conversation around how we could use illustrations to better tell a story.

<div class="image bg"><img src="/assets/images/projects/microsoft/fre1.png"></div>
<div class="image"><img class="shadow" src="/assets/images/projects/microsoft/fre2.png"></div>
<div class="image"><img class="shadow" src="/assets/images/projects/microsoft/fre3.png"><h5>Imagining setting up Admin Center as setting up an office</h5></div>
### Welcome Banner

Our welcome banner was in need of a refresh, and I flexed my creative muscles to come up with over 30 variations, and landed on three of my favourites. I tried to push the boundary in terms of how we could use different illustrations, sizes, and orientations to better onboard new users.

<div class="image"><img class="shadow" src="/assets/images/projects/microsoft/variations.png"></div>
<div class="image"><img class="shadow" src="/assets/images/projects/microsoft/work1.png"></div>
<div class="image"><img class="shadow" src="/assets/images/projects/microsoft/work2.png"></div>
<div class="image"><img class="shadow" src="/assets/images/projects/microsoft/work3.png"></div>
### Catastrophic Error State

I worked with a high school intern to breathe life into an error page. I learned that for even the smallest features, multiple check-offs happen to ensure design consistency. I shifted my illustration to an isometric view, because my original work didn’t comply with the newly developed M365 illustration styles.

<div class="image"><img class="shadow" src="/assets/images/projects/microsoft/error1.png"></div>
<div class="image"><img class="shadow" src="/assets/images/projects/microsoft/error2.png"></div>
### Dark Mode

While the push for dark mode was already happening, the transition was just a simple page refresh. I had some fun making a few different explorations to offer a source of inspiration for future designers, developers, and PMs on the dark mode project.

<div class="image"><video class="shadow" autoplay muted loop playsinline><source src="/assets/images/projects/microsoft/dark1.mp4" type="video/mp4"></video></div>
<div class="image"><video class="shadow" autoplay muted loop playsinline><source src="/assets/images/projects/microsoft/dark2.mp4" type="video/mp4"></video></div>
<div class="image"><video class="shadow" autoplay muted loop playsinline><source src="/assets/images/projects/microsoft/dark3.mp4" type="video/mp4"></video></div>
## Learnings and Lessons

Did I have the best summer internship ever? Of course I did. I walked away with some valuable takeaways for my future.

### Be flexible and adaptable

Sometimes (usually always), things change. It’s important to roll with the punches, and know that getting things done is a team effort. Nothing is ever a straight path, but it makes for a much more compelling story when it’s not.

### Know the constraints, but don’t let them constrain you

Especially at a slightly larger company like Microsoft, a ton of existing work will have been done before you get there. It’s important to get familiar with what other people have made, and to leverage it into your own work, but it’s also equally important to know it’s totally okay to take it farther. That’s how things evolve.

### Shoot for the moon

Be grandiose. Make what you want to make. Make what you think is cool. The more excited you are about your own work, the easier it is to spark conversations with others, and get them excited too. When others share your vision, it’s easier to bring them along and go further with your work than if you just play it safe.

### Never become unenthusiastic

12 weeks is a really short time to get acquainted with a team, so jump in with both feet! Talk to people, work with people outside your team or organization, and be excited about your work. Positive energy is contagious, and it’s apparent to everyone when you’re passionate about what you’re doing.

