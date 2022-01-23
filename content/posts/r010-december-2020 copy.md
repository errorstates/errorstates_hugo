+++
title = "Roundup 010, December 2020"
date = "2021-01-03T20:34:03-05:00"
publishdate = "2021-01-03T20:34:03-05:00"

description = "This is for google search snippets."

summary = "This is the preview text. [Continue Reading]"

tags = ["APIs","Error Handling","AI","Ethics","Hacked","Aesthetics"]

[author]
    name = "Roman"

[image]
    src = "/images/roundups/r010.jpg"
+++

This month the SolarWind hack, FireEye hack, and Timnit Gebru's firing made most of the news. 

---

## On Firing Timnit Gebru, Google's AI Ethics Chief

[We read the paper that forced Timnit Gebru out of Google. Here’s what it says. (MIT Tech Review)](https://www.technologyreview.com/2020/12/04/1013294/google-ai-ethics-research-paper-forced-out-timnit-gebru/)

> “On the Dangers of Stochastic Parrots: Can Language Models Be Too Big?” lays out the risks of large language models—AIs trained on staggering amounts of text data. These have grown increasingly popular—and increasingly large—in the last three years. They are now extraordinarily good, under the right conditions, at producing what looks like convincing, meaningful new text—and sometimes at estimating meaning from language. But, says the introduction to the paper, “we ask whether enough thought has been put into the potential risks associated with developing them and strategies to mitigate these risks.”

> Large language models are also trained on exponentially increasing amounts of text. This means researchers have sought to collect all the data they can from the internet, so there's a risk that racist, sexist, and otherwise abusive language ends up in the training data.

> An AI model taught to view racist language as normal is obviously bad. The researchers, though, point out a couple of more subtle problems. One is that shifts in language play an important role in social change; the MeToo and Black Lives Matter movements, for example, have tried to establish a new anti-sexist and anti-racist vocabulary. An AI model trained on vast swaths of the internet won’t be attuned to the nuances of this vocabulary and won’t produce or interpret language in line with these new cultural norms.

> It will also fail to capture the language and the norms of countries and peoples that have less access to the internet and thus a smaller linguistic footprint online. The result is that AI-generated language will be homogenized, reflecting the practices of the richest countries and communities.

> Moreover, because the training data sets are so large, it’s hard to audit them to check for these embedded biases. “A methodology that relies on datasets too large to document is therefore inherently risky,” the researchers conclude. “While documentation allows for potential accountability, [...] undocumented training data perpetuates harm without recourse.”

See also:

- [From whistleblower laws to unions: How Google’s AI ethics meltdown could shape policy (VentureBeat)](https://venturebeat.com/2020/12/16/from-whistleblower-laws-to-unions-how-googles-ai-ethics-meltdown-could-shape-policy/)

- [Google told its scientists to 'strike a positive tone' in AI research - documents (Reuters)
](https://www.reuters.com/article/us-alphabet-google-research-focus-idUSKBN28X1CB)

---

## AI, More Broadly

[Co-op is using facial recognition tech to scan and track shoppers (Wired)](https://www.wired.co.uk/article/coop-facial-recognition)

> Every time someone enters one of the 18 shops using the tech cameras scan their faces. These CCTV images are converted to numerical data and compared against a watchlist of ‘suspects’ to see if there’s a match. If a match is made, staff within the store receive notifications on smartphones.

> “The system alerts our store teams immediately when someone enters their store who has a past record of theft or anti-social behaviour,” Gareth Lewis, Southern Co-op’s loss prevention lead wrote in a blog post on the Facewatch website. The post is the only public acknowledgement of the use of the technology and Lewis says it has been “successful,” with the tech being deployed in branches where there are higher levels of crime.

See also New York Time's interactive investigation of AI-generated faces, [Designed to Deceive: Do These People Look Real to You?](https://www.nytimes.com/interactive/2020/11/21/science/artificial-intelligence-fake-people-faces.html)

> These people may look familiar, like ones you’ve seen on Facebook or Twitter. They look stunningly real at first glance. But they do not exist.

Also: [I asked GPT-3 for the question to “42”. I didn’t like its answer and neither will you. (Medium)](https://muellerberndt.medium.com/i-asked-gpt-3-for-the-question-to-42-i-didnt-like-its-answer-and-neither-will-you-33f425a4d60f)

Also: [2020’S ‘THE DOG ATE MY HOMEWORK’ UNIVERSAL SCAPEGOAT: ‘THE ALGORITHM’ (Daring Fireball)](https://daringfireball.net/linked/2020/12/19/stanfords-dog-ate-their-vaccine-or-something-something)

> Stanford Health Care apologized Friday for a plan that left nearly all of its young front-line doctors out of the first round of coronavirus vaccinations. […] The “residents” — medical school graduates who staff the hospital for several years as they learn specialties such as emergency medicine, internal medicine and family medicine — were furious when it became clear that just seven of the more than 1,300 at the medical center were in the first round for vaccinations. Also affected were “fellows,” who work in the hospital as they train further in sub-specialties, nurses and other staff.

> Residents across specialties had just been asked to volunteer for extra intensive care unit work in preparation for a surge in covid-19 patients.

> An email to pediatrics residents and fellows obtained by The Washington Post said that “the Stanford vaccine algorithm failed to prioritize house staff,” as the early year doctors are known collectively.

---

## On SolarWinds and FireEye Getting Hacked

[Why the US government hack is literally keeping security experts awake at night (CNN)](https://www.cnn.com/2020/12/16/tech/solarwinds-orion-hack-explained/index.html)

[Microsoft unleashes ‘Death Star’ on SolarWinds hackers in extraordinary response to breach (GeekWire)](https://www.geekwire.com/2020/microsoft-unleashes-death-star-solarwinds-hackers-extraordinary-response-breach/)

[U.S. cybersecurity firm FireEye discloses breach, theft of internal hacking tools (Reuters)](https://www.reuters.com/article/fireeye-cyber-idUSL1N2IO2EI)

[Suspected Russian hackers spied on U.S. Treasury emails - sources (Reuters)](https://www.reuters.com/article/us-usa-cyber-treasury-exclusive-idUSKBN28N0PG)

---

## Digital Infrastructure

[How SEO Is Gentrifying the Internet (Current Affairs)](https://www.currentaffairs.org/2020/12/how-seo-is-gentrifying-the-internet/)

[Framing a privacy right: Legislative findings for federal privacy legislation (Brookings)](https://www.brookings.edu/research/framing-a-privacy-right-legislative-findings-for-federal-privacy-legislation/)

---

## Filed under aesthetics

[Is Glitchcore a TikTok Aesthetic, a New Microgenre, or the Latest Iteration of Glitch Art? (Pitchfork)](https://pitchfork.com/thepitch/is-glitchcore-a-tiktok-aesthetic-a-new-microgenre-or-the-latest-iteration-of-glitch-art/)

![Glitchcore](https://media.pitchfork.com/photos/5fb6d958123fe4fec44c0962/2:1/w_2560%2Cc_limit/Final_Scale.gif)

---

## Error Handling is Hard

I'd like to do a deep dive into some different ways of handling errors across programming languages, but this so far is the best example of Error State-specific coverage I've seen, here re: Rust and Haskell:

> Like so many other things, error handling ultimately is a trade-off. When we're writing our initial code, we don't want to think about errors. We code to the happy path. How productive would you be if you had to derail every line of code with thought processes around the myriad ways your code could fail?

> But then we're debugging a production issue, and we definitely want to think about errors. We curse our lazy selves for not handling an error case that obviously could have arisen. "Why did I decide to abort the process when the TCP connection failed? I should have retried! I should have logged the address I tried to connect to!"

> Then we flood our code with log messages, and are frustrated when we can't see the important bits.

> Finding the right balance is an art. And typically it's an art that we don't spend enough time thinking about. There are some well-established tools for this, like runtime-configurable log levels. That's a huge step in the right direction.

[Error Handling is Hard (FP Complete)](https://www.fpcomplete.com/blog/error-handling-is-hard/)

See also [this discussion components versus tools on hacker news:](https://news.ycombinator.com/item?id=25252089)

> Hinges - like everything else on CarpentryHub - are either in a state of permanent development or abandoned. So you design your project for Hinge 13.2, but then you come back a month later - just before you open your Etsy store - and discover that Hinge x.n has now become HingeOS, which is breaking change.

> It also has its own HingeAPI, which is poorly documented, somewhere.

> You were used to Hinge's ScrewHole 5.3. But that's now buried inside HingeAPI, which calculates your project budget and lifetime carbon footprint for you, but no longer accepts external screwhole positions, because it works its own values from the complex project specification you have to supply - defined in DirkLang, which is a hot new carpentry specification language only ten people know, and replaces HammerLang, which was fifty five years old and very popular but had a lot of frankly questionable design choices.

> And the values HingeAPI returns aren't mutable, because mutability is bad practice.

And also: [regarding API degradations](https://news.ycombinator.com/item?id=25466031)...

> Flush Button Push Detected
> Contacting Toilet Cloud Server...
> 503 Service Unavailable
> Alert User: "Water Unavailable, Please try Later."

![flush api](/images/roundups/r010-flush-api.png)

---

## ... in the Twitter sphere:

Whoever registered the company name with valid XSS injection and caused @companieshouse to sent this email: I will buy you a drink [Twitter link](https://mobile.twitter.com/jonty/status/1319325590223204352?mc_cid=48742e06fe)

![xml injection](/images/roundups/r010-xml-injection-2.png)

---

TIL: Google’s Pixel 2, released in 2017, is now unsupported and gets no new software updates.  Given today’s security environment, I guess that means I should recycle it. Apple just released iOS 12.5 for devices shipped in 2013. [Twitter Link](https://twitter.com/benedictevans/status/1339644642938269697)

![support](/images/roundups/r010-google-vs-apple-support.png)

---

I wonder how much of UK-EU trade deal has been copy & pasted from old 90s documents 🤔 p921 refers to Netscape Communicator 4.0 as a "modern e-mail software package" (it was last updated in 2002) and recommends SHA-1 as a hash algorithm (deprecated by NIST in 2011 as insecure) 
[Twitter link](https://mobile.twitter.com/paulmaunders/status/1343143578147684357)

![support](/images/roundups/r010-brexit.png)






