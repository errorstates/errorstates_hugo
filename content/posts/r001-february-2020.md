+++
title = "Roundup 001, February 2020"
date = "2020-02-28"
publishdate = "2020-02-28"
draft = false

description = "February Roundup of miscellaneous notes about driverless cars, flawed datasets, and Boston Dynamics."

summary = "Notes from around the internet about driverless cars, flawed datasets, and Boston Dynamics. [Continue Reading]"

tags = ["Round Up","Driverless Cars","Public Infrastructure","Data","Manufacturing","Cloud"]

keywords = []

[amp]
    elements = []

[author]
    name = "Roman"

+++

## Tesla tricked into speeding by researchers using electrical tape
[https://www.cbsnews.com/news/tesla-tricked-into-speeding-by-researchers-using-electrical-tape/](https://www.cbsnews.com/news/tesla-tricked-into-speeding-by-researchers-using-electrical-tape/)

Eisenhower and his ambitious interstate highway system transformed the US into a nation with infrastructure primarily designed around cars and large machinery. As we  roll out more autonomous vehicles and implement machine vision more broadly in public spaces, we're going to again redefine who public spaces are designed for. There's a lot in here, but I don't have enough to write a full exploration yet. 

> McAfee technicians fooled the car into reading the speed limit as 85 miles per hour by placing black tape across the middle of the first digit on a 35 mile per hour sign. That caused the vehicle's cruise control system to automatically accelerate, according to McAfee. The tests involved a 2016 Model S and Model X that used technology made by Mobileye, a division of Intel. Tesla stopped using the company's camera systems in 2016. The newest Tesla models do not use Mobileye technology "and do not currently appear to support traffic sign recognition at all," McAfee researchers Steve Povolny and Shivangee Trivedi wrote in a blog post.

>"Traffic sign fonts are determined by regulators, and so advanced driver-assistance systems are primarily focused on other more challenging use cases, and this system in particular was designed to support human drivers — not autonomous driving," a Mobileye spokesperson said by email. "Autonomous vehicle technology will not rely on sensing alone, but will also be supported by various other technologies and data, such as crowdsourced mapping, to ensure the reliability of the information received from the camera sensor and offer more robust redundancies and safety."

---

## Related: A popular self-driving car dataset is missing labels for hundreds of pedestrians
[https://blog.roboflow.ai/self-driving-car-dataset-missing-pedestrians/](https://blog.roboflow.ai/self-driving-car-dataset-missing-pedestrians/); Related discussion: [https://news.ycombinator.com/item?id=22298882](https://news.ycombinator.com/item?id=22298882)

>We were surprised and concerned when we discovered that a popular dataset (5,100 stars and 1,800 forks) being used by thousands of students to build an open-source self driving car contains critical errors and omissions.
We did a hand-check of the 15,000 images in the widely used Udacity Dataset 2 and found problems with 4,986 (33%) of them. Amongst these were thousands of unlabeled vehicles, hundreds of unlabeled pedestrians, and dozens of unlabeled cyclists. We also found many instances of phantom annotations, duplicated bounding boxes, and drastically oversized bounding boxes.
Perhaps most egregiously, 217 (1.4%) of the images were completely unlabeled but actually contained cars, trucks, street lights, and/or pedestrians.

!["Missing Labels"](https://blog.roboflow.ai/content/images/2020/02/omitted-labels.jpg)

---

## The Prepared (newsletter), 2/17/2020
[https://mailchi.mp/theprepared/nn3lqu5vdp](https://mailchi.mp/theprepared/nn3lqu5vdp)

Some notes from The Prepared. Always insightsful takes.

> **Making & Manufacturing.**
	[Adam Savage made a rickshaw for his Boston Dynamics Spot](https://theprepared.us3.list-manage.com/track/click?u=2e2c86e49a5f6d1fd1ab7ce70&id=0b917a48f4&e=d8caa171eb) , and had Spot tow him around while wearing a top hat. Aside from the obvious observation (that this is a silly project), the bloopers at the end of the video provide a little taste for BD's  [technology readiness level](https://theprepared.us3.list-manage.com/track/click?u=2e2c86e49a5f6d1fd1ab7ce70&id=69ccb56a6a&e=d8caa171eb) ; Spot doesn't seem to really "just work." I also found myself ruminating on how workshops like Savage's are wondrous, enchanting places - and how *fabrication* (the act of converting materials into parts and assemblies) looks almost nothing like *manufacturing* (the act of making a thing, over and over again, in a repeatable and predictable way). I love both of those things, and each of them is visually fascinating, but I try to be cognizant of the spectrum between them.

Also:

> **Maintenance, Repair & Operations.**
	This is slightly old news by now, but [owners of older Haas machining centers are revolting](https://theprepared.us3.list-manage.com/track/click?u=2e2c86e49a5f6d1fd1ab7ce70&id=2d7c7f1de9&e=d8caa171eb)  over lack of product support on older tools (like, 90s and aughts). I have some sympathy for Haas here, but I'm also aware that manufacturers of heavy equipment like Caterpillar and John Deere (note,  [Deere has other *big* issues on maintainability](https://theprepared.us3.list-manage.com/track/click?u=2e2c86e49a5f6d1fd1ab7ce70&id=96935c7d69&e=d8caa171eb) ) keep huge libraries of old casting & forging tools so that they can support ancient equipment. Presumably we'll eventually get to a steady state where control boards are seen the same way mechanical parts are; I wonder whether the end of Moore's law, over which there has been so much hand-wringing, might at least bring some stability to the electronics market and give a little more heft to the argument that electronics are only end-of-life because nobody's willing to pay for them to be resuscitated. 

---

## Cloudflare silently deleted my DNS records
[https://txti.es/cloudflare-deleted-my-dns](https://txti.es/cloudflare-deleted-my-dns)

Interesting from the perspective of error-handling and cloud-services as fundamental communications infrastructure:

> If I intentionally set out to build a horrible user experience I'm unsure if I could top this. I naively expected that I would be notified by email before Cloudflare broke everything. In the absence of that, I would expect to see a notice when I logged in. In the absence of that, I would expect to see a field in the audit log mentioning in human language what happened. In the absence of that, if for some arcane reason Cloudflare is unable to change the format of their audit logs, I would at a minimum expect a message on the audit log page that explained what a deletion logged to 127.0.0.1 means. I registered for Cloudflare with a Gmail address specifically so that I could receive notifications from them if there were issues with my email setup. 

> To add insult to injury I learn that when Cloudflare automatically detects an anomaly with your domain they permanently delete all DNS records. Mine won't be difficult to restore, but I'm not sure why this is necessary. Surely it would be possible for Cloudflare to mark a domain as disabled without irrevocably deleting it? Combined with the hacky audit log, I'm left with the opinion that for some reason Cloudflare decided to completely half-ass the part of their system that is responsible for deleting everything that matters to a user. Because Cloudflare deleted my domain registration I can't change the status from clientTransferProhibited through their dashboard so I don't think I can even leave.

---

## SAP project costs cited in jeweler's bankruptcy filing
[https://www.computerworld.com/article/2530405/sap-project-costs-cited-in-jeweler-s-bankruptcy-filing.html](https://www.computerworld.com/article/2530405/sap-project-costs-cited-in-jeweler-s-bankruptcy-filing.html)

This one is back from 2009 and not entirelty a bug, but still relevant and came in up conversation recently (I'm working with a team to implement an ERP at my day job):

> Shane Co. signed a contract with SAP AG in 2005 for a "highly sophisticated point-of-sale and inventory management system," with an original projected cost of $8 million to $10 million and a one-year rollout schedule, the filing states. But costs ended up skyrocketing to $36 million, and the implementation stretched out to 32 months before the ERP system eventually went live in September 2007.

> The company noted that it subsequently discovered that the new system "did not yet provide accurate inventory count numbers," causing Shane to become "substantially overstocked with inventory, and with the wrong mix of inventory." That added to Shane's capital costs and affected sales for the rest of 2007 and the first nine months of 2008, the court document says.

