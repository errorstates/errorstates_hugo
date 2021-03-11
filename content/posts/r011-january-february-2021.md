+++
title = "Error States Roundup 011, January-February 2020"
date = "2021-02-28T20:34:03-05:00"
publishdate = "2021-02-28T20:34:03-05:00"

description = "Well, January and February were interested, to say the least. For posterity, I've rounded up some of the more interesting things to come out related to the intersection of error handling and politics... as well as updates on the healthcare-x-machine-learning side of things and bitcoin woes."

summary = "Well, January and February were interested, to say the least. For posterity, I've rounded up some of the more interesting things to come out related to the intersection of error handling and politics... as well as updates on the healthcare-x-machine-learning side of things and bitcoin woes. [Continue Reading]"

tags = ["FAANG","Error Handling","AI","Machine Learning","Hacked","Politics","Healthcare"]

[author]
    name = "Roman"

[image]
    src = "/images/roundups/r011.jpg"
+++

!["Roundup"](/images/roundups/r011.jpg)

# Roundup, January-February 2021

Well, January and February were interested, to say the least. For posterity, I've rounded up some of the more interesting things to come out related to the intersection of error handling and politics... as well as updates on the healthcare-x-machine-learning side of things and bitcoin woes.

---

## When "Good, Cheap, Fast" met "Opaque, Difficult, and Unresponsive"

https://www.goodcheapandfast.com/2020 or https://www.johnwdefeo.com/my-work/good-cheap-and-fast -- I think they link to the same place. 

From time to time, I collect stories about how Google (or insert your favorite FAANG+ group member) will roll someone through a completely opaque process of delisting/deservicing someone with little path to recourse. Twitter and Hacker News tend to be the best places to go because of the number of employees that visit the site. From time to time, an employee will respond, escalate an issue internally, and get it resolved. We're not all so lucky. "Good, Cheap, Fast"'s story is a good example of this -- what goes wrong when your presence and web business is essentially turned off by forces beyond your control. There's an example every week, but some have better narratives than others. 

On a related note, here's an interesting (and unfortunate) cascading effect of the same sort from GitHub:

!["On sanctions and cascading logic"](/images/roundups/r011-01.png)

https://mobile.twitter.com/sebslomski/status/1344219609923276801

---

## Medicine's Machine Learning Problem

http://bostonreview.net/science-nature/rachel-thomas-medicines-machine-learning-problem

> As Big Data tools reshape health care, biased datasets and unaccountable algorithms threaten to further disempower patients.

I work in healthcare technology and one of the most interesting things our company chose to do -- contrary to common business trends and the direction of the competition -- was to (a) make AI optional, and (b) use AI tools to augment the caregiver's experience, rather than forcing it on the patients. This leaves people in full control over the experience and able to intervene where and when neccessary. But elsewhere, the trends are not so positive:

> Data science is remaking countless aspects of society, and medicine is no exception. The range of potential applications is already large and only growing by the day. Machine learning is now being used to determine which patients are at high risk of disease and need greater support (sometimes with racial bias), to discover which molecules may lead to promising new drugs, to search for cancer in X-rays (sometimes with gender bias), and to classify tissue on pathology slides. Last year MIT researchers trained an algorithm that was more accurate at predicting the presence of cancer within five years of a mammogram than techniques typically used in clinics, and a 2018 survey found that 84 percent of radiology clinics in the United States are using or plan to use machine learning software. The sense of excitement has been captured in popular books such as Eric Topol’s Deep Medicine: How Artificial Intelligence Can Make Healthcare Human Again (2019). But despite the promise of these data-based innovations, proponents often overlook the special risks of datafying medicine in the age of artificial intelligence.

As always, the main risk drivers are: bad data, inherent biases in the data, a lack of transparency into algorithms, lack of proper clinical input during the development process, centralization of decision-making in a field that requires _more, not less_ individualization and context clues and human-led digging.

---

## That Thing With The Trying to Overthrow the Government

As always, twitter is on point: 

!["Twitter"](/images/roundups/r011-02.png)

https://twitter.com/neurovagrant/status/1346964347684179970?s=20

Related: 

- [70TB of Parler users’ messages, videos, and posts leaked by security researchers](https://cybernews.com/news/70tb-of-parler-users-messages-videos-and-posts-leaked-by-security-researchers/)
- [Why platforms had to cut off Trump and Parler](https://www.theverge.com/22224860/parler-trump-deplatformed-capitol-raid-moderation-censorship-facebook-amazon-twitter)
- [ISP Blocks Twitter and Facebook to Protest Anti-Trump ‘Censorship’](https://www.vice.com/en/article/m7a5ay/isp-blocks-twitter-facebook-protest-trump-ban-censorship)
- ... and some great old fashioned trolling: [Pirate Bay Founder Thinks Parler’s Inability to Stay Online Is 'Embarrassing'](https://www.vice.com/en/article/3an7pn/pirate-bay-founder-thinks-parlers-inability-to-stay-online-is-embarrassing)

!["Pirate Bay trolling"](/images/roundups/r011-03.png)

---

## "The Prepared" Keeps Delivering

> In a twist on the “ [I can’t access my bitcoin fortune because I forgot my password](https://theprepared.us3.list-manage.com/track/click?u=2e2c86e49a5f6d1fd1ab7ce70&id=5f3d5031a7&e=d8caa171eb) ” narrative, we were struck by the story of  [this guy in Wales](https://theprepared.us3.list-manage.com/track/click?u=2e2c86e49a5f6d1fd1ab7ce70&id=474270a46e&e=d8caa171eb) . He requested (and was denied) permission to dig up a local landfill to find a hard drive he threw away in 2013 with 75,000 bitcoin that were “virtually worthless” at the time. Now? They’re worth an estimated $US275 million. Turns out even digital currency can run into physical problems.
As the economy is increasingly driven by the seemingly immaterial forces of financial speculation and big tech, this story is a good reminder that despite how hard you try, the material realities of the world will come into play sooner or later. As the authors of the excellent book  [The Innovation Delusion](https://theprepared.us3.list-manage.com/track/click?u=2e2c86e49a5f6d1fd1ab7ce70&id=da6b5032d2&e=d8caa171eb)  put it: “Computing is surrounded by a set of words that suggest disembodied immateriality, like ‘virtual’ and ‘cyberspace’, but every act we do with digital technologies, from opening an app to searching the Internet, involves some device doing something quite physical, whether in our hand or in a distant ‘cloud’ server.” Sometimes, that physical thing is a literal pile of rubbish. 

It's a bit of a hard turn for most people from the day-to-day content they may be encountering (deep dives into fabbing and drill bits?) but I recommend that everyone subscribe for the consistently gold-nugget observations the team lays down: https://theprepared.org

Related:

- [How weaponizing disinformation can bring down a city’s power grid(PLOS Journal)](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0236517)

---

## From Ben Evan's Observation Files

https://www.wsj.com/articles/how-volkswagens-50-billion-plan-to-beat-tesla-short-circuited-11611073974

> Meanwhile the WSJ has a price on how VW's bad software tripped over its recent EV efforts. I feel rather ambivalent about this. Software is indeed very hard to learn (see Nokia versus iPhone), but I'm not sure how much this is really 'software' versus 'firmware', and how much more important scale manufacturing is.  [Link](https://ben-evans.us6.list-manage.com/track/click?u=b98e2de85f03865f1d38de74f&id=1d2fa7ba0c&e=f33426d29a)

---

## Your AI Monitoring Startup Will Fail

https://www.yesthatblog.com/post/0022-ai-based-monitoring-startups/

> Since 1991 I have been contacted by sales people from startups that use AI to make their monitoring system awesome. [...] Why do these companies fail? None of them made products that actually helped sysadmins (or devops or SREs, etc). They made products that helped what an AI researcher thought would be useful. By definition, an AI researcher does not have operational experience.

and the crux:

> Here’s why your AI-based monitoring startup is going to fail:

> 1. If I have a small system, it doesn’t need AI to help me.

> 2. If I have a big system, should be made up of components that are clearly defined so that I can route alerts properly.

> 3. If I have one NOC for all of my services and they’re chasing their tail trying to figure out root causes and who is responsible for each service… you have a management problem. First of all, NOCs are bad and you are bad for having one. Second, there’s no single root cause. Third, if you don’t know who is responsible for each service, how the hell would an AI know better than you? Get a damn technical project manager to talk with each team and help them get their monitoring and alerting in order.

---

## "Technical issue resolved after '150,000 police records lost' (BBC)"

https://www.bbc.com/news/uk-55672194

> A coding error resulted in records that had been flagged for deletion being lost from the database before checks had been carried out to determine whether they could be lawfully held or not. The error, first reported in the Times, saw data including fingerprint, DNA and arrest histories wiped after being accidentally flagged for deletion. The Home Office said the lost entries related to people who were arrested and then released without further action.

---

## Miscellany

- [Ubiquiti, maker of prosumer routers and access points, has had a data breach (The Verge)](https://www.theverge.com/2021/1/11/22226061/ubiquiti-data-breach-email-third-party-unathorized-access)

- [FTC settles with photo storage app that pivoted to facial recognition... The agency says Ever used customers’ images without their permission (The Verge)](https://www.theverge.com/2021/1/11/22225171/ftc-facial-recognition-ever-settled-paravision-privacy-photos)

> In a 2019 report, NBC News detailed how Ever launched as a cloud storage business in 2013, but then switched to be a facial recognition technology provider four years later because it realized its photo app “wasn’t going to be a venture-scale business.” The report found that the Ever app was using customer’s private photos to train its facial recognition algorithm, which it then sold to clients.

- [Why can 2 times 3 sometimes equal 7 with Android's Neural Network API?](http://alexanderganderson.github.io/engineering/2021/01/23/integer_indeterminism.html)

> It is well-known that floating point matrix multiplication can result in a variety of surprises. But did you know that quantized neural networks are not deterministic as well? A quantized neural network uses integers to multiply weights and activations in a neural network. Thus, the naive logic goes, two and three represented and multiplied as integers should always give the exact same result, namely six.