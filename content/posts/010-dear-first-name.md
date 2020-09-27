+++
title = "010 - Dear %%First Name%%"
date = "2020-07-03T16:00:29-04:00"
publishdate = ""
draft = false

description = "Marketing is all about personalization, but sometimes that goes wrong."

summary = "Marketing is all about personalization, but sometimes that goes wrong. [Continue Reading]"

tags = ["email","marketing","variables"]

[author]
    name = "Roman"

[image]
    src = "/images/010-first-name-cover.jpg"
+++

# 010 - Dear %%First Name%%

!["Dear %%First Name%%, 1"](/images/010-first-name-2.jpg)

Marketing is all about personalization. Reach the right person, at the right time/place, with the right message. Personalized marketing tends to have better conversion rates. So of course, we do personalized marketing.

But sometimes it goes wrong. I've been on the other side of this many times. Making a mistake is easy: a content management system -- say, Mailchimp or Hubspot or something -- gives you the option to add a 'personalization' token. perhaps the user's first name, or their email address. You add it, and it shows up all nice and `formatted`, a visual placeholder. Sometimes, you even add a fallback display (`If first name is missing, then use "there"` as in, "Hi There").

For example, Hubspot:

!["Hubspot"](/images/010-personalize-templates.png)

Or MailChimp:

!["Mailchimp"](/images/010-mailchimp.png)

But maybe you copy that as code. Or a developer goes in and makes a modification. Or perhaps you forgot you CMS' convention and used the wrong code. Or %%First Name%% could be pseudocode from a text document that was overlooked and accidently used. 

Whatever the case is, you send out the email and instead of it looking personalized, it looks like this:

!["Dear %%First Name%%, 2"](/images/010-first-name-1.JPG)

_Sigh._ How are you supposed to know my size, if you don't even know your name?

Anyway, it happens. It's more annoying when a _spammer_ does it (sorry Eric, I have no idea who you are and why you're emailing me), less so if it's a brand that messes up, assuming I expected to hear from them.

Cue my burly army ranger voice: _I've got war stories about this..._ Because it's not the end of a brand's troubles. 

!["Drizzly gets it wrong"](/images/010-drizzly-fail.jpeg)
(This one isn't mine. Source: https://www.linkedin.com/posts/christophschachner_marketing-activity-6673127048275361792-astj/)

If you're working with a self-submitted form, then you can have bad data or formatting if it isn't cleaned properly. It's just as likely that you might find yourself emailing "Hi JENNIFER" or "Hi jennifer", assuming you forgot to add the `style="text-transform:capitalize;"` inline code. 

Sometimes, you get a wise-ass who submits their name as "I'm not telling you!!"... which makes for a funny "Hi I'm Not Telling You!!" email somewhere down the road.  

Or if you're working with a "Full Name" form, you need to be mindful of how the data is being split for personalization. That kind of stuff is hard to write rules around -- it ranges from "Dr." or "Mr." sometimes being the first name, or having "III" being the last name if split by spaces. Never mind the eternal questions about what to do with people with three names. That middle name -- do you hide it? Keep it as part of a last name? First name? It's just bad form design in my opinion.

Next time someone addresses you as "Hi %%First Name%%!", just think of this blog post. 

!["USPS"](/images/010-usps.jpg)
