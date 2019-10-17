---
layout: post
title:  "Shoom"
date:   2019-10-04 12:52:01 -0700
categories: jekyll update
permalink: "/shoom"
excerpt: "Shoom is an app to help emerging musical artists control their destiny by showing them where their potential new fans are and by allowing them to book gigs with similar artists."
image: /assets/shoom/splash-screen.png
category: "Product Design"
---
## Overview
Shoom is an app to help emerging musical artists control their destiny by showing them where their potential new fans are and by allowing them to book gigs with similar artists. I designed it as part of a group project for a User Interface Design course at the UC Berkeley School of Information. The project was designed to serve as an introduction to the full UX process from user research to hi-fi mockups.

## Role
Shoom was designed to be part of a larger ecosystem of services. One of my teammates, Yi Gai, designed a service that enabled concert goers to request artists to play in their city. Our teammate Sharanya Soundararajan designed a service that offered concert venue owners a place to list their venue and handle booking requests from artists.

Each of us autonomously did conducted user research and designed flows for each of our stakeholders and offered each other regular critique throughout the course. Thus, **I was responsible for conducting user research with and designing the flow for artists.** In addition, I originally proposed the group project for an ecosystem of services for artists, venues, and concert goers and built the team to pursue the idea.

## Inspiration
**More than anything growing up, I wanted to be a professional musician,** but coming of age during the massive shift in the music industry away from physical sales – which brought an equally massive decline in overall revenue – left me with the impression that making a life as a musician would become even harder than it already was. In the intervening years, my passion for music has not wavered (insert shameless plugs [here](https://www.instagram.com/anima1a1a1a1/) and [here](https://www.youtube.com/watch?v=FjtLo-zHwNI)), but it has had to compete with my passion for UX design/engineering. Hence, when the opportunity arose to create a custom project in my first User Interface Design course, **I was inspired to design a service with the goal of putting more power in artists’ hands** such that they can sustain their work on their own terms.

## Problem Space
Due to the aforementioned shift in the music industry, artists tour far more frequently than they used to in order to sustain their work. However, touring is both physically and financially draining, and most emerging artists make no profit or even lose money from touring. **How might we enable emerging artists to profit more from touring?**

<img src="/assets/shoom/pie-chart.png" alt="pie-chart" />

##### This recent artist revenue breakdown from PwC (apologies for the pie chart) illustrates just how much artists rely on touring

In order to create more touring profit for emerging artists, I hypothesized artists need the following:
1. Artists need to know where their fans are
2. Artists need to be able to book their own shows
3. Artists need to be able to manage their own tours

In a world where artists are their own analytics managers, booking agents, and tour managers, artists will have all the tools they need to be their own managers, thus cutting their costs and allowing them to keep more of their hard-earned money in their pockets.

## Timeline and Process
10 weeks
* Round 1
  * User Flow: 1 week
  * Lo-Fi Mockups: 2 weeks
  * Interviews: 2 weeks

* Round 2
  * Initial Hi-Fi Mockups: 2 weeks
  * Usability Testing: 1 week
  * Final Hi-Fi Mockups: 2 weeks

## Round 1
### User Flow
The initial user flow I hypothesized entailed a blend of Spotify Analytics, Instagram, and Airbnb. Even before creating a lo-fi mockup, I sensed the scope would be too much to take on in an Intro to UX class, but at the time, I believed the best way to test my hypotheses was to design a full lo-fi mockup and then conduct exploratory interviews rather than the other way around.

<img src="/assets/shoom/user-flow.png" alt="user-flow" />

### Lo-Fi Mockup
To test these hypotheses, I first created a lo-fi mockup of an automated tour planning service built on a foundation of fan analytics and direct venue booking.
**The service I initially mocked up was designed to automatically plan tours for artists by automatically booking shows for them in cities where they had the most potential to increase their fanbase.** In addition, the service estimated how much profit artists could expect to earn from the tour. Two key features helped build up to automated tour planning: fan analytics and venue discovery.

#### Fan Analytics
For Fan Analytics, I provided a heat map that shows how many fans of a given artist or genre live in a given city. **Putting this knowledge into artists' hands cuts their touring costs by making them their own analytics managers, and it puts them one step closer to being their own booking agents.** I was inspired by Spotify Artist Analytics to show artists where not only their listeners were, but also where related artist’s listeners were, to inspire them to book shows in places they may not otherwise have considered.

<img src="/assets/shoom/fan-discovery.png" alt="fan-discovery" />

##### Fan Analytics cuts touring costs by giving artists ownership over their streaming data

#### Venue Discovery
Venue Discovery was designed to help artists find the right venue to play at in an unfamiliar city. I did this by providing a list of venues in a given city ranked by how many related artists had played there recently. **Venue Discovery saves artists money on booking agents by allowing them to understand the scene in any city.**

<img src="/assets/shoom/venue-discovery.png" alt="venue-discovery" />

##### Venue Discovery cuts touring costs by making artists their own booking agents

#### Tour Planning
Thus, once an artist chose the cities they wanted to tour in using the Fan Analytics feature, the automated Tour Planner would string together a series of booking requests to the most compatible venues in each of those cities. **Enabling artists to book their own tours saves them money on booking agents and tour managers and lets them keep more of their hard-earned money.**

<img src="/assets/shoom/tour-planner.png" alt="tour-planner" />

##### Tour Planning cuts touring costs by making artists their own tour managers

### Interviews
With a full lo-fi mockup in hand, I then interviewed 4 current and former artists who have either played local shows or gone on regional tours. Before walking them through the mockup, I asked high-level questions about the biggest pain points they face building a fanbase, booking shows, and planning tours.

#### Interview Findings
From the interviews alone, I discovered emerging artists face three key pain points, none of which necessitated an automated tour planning service:
1. **Emerging artists want a way to get noticed by bigger artists** because emerging artists build their fanbase largely by being an opening act
2. **Emerging artists want visibility into which cities suit them best**
3. **Emerging artists want to know if related artists have recently played a given city** such that they don’t compete for the same audience
	
By walking my participants through the mockup, I discovered that building an automated tour planning service was infeasible due to the amount of uncertainty on the road. One key feature of the service was to show artists how much profit they could expect to earn from their tour, but what if their van broke down halfway to the next show, cost $1000 to fix, and they couldn’t make the next gig? The service I designed would not be able to handle such contingencies.

### Round 1 Lessons Learned
With the feedback I received through interviews, I had to throw my core assumption that artists want their tours planned for them out the window. Putting in hours of work to create a lo-fi mockup only to have it invalidated through interviews before even showing it taught me a hard lesson I will never forget: **understand your users first.**

In the future, I will be sure to conduct interviews before creating any mockups. But rather than feel discouraged by having my core assumption invalidated, I felt empowered that a number of musicians who had been on the road told me I was on the right track and they wish they had services specifically designed to help them. Thus, the project was reborn as a way to empower emerging artists to build their fanbase by getting noticed by bigger acts and securing a spot as an opener.

## Round 2
### Initial Hi-Fi Mockup
As encouraged as I was to discover the pain points emerging artists faced, doing so late in the semester left me with little time to start over as I had to deliver hi-fi mocks for the team final presentation. Thus, I made the tough decision to go straight to a hi-fi mockup which deprioritized tour planning and instead emphasized allowing artists to request to play a show with other artists because securing an opening spot was the highest priority pain point the artists I interviewed identified. This decision unfortunately came at the expense of solving for the other pain points I uncovered due to the time constraints. I did, however, have time to include features for artists to review venues and each other. 

### Usability Testing
Using the initial hi-fi mockup, I conducted three usability tests through UserTesting.com using a screener for testers that were musicians. The key findings were that test users wanted to see an artist’s top songs on their profile, test users want to be able to chat with other artists, and test users want to know whether reviews came from other artists or venues.

### Final Hi-Fi Mockup
With this feedback, I created a final hi-fi mockup that showed an artist’s top songs on their profile, allowed artists to chat via Facebook Messenger, and showed whether reviews came from other artists or venues.

<img src="/assets/shoom/discover-bands.png" alt="discover-bands" />
<img src="/assets/shoom/band-profile.png" alt="band-profile" />

##### Giving bands a way to discover each other in the same service as discovering fans and venues addresses artists’ need to grow their fanbase through collaboration

## Takeaways
As I mentioned earlier, the biggest lesson I learned was to listen to, and understand, your users as much as possible as early as possible. **Were I to do it all over again, I would start by interviewing as many users as it takes to see patterns, and only then would I begin creating mockups.** Doing so would have freed up time to build and test mockups that addressed artists’ needs more deeply – for example, building specific features showing artists if related acts have played in a given city recently – but given the time constraint of the semester and the setback of creating mockups before interviews, we only had time for a first pass.

Because I feel strongly about enabling emerging artists to circumvent the gatekeepers of the music industry, I’m disappointed that I was only able to go so deep into this project, but I’m encouraged by the fact that in the year since, both Spotify and Apple Music have released artist analytics products, and a number of startups are forming in this space. **Without musicians, we would have no music industry. Let’s put the power back in their hands.**
