+++
title = "024 - Integration Testing"
date = "2021-07-11T14:54:05-06:00"
publishdate = "2021-09-05T18:48:42-06:00"
draft = false

description = "On June 17th, HBO accidentally sent out an email meant for only internal developer audiences. This email was an integration test, confirming that the code was running as intended. Except, they sent it out to _everyone_. ... And what is an integration test anyway?"

summary = "On June 17th, HBO accidentally sent out an email meant for only internal developer audiences. This email was an integration test, confirming that the code was running as intended. Except, they sent it out to _everyone_. ... And what is an integration test anyway? [Continue Reading]"

tags = ["Testing","Software","Email","HBO","Intern"]

[author]
    name = "Roman"

[image]
    src = "/images/024/024-hbo-1.jpg"
+++

# 024 - Integration Testing

!["Integration testing"](/images/024/024-hbo-1.jpg)

On June 17th, HBO accidentally sent out an email meant for only internal developer audiences. This email was an integration test, confirming that the code was running as intended. 

Except, they sent it out to _everyone_.

... and the culprit was an intern. Oof.

The internet went wild:

<blockquote class="twitter-tweet"><p lang="en" dir="ltr">We mistakenly sent out an empty test email to a portion of our HBO Max mailing list this evening. We apologize for the inconvenience, and as the jokes pile in, yes, it was the intern. No, really. And we’re helping them through it. ❤️</p>&mdash; HBOMaxHelp (@HBOMaxHelp) <a href="https://twitter.com/HBOMaxHelp/status/1405712235108917249?ref_src=twsrc%5Etfw">June 18, 2021</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script> 

<blockquote class="twitter-tweet"><p lang="en" dir="ltr">Go look up the &quot;Dear Intern&quot; trend on Twitter. It&#39;s people all admitting their mistakes and noting they&#39;re still present/successful. It&#39;s so heartwarming, and I wish society would look more kindly on mistakes in general. We&#39;re all humans, not robots. Well, for now, anyway.</p>&mdash; Threatymology (@threatymology) <a href="https://twitter.com/threatymology/status/1405885473248235527?ref_src=twsrc%5Etfw">June 18, 2021</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script> 

<blockquote class="twitter-tweet"><p lang="en" dir="ltr">Dear Intern, as a young lawyer I proof read a legal brief and filed it with the court. I caught a typo and blindly used the global find and replace function. Pro tip: don&#39;t do that. My brief argued for the rights of &quot;the panties.&quot; Not &quot;the parties.&quot; All 50 pages of it. 🤦🏻‍♀️🩲🩲 <a href="https://t.co/PDJYMXuOlw">https://t.co/PDJYMXuOlw</a></p>&mdash; Suzanne Lovett (@sdtlovett) <a href="https://twitter.com/sdtlovett/status/1405934311048679424?ref_src=twsrc%5Etfw">June 18, 2021</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script> 

<blockquote class="twitter-tweet"><p lang="en" dir="ltr">Dear intern,<br> <br>It’s ok. I dropped a prod database when I was a senior engineer. These things happen more often than you might think. Building good systems is about having resilience against human mistakes. Because we, humans, always make mistakes.</p>&mdash; Jaana Dogan ヤナ ドガン (@rakyll) <a href="https://twitter.com/rakyll/status/1405752437286133760?ref_src=twsrc%5Etfw">June 18, 2021</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script> 

Including an HBO Intern mock account:

<blockquote class="twitter-tweet"><p lang="en" dir="ltr">Excited to announce that the test was a success 🥳</p>&mdash; HBO Intern 🤦‍♂️ (@hbo_intern) <a href="https://twitter.com/hbo_intern/status/1405770278907432962?ref_src=twsrc%5Etfw">June 18, 2021</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script> 

Perhaps because I've used a number of different accounts as HBO's digital offerings have evolved, I got more than one email.

!["Integration testing"](/images/024/024-hbo-2.PNG)

---

As far as corporate error states go, this one was rather innocent. No private information disclosed, nothing too amiss. So what is an `integration test`?

Most software goes through a few different types of testing:

- Unit Testing
- Integration Testing
- End-to-End Testing
- User Acceptance Testing

`Unit Tests` are tests written to validate that a function runs correctly. Given `x` input, we expect `y` output. A lot of unit tests are done by the developers themselves, and best practices mandate that these functional "unit" tests are automated.

`Integration Tests` evaluate how different functions/units come together to perform larger functions. Sometimes this is evaluating literal integrations between pieces (is your function talking to the other vendor?), and other times it tests a feature that is made up of multiple functions. 

`End-to-End Tests` (or Systems Testing) evaluates the complete system, end-to-end. During this testing, the goal is to make sure that _everything_ still works, even areas your code may not have touched. Because of emergent complexity in software development, bugs, defects, and unforeseen behaviors have a way of showing up far downstream from where changes are made. 

For example: a unit test might show a function that works as intended, and the integration test might mean that all of the new units come together as expected. However, if the output of the integration testing has changed, a feature somewhere else might not be able to accept it and _that_ will be the breaking change. End to end tests are long and rigorous for complex software, but aim to catch these emergent issues for both "happy" paths (if everything is supposed to go as it should) and "edge" cases (strange input behaviors that are allowable but uncommon).

`User Acceptance Testing` is the last type of testing. It asks: does the thing that was built actually meet the requirements and acceptance criteria that was defined for it? It might work, but not be accepted by a user. Or -- the user might accept it with known defects because those defects might be out of scope of the original request.

---

So there we have it. Some intern somewhere in the engineering department likely triggered an integration test while having their environment variables connected to the "real" email system, instead of the testing system. And the rest as they say is history. 