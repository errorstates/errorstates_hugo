+++
title = "026 - At The Airport"
date = "2022-01-23T18:49:08-06:00"
publishdate = ""
draft = false

description = "In many regards, airports and flights are perfect places for technology and screens to be introduced and to make a positive impact. Airports are data fiends. Flights are constantly being routed and rerouted, or moved around. Like with any logistics-centric businesses, data -- and more importantly, the showcase of data -- is an integral part of the experience. So when a screen that you're relying on to show you critical information fails, you take notice. And when it happens over and over... well, it's interesting to see the myriad of ways that this tech breaks."

tags = ["Airports","Screens","Error","Broken"]

[author]
    name = "Roman Kudryashov"

[image]
    src = "/images/026/026-flight-error-1.jpg"
+++

I spent a surprisingly large amount of 2021 flying around from place to place, despite Covid being still a very real and present thing. Being in airports was a strange experience -- despite every sign and precaution telling you to avoid crowding and to keep six feet of distance, you were constantly packed like sardines into air trains and walkways and in waiting areas on the flights themselves.

Masks were often surprisingly hard to find, despite every sign telling you to mask up. Yes, of course you already needed to have your own mask coming into the airport, but after breathing into some masks for a hours at a time, nothing felt better than switching it out for something fresher. And every time someone coughed! Like an infectious yawn, a single loud cough had the ability to draw your attention to everyone around you and be extra mindful of everyone's breathing. It was a lot of stress - if I didn't have a good reason to fly (beyond the environmental reasons, of course), I wouldn't have.

But being in an airport was also very interesting from an "Error States" perspective. Everyone's staffing was down, and it wasn't usual to see flight staff running from one gate to another, or delays because someone got sick or wasn't available, or things were backed up in general.

!["Closeup of a update needed"](/images/026/026-flight-error-2.jpg)

!["Closeup"](/images/026/026-flight-error-3.jpg)

But in many regards, airports and flights are perfect places for technology and screens to be introduced and to make a positive impact. Airports are data _fiends_. Flights are constantly being routed and rerouted, or moved around. Like with any logistics-centric businesses, data -- and more importantly, the _showcase_ of data -- is an integral part of the experience.

So when a screen that you're relying on to show you critical information fails, you take notice. And when it happens over and over... well, it's interesting to see the myriad of ways that this tech breaks.

!["When your screen fails"](/images/026/bad-flight-tech-2.jpg)

!["Closeup"](/images/026/bad-flight-tech-3.jpg)

For example, the iPhoto interruption of the Frontier Airlines gate screen would be funny, if not for the completely vintage OS it is running. Other times it's a little more concerning, such as when you're trying to figure out which gate you're at only to learn that the `FidsClient has quit unexpectedly`. Should I be concerned?

!["Buying seats"](/images/026/026-aa-2.jpg)

Other times still, it's just frustrating. I was trying to buy a seat (because apparently many flights no longer come with designated seats, while others like Frontier and RyanAir are two steps away from asking you to bring your own, otherwise it's standing room only), but only half of the process seemed to work. I can imagine the engineers now: "Well, we delivered on the sprint goal of getting billing to work, but having it actually process your change is something we'll tackle next week".

Or from a security perspective, just seeing routers left out for anyone to plug into, or that the security system keeps rebooting.

!["Routers 1"](/images/026/026-router-2.jpg)

!["Routers Closeup"](/images/026/026-router.jpg)

!["Security Reboot"](/images/026/026-general-error.jpg)


None of it was doom-and-gloom level errors, it was still interesting to see all of the different systems at play: Microsoft and Apple were well represented, but so were many custom systems. Some of the error states were so easy to resolve, assuming someone could walk by and restart it, or remote in and click an option. But unless IT staff were walking around and actively seeing this... whose problem is it? Is there a staff portal for you to submit a ticket? 

Here's another frustrating example. I'm trying to order food at the ubiquitous iPads that have replaced front-of-house servers. Aside from taking up space where my plate would be, it's also just not working. Which is extremely frustrating, because it's a simple URL error. Don't try to `http` and `https` at the same time into your AWS buckets! It's one or the other! Worst of all, it's a touchscreen interface but it's been locked down so that I can see the error, but I can't interact with the browser. 

!["Ordering food."](/images/026/026-order-food.jpg)

Here's some more random screens:

!["Scala Screens"](/images/026/026-scala-1.jpg)

!["Scala Closeup"](/images/026/026-scala-2.jpg)

Or a view of random metadata. This flickered onto the screen for a few seconds, then would cycle to the next screen, and the next. Not the worst thing, but distracting... and interesting. I have no idea what's going on here.

!["Scala Closeup"](/images/026/026-metadata.jpg)

Last one, I promise. This was from the flight itself, where IT support can't hear you screen. The unfortunate person in front of my spent at least ten minutes trying to get it to work before giving up. It was a long flight.

!["Just doesn't work"](/images/026/026-broken.jpg)