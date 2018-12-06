---
layout: case
title: Property Inspector
permalink: /property/
preview: Rethinking the adjuster workflow.
order: 1
thumbnail: /assets/images/projects/property/thumbnail.png
cover: /assets/images/projects/property/Cover.png
blurb: An insurance company in Germany was having trouble with its property damage inspection process. The use of paper forms caused inconsistencies in how the information was being recorded, which impeded claim processing in the back-office. </br> </br> I was part of a project to create a prototype that the client could later demo at a trade show, with the intention of attracting potential buyers and stakeholders.
nda: In compliance with my NDA, I have omitted confidential information. The designs are a reinterpretation of the original.
next-title: 365 Days of Design
next-url: /365/
---

# The Present-day reality

All property damage inspections are done using paper forms. Because the adjuster has to be physically on-site, it made sense that paper would be the most reliable way to record information without an internet connection. However, with data plans being so cheap, especially in Germany, it was possible now to reliably record inspection information digitally.

The high-level requirements given to us were:

1. Improve the efficiency of the property inspection process for the adjusters.
2. Create a tool that could be integrated into the existing suite of software used to handle their claims processing.
3. Design for a 10 inch iPad.

# My role

I was responsible for creating wireframes, talking to the client in order to iterate, and creating the visual design.

In addition, I worked alongside our Strategy Director, Product Manager, and was managed by our Director of Product Design.

I was involved from the discovery phase all the way to client handoff, spanning four months from January 2018 to April 2018.

# One form, different habits

From early talks with the client, we thought that the problem mostly lay with the paper forms. We were told that the adjusters usually had to fill out a multi-page form during the inspection, and the form items were never filled in order, due to the unpredictable nature of property damage.

<div class="case-image"><img src="/assets/images/projects/property/FormOrder.png" data-zoom="zoom"></div>

We initially thought that this would be a simple process of porting over their existing forms into a digital format, which was an incredibly optimistic assumption. We pressed on, and discovered that each adjuster’s different form-filling habits caused a good deal of issues for the back-office, where the claims were actually processed.

<div class="case-image"><img src="/assets/images/projects/property/FormOrder2.png" data-zoom="zoom"></div>

No inspector filled out their forms in the same way, as each had their own “style” of conducting inspections. Forms were also rarely completely filled out. This made it difficult for the people in the back-office, who had to input information into the claims software, but the many different variations of completed forms slowed down this task considerably.

# Figuring out common actions

We were fortunate enough to be able to talk to some people on the client’s side who were more familiar with the property inspection process. Through many conversations, and reading through crudely translated inspection forms, I pieced together a customer journey that described at a high level what a typical inspection from start-to-finish would look like.

<div class ="case-image"><img src="/assets/images/projects/property/CustJourney.png" data-zoom="zoom"></div>

The idea was that if we were able to figure out an acceptable general path for property inspections, we could start to figure out how to create a form that would guide (but not force) adjusters in filling out all the necessary information for the folks in the back-office.

This also allowed us to map out what new features we would need to design, and also see what existing features in the larger suite of software we could use.

# Nudge, not push

One thing we noticed about the paper forms was that it didn’t ask too many questions; there were input boxes to record all kinds of information, like measurements, damage types, building types, etc, but there were no prompts or indications of what was necessary to fill out.

We also realized that since no two properties are the same, it was almost impossible to follow the same procedure for every single inspection. This meant that it wasn’t doing anyone favours if we forced adjusters to follow a strict order when answer questions.

<div class="case-image"><video autoplay muted loop playsinline><source src="/assets/images/projects/property/diffhouses.mp4" type="video/mp4"></video></div>

The back-office had their own requirements for what information was necessary in order properly create a claim, but because the paper forms were entirely made up of written answers, it was difficult to establish consistency in what was being recorded. We worked with the client to figure out all the possible options for different inspection questions, and opted to make the majority of the form multiple-choice.

<div class="case-image"><img src="/assets/images/projects/property/questionexamples.png" data-zoom="zoom"></div>

We created a set of questions based on a water damage claim, doing our best to make sure the answers fulfilled the back-office requirements. The client partnered with us on this endeavour, modifying certain elements to better match the actual inspection process of an adjuster.

# Embracing different inspection styles

Paper forms can’t tell you how much progress you’ve made, but thankfully digital mediums can. Always showing progress gives the adjuster an idea of where his inspection is.

<div class="case-image"><video autoplay muted loop playsinline><source src="/assets/images/projects/property/progress.mp4" type="video/mp4"></video></div>

The flexible nature of the form allows for different inspection styles. The “power adjuster” might opt to jump between sections without following a certain order, whereas others might opt to follow the form sequentially. It doesn’t really matter how the form is completed, as long as it’s completed properly.

<div class="case-image"><video autoplay muted loop playsinline><source src="/assets/images/projects/property/order.mp4" type="video/mp4"></video></div>

# An all-in-one inspection tool

The client also pushed us to consider other needs that an adjuster might have, such as documenting information through photos and videos, or making estimates.

Because the iPad has a built-in camera, we were able to leverage this and allow adjusters to add extra documentation when needed. This also aids the back-office when they analyze all the information when making a claim.

<div class="case-image"><img src="/assets/images/projects/property/Documentation.png" data-zoom="zoom"></div>

It’s also helpful for adjusters to be able to make damage calculations on the spot, when the scene is still fresh, and there’s the option to walk around and physically assess the damage. We were given the Excel document used to calculate these estimates, and dissected it so we could repurpose it for our inspection tool.

<div class="case-image"><img src="/assets/images/projects/property/Calculations1.png" data-zoom="zoom"></div>

At times, it’s also necessary to take into account depreciation for certain damage items. As it’s not applicable to all items, it’s condition that can be applied or removed.

<div class="case-image"><video autoplay muted loop playsinline><source src="/assets/images/projects/property/timevalue.mp4" type="video/mp4"></video></div>

Being able to preview the report as the inspection happens allows for the adjuster to see what they might have missed anything, or if they made a mistake. Compared to flipping through 6+ page forms, this is a much easier way to check their work.

<div class="case-image"><img src="/assets/images/projects/property/Preview.png" data-zoom="zoom"></div>

Each section in the form can be accessed through the preview, so no time is wasted in looking for the section they want to edit.

The power of technology also allows us to prevent a report from being generated and sent if there are required fields that are unfilled. This ensures the folks at the back-office won’t have to chase down an adjuster for information that they might have little recollection of.

# Designing for the German language

This tool ultimately needed to be in German, and I designed with that consideration in mind from the beginning. Our resident copywriter informed us that German is typically 30% longer than English, but her experience was closer to 50%. We designed the UI with that in mind.

<div class="case-image"><img src="/assets/images/projects/property/German1.png" data-zoom="zoom"></div>

We made the initial designs in English, and the client translated everything to German. We were focused on making sure all the content and inspection-related text was correct before asking for translations. The final design was delivered in German.

<div class="case-image"><img src="/assets/images/projects/property/Final1.png" data-zoom="zoom"></div>

<div class="case-image"><img src="/assets/images/projects/property/Final2.png" data-zoom="zoom"></div>

# Lessons and takeaways

The clients worked with us over a period of four months, with lots of back and forth and expert opinions from adjusters informing our design choices. My prototype was presented at a trade show shortly after, with positive reactions from the attendees, and we were told that an investment would be made into building out this inspection tool. 

Due to the confidential nature of this project, we were not allowed to test the prototype with anyone outside of the project or client team. There were few on the client’s side with experience in property inspections, but getting the prototype out earlier to a larger number of users might have produced better insights earlier on in the process.

I would have liked to continue working on this project into the build stage, so that I could further improve the product with insights from adjusters using it in the field, verifying some of the assumptions with users beyond the ones we had on the client team. 

I’m grateful to have been given the opportunity to be the primary designer on this project as an intern, and equally grateful for all the support from an amazing team who backed me up. Hopefully we were able to move insurance closer into the 21st century, even if it’s just by a little bit.