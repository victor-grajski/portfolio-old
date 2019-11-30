---
layout: post
title:  "DMV Redesign"
date:   2019-10-08 10:52:01 -0700
categories: jekyll update
permalink: "/dmv"
excerpt: "A redesign of the REAL ID office visit flow for the California DMV."
image: /assets/dmv/splash-screen.png
category: "Product Design"
---

<img src="/assets/dmv/splash-screen.png" alt="splash" />

**[InVision Prototype](https://invis.io/NEU60BEG58U){:target="_blank"}**

## Landing Page
I decided to simplify the appointment landing page by routing most of the help text to the FAQs and bringing the actions to the top of the page. I believe this was the right decision because the amount of text on the page previously obscured what actions the user could take and repeated much of what users can find in the FAQs. I believe something like making an appointment online is a common enough pattern that users don't need a paragraph explaining how to do so.

<img src="/assets/dmv/appointment_system_before.png" alt="appointment-system-before" /> <img src="/assets/dmv/make-an-appointment.png" alt="make-an-appointment" />

## Booking an Appointment
On this screen, and many of the following screens, I separated each step in the process into its own screen and structured the decision process in a Q+A format. I believe this is the right solution to reduce cognitive load per screen.

I also included a progress bar with estimated time remaining in order to give users a sense of where they are in the process now that each screen has been atomized to one step in the process.

Finally, I included info boxes to clarify some of the finer details to the user without overwhelming them with text on the screen by default.

<img src="/assets/dmv/book-an-appointment-before.png" alt="book-an-appointment-before" /> <img src="/assets/dmv/step-one-after2.png" alt="step-one" />

### Choosing an Office
Here I wanted to give users multiple paths to find their office using two common patterns: location and search. I believe offering multiple options is the right solution because users who are comfortable sharing their location, or are in a place where it makes sense to do so, will complete the flow faster. If users don't want to, or it doesn't make sense for them to find an office based on their current location, I wanted to offer a path to finding an office through search functionality.

Once I know the area they're searching in, I decided to show the nearest office and one other office by default. This will keep the cognitive load low while preserving choice for the user. If they'd like, they can tap "More Offices" and more results will appear. I opted to only show one other office by default since most CA residents are most likely to go to the nearest office and may be in practical range of one other offices. But again, I'm still giving the user the option to see more offices if they prefer.

I also believe giving the user the choice between booking the next available appointment right away or seeing more appointment times makes them feel in control of the process while allowing those users who want to complete the flow as quickly as possible a way to do so.

<img src="/assets/dmv/find-an-office-before.png" alt="find-an-office-before" /> <img src="/assets/dmv/find-an-office-after.png" alt="find-an-office-after" />

### Choosing a Time
Here I want to guide the user to booking the first available appointment but also preserve the choice to choose their own time. They can either filter by the time slots available on a given day, or they can filter to which days have a given time slot available. I believe this was the right decision because user conceptualize their availability in different ways and I wanted to preserve that choice. Some users may only be available at a certain time of day or on a certain day.

<img src="/assets/dmv/choose-a-time-before.png" alt="choose-a-time-before" /> <img src="/assets/dmv/choose-a-time-after.png" alt="choose-a-time-after" />

## The Day Of
I decided to create a dedicated page for users to refer back to leading up to their appointment and to use when they check in (the button renders an infobox with a QR code). I also envision a link to this page being sent in the reminder and confirmation email/text message. Having a central place to refer back to reduces cognitive load as users prepare for their appointment and may reduce customer complaints.

<img src="/assets/dmv/confirm-appointment-before2.png" alt="confirm-appointment-before" /> <img src="/assets/dmv/day-of-after.png" alt="day-of-after" />
