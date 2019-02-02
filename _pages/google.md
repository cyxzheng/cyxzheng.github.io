---
layout: secret
title: Google Design Exercise 2019
permalink: /supersecret/
cover: /assets/images/projects/google/Cover.png
blurb: “Design an experience for new students to browse, search, and propose new student organizations. Provide your overall process, a wireframe flow, and one to two screens at higher fidelity.”
---

# Research

I came up with 5 questions that I asked to 10 fellow undergraduate students, between the ages of 18-24. I wanted to figure out what was important to them when it came to joining student organizations, how they search for them, and whether or not they ever considered proposing a new organization.

1. Why do you join student organizations?
2. What’s important to you when picking an organization?
3. How do you search for organizations to join?
4. What makes you decide/not decide to join an organization that’s interesting to you?
5. Have you ever considered starting an organization? Why or why not?

### Risks and considerations

Due to the limited time available for this exercise, I am aware that 10 people is not representative of the entire student demographic. I will take this into account, and do my best to make decisions without bias.

# Insights

I gathered answers and summarized my findings, taking note of how frequently the same responses would come up. There was a good amount of overlap between experiences, even at different schools.

<div class="case-image"><img src="/assets/images/projects/google/Question1.png" data-zoom="zoom"></div>

<div class="case-image"><img src="/assets/images/projects/google/Question3.png" data-zoom="zoom"></div>

<div class="case-image"><img src="/assets/images/projects/google/Question4.png" data-zoom="zoom"></div>

<div class="case-image"><img src="/assets/images/projects/google/Question5.png" data-zoom="zoom"></div>

# Finding core problems

My initial research showed that most people have an idea of their interests when searching for organizations. I narrowed down what I found into three core problems:

### 1. There are a lot of options to dig through

A directory presents all the available organizations, and it's up to the user to figure out which ones are relevant to them. Friends and peers can offer recommendations, but they might not be aware of all the available choices.

### 2. Details about an org aren’t always clear

My school has a directory for all organizations, but it doesn’t include information needed to join, such as meeting times and locations. Every organization has a different way of managing their online presence, which sometimes makes it difficult to find the most updated information.

### 3. Proposing an org is a daunting and confusing process

Looking at different universities, the procedures are all quite lengthy, and somewhat intimidating, but I was able to piece together a general process after looking at the procedure from about 10 different schools.

<div class="case-image"><img src="/assets/images/projects/google/Proposal.png" data-zoom="zoom"></div>

When there’s no easy way to search through a catalogue of student orgs, finding out if your idea has a duplicate can be daunting, especially at the larger schools with 600+ student orgs.

# Defining the objective

To help new students **browse, search, and propose new student organizations**, I’ve decided to achieve it with these three goals in mind:

1. Make it easy for students to find orgs based on their interests and values
2. Provide clear information about each org
3. Make the proposal process less daunting

The experience being designed should should aim to fulfill these.

# Ideation and wireframes

I broke down the different unique screens that students might see, in order to better understand what I needed to design.

<div class="case-image"><img src="/assets/images/projects/google/HLFlow.png" data-zoom="zoom"></div>

I went ahead and fleshed out the user flow in Sketch. I chose to design for web, as it’s [incredibly difficult](https://techcrunch.com/2017/08/25/majority-of-u-s-consumers-still-download-zero-apps-per-month-says-comscore/){:target="_blank"} nowadays to convince users to download apps. Typing in a URL is a considerably lower barrier to entry, and developing for web ensures access from almost all devices, as long as they’re connected to the internet.

<div class="case-image"><img src="/assets/images/projects/google/Flow.png" data-zoom="zoom"></div>

You can view the full size image [here](/assets/images/projects/google/Flow.png){:target="_blank"}.

There are three sections in the navigation, each with its own unique purpose.

### 1. Browse

This is where the user looks for organizations that are interesting to them. Recommended for You is a curated list based on user-specified interests, and All Organizations is simply a list with all the options available.

### 2. Favorites

The Favorites section allows users to save organizations for future reference. The Your Interests subsection allows users to keep track of proposed (but not yet formed) organizations that they’ve expressed interest in.

### 3. Up-and-coming

Up-and-coming shows proposed organization ideas that users can “show interest” in, as new organizations being formed need to show that there’s demand. Users can also come up with their own proposals that hopefully garner interest, get submitted, and eventually approved.

Finding and proposing student organizations can be a more dynamic process, as we can take into account a student’s interests, and break down processes to prevent information overload.

# Solving the problem

A couple things come together to make this possible, starting with when the student first logs into the portal.

### 1. Make it easy for students to find orgs based on their interests and values

<div class="case-image"><img src="/assets/images/projects/google/Onboard.png" data-zoom="zoom"></div>

You can view the full size image [here](/assets/images/projects/google/Onboard.png){:target="_blank"}.

Some things have to be determined in person, such as if a user gets along with other members of an organization. Other things, like a user’s interests, we can ask.

The onboarding takes a user’s interests and values, and shows matching organizations up front; this eliminates the need to do blind searches, or to scroll through every category in the school directory. 

<div class="case-image"><img src="/assets/images/projects/google/Explore1.png" data-zoom="zoom"></div>

Under Browse, the Recommended page shows all the results relevant to the user’s interests. This view allows them to very quickly see their options, saving time, and also showing them organizations that they otherwise might have missed if they were manually searching.

The All Organizations page is a collective list of every single student organization. Users, now without the need to look out for organizations relevant to their interests, can browse through the rest of the organizations and allow some to (hopefully) catch their eye.

<div class="case-image"><img src="/assets/images/projects/google/Explore3.png" data-zoom="zoom"></div>

What about the users with interests for which no organizations exist? The Up-and-Coming section shows all proposed organizations. Users can “show interest” to the organizations they want to become a reality.

Each proposal card will show the amount of interest garnered, as well as an expiry time. Each proposal will expire after a month, as that should be sufficient time for aspiring organizations to establish a potential member base.

<div class="case-image"><img src="/assets/images/projects/google/Explore4.png" data-zoom="zoom"></div>

Users can also search for organizations using keywords. This will take into account proposed organizations as well, so that if a search turns up no results, the user can see potential options that they can pledge interest to, so that even if the organization doesn’t exist at the current time, they can do their part to help it form in the future.

### 2. Provide clear information about each org

<div class="case-image"><img src="/assets/images/projects/google/Explore2.png" data-zoom="zoom"></div>

Each organization will have its own page, with accompanying descriptions and pictures. There's an opportunity here to paint an image of what membership entails, and can give potential members an idea of whether or not this organization will benefit them and provide the community that they're seeking.

Important information, such as meeting times, location, and fees, are present on this page, for every single organization. This will reduce confusion, and in turn drive participation, as users won’t have to wonder if the meeting room they’re wandering to is truly the right location.

### 3. Make the proposal process less daunting

<div class="case-image"><img src="/assets/images/projects/google/Propose.png" data-zoom="zoom"></div>

You can view the full size image [here](/assets/images/projects/google/Propose.png){:target="_blank"}.

Duplicate organizations are generally not allowed, as the idea must be original.

The user picks the categories and subcategories that their proposal might fall under, and similar organizations will be shown that match the user’s choices. Presenting potential duplicates upfront reduces the need for a manual search, eliminating the daunting tasks of searching through potentially hundreds of existing organizations to find one that is too similar.

# High-fidelity

I designed with desktop in mind, but didn’t forget about mobile users. A responsive grid was used to ensure that the layout translates well across screen sizes.

### Onboarding

<div class="case-image"><img src="/assets/images/projects/google/Onboard2.png" data-zoom="zoom"></div>

The onboarding process is designed so that the user can scan through the choices quickly. No other content is present, other than the question and possible answers.

A "Next" button is placed here because the form allows for multiple selections, so the user should move forward only when they're ready.

### Browse

<div class="case-image"><img src="/assets/images/projects/google/Browse.png" data-zoom="zoom"></div>

The Browse page presents relevant organizations up front, with a featured picture that gives the user a better sense of what the organization is all about. Each organization is its own card, as they all contain unique information.

A floating action button on the top right allows the user to edit their interests, which in turn will change what's being displayed on the Recommended page.

<div class="case-image"><video autoplay muted loop playsinline><source src="/assets/images/projects/google/menu.mp4" type="video/mp4"></video></div>

The navigation drawer is left open by default on a desktop view, for the sake of visibility to the user. The user can choose to toggle it open or closed.

Tabs enable lateral navigation within each page, allowing for the switch between subcategories of content.

### Organization Details

<div class="case-image"><img src="/assets/images/projects/google/Details.png" data-zoom="zoom"></div>

The Details page contains relevant information about an organization. A small gallery gives the user a preview of what membership might entail. Allowing each organization to provide more details besides a basic description will hopefully encourage more use of this platform, which in turn should result in the important details being updated more often.

<div class="case-image"><img src="/assets/images/projects/google/Up-and-coming.png" data-zoom="zoom"></div>

The Up-and-coming page containing organization proposals is laid out largely the same as the Browse page, but with a dismissable reminder upon first use that informs the user these organizations are not real... yet.

Cards are not split into different category sections, due to the unpredictable nature of what organization proposals might be active at any given time; each proposal's category will be on its own card instead. Each card also has the addition of a "# interested" tag, to show the current level of interest, as well as an expiry timer at the bottom.

# A cool-to-have

### I follow my friends

<div class="img-grid">
<div class="grid-image-3"><img src="/assets/images/projects/google/Friends2.png" data-zoom="zoom"></div>
<div class="grid-image-3"><img src="/assets/images/projects/google/Friends1.png" data-zoom="zoom"></div>
<div class="grid-image-3"><video autoplay muted loop playsinline><source src="/assets/images/projects/google/friends.mp4" type="video/mp4"></video></div>
</div>

During the research phase, many expressed that they would take into account if they had friends in an organization before joining. There was also a good number of people who said they consult their friends for recommendations on what to join. I dreamed up a feature to address this insight, and added a "friends who joined" indicator that can help users see at a glance if they know anyone within an organization.

Unfortunately, it doesn't seem like most universities allow signing in with any form of social media, so this is probably an unfeasible feature in the short term. In the long term, if there's a "friends" feature, and people are compelled enough to add each other, then I could see this happening.

# Takeaways

There's a definite opportunity here to expand beyond simply searching for and proposing student organizations. If I had more time, I would explore beyond simply searching for and proposing organizations, as this could potentially be a centralized hub for all student-related activities, events, and news, not just limited to student orgs. Thank you for taking the time to read my thoughts!