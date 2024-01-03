---
title: "On Subscriptions (Part One)"
date: "2021-06-22"
categories: 
  - "technology"
tags: 
  - "drafts"
---

Over the last few years, the number of subscriptions I have for apps has grown by quite a bit, and a lot of apps that I’d previously bought on their own have transitioned to subscriptions. I wanted to spend some time on my thoughts on what I’ve found worth it and why that might be; perhaps as an encouragement to others to try certain apps in spite of their subscriptions, or maybe as a bit of catharsis to justify what I spend on apps that will just go out to the void.

As it was well-put on [Mac Power Users](https://www.relay.fm/mpu/459), there’s a lot of good reasons for an application to change their business model to be based on subscriptions. It creates sustainable income for developers when the current models are failing. Apple takes quite a bit of blame for this in their lack of support for the traditional model of versions and upgrades with the App Store on both Mac and iOS. Additionally, Apple has encouraged it via a better revenue split for developers on the second year of any subscription.

But as a user, each subscription has to be justified. In theory, any purchase should be justified, but up to a certain amount, I personally have a pretty low bar for an app purchase if I think I ever might get use out of it. But if I have to pay for it again next year, I have to ask myself if it’s worth that money _this_ year.

And even for apps I know I get use out of, it’s not always an obvious slam-dunk for a subscription. If I can see how the feature roadmap benefits me, then I might be more inclined to go forward with a subscription. Or if I can see where the recurring costs (usually in server hosting) for a developer are, then I’m more sympathetic. But I know I’m not totally consistent in my reasoning — and my choices might be totally different from someone else in very similar shoes, and if someone were trying to break these down as a market study, it might be totally useless data.

### Great Subscriptions

The first app I can remember subscribing to is **[Bear](https://bear.app)**. I was unhappy with how I was using Apple Notes, and an [article on The Sweet Setup](https://thesweetsetup.com/use-day-one-aside-differences-bear-day-one/) persuaded me to give it a whirl. At $15/yr, Bear became a somewhat unfair measuring stick for the value of other apps. It’s usable without that subscription, but only technically — sync is locked behind that paywall.

Bear doesn’t run its own servers for that sync, but rather syncs through iCloud. The subscription entirely goes to the cost of development, but it’s a totally reasonable fee to me. Bear launched originally as an upfront purchase app before being one of the earlier popular apps to have a subscription fee. I never got in before it was subscription-only.

Some Bear users are a bit upset that updates aren’t faster, but the developers are actively working on a [major rewrite of the editor](https://beta.bear.app/latest) and are very responsive. Many users want to see a web version which is apparently coming, but is probably more than a year off. I’m very happy with the way things are in Bear, though, even if I will appreciate a lot of the new features coming.

**[Overcast](overcast.fm)** is the app I could most easily get away without subscribing to. Its free version is more than comprehensive, and if I needed to save the $10/yr all of the sudden, I could live without its premium features. It’s supported by some very reasonable ads without the subscription, reasonable enough that back when I was on an iPhone 6 Plus, I actually kept the ads on after I was subscribing because I felt the UI was more balanced with them on. Since upgrading to an XS Max in 2018, I’ve turned them off, but they’re just ads for podcasts.

I don’t pay that subscription to get rid of the ads, obviously. I pay it for the very useful feature of being able to upload any audio file I want and listen to it with Overcast’s powerful Smart Speed (and other audio adjustment) features. This is most useful in using [`youtube-dl`](https://youtube-dl.org) to pull the audio from a video that I really only want to listen to, and being able to consume it faster and without giving it more attention. There’s a post brewing on that workflow.

Jumping up in price, [**Drafts**](https://getdrafts.com) has, since moving to a subscription model, been $20/yr, but [starting in 2021](https://twitter.com/draftsapp/status/1335992814576996355) is now $30/yr for new subscribers (I’m grandfathered in at $20/yr). I wrote [at the end of 2018](https://mrehler.com/2018/12/26/2018-recap-apps-that-i-didnt-get-in-2017/) about the place I found for Drafts in my workflow, and it’s an app that I’m not done [writing about](https://mrehler.com/tag/drafts/). I can’t really do it justice on my own to explain, and I don’t have easy links compiled to break down why it’s so useful, but Robby Burns wrote a [great review](http://www.robbyburns.com/blog/app-of-the-week-drafts-5) when it launched version 5, and did a recommendable [podcast episode](http://www.robbyburns.com/robbyburnsandfriends/writing-with-drafts-featuring-greg-pierce-season-3-episode-5) with its developer Greg Pierce.

The subscription funding of Drafts has allowed Greg to go nuts with his development pace. It’s now his full-time job, and he’s put in incredible and powerful features regularly. The features that this subscription adds beyond the free version are really essential for anyone who’s serious about pushing the app to its limits.

I have a love-hate relationship with my email app of choice, **[Airmail](https://airmailapp.com)**. When I started using it during my student-teaching, it helped me get my email life under control. The number one feature of it to me is that you can extract a URL scheme for _every_ message on both macOS and iOS.[\[1\]](1 "see footnote") This is incredibly valuable for being able to point to a message from another app; I can have a Bear note on a certain topic and reference the emails on it. I can have an OmniFocus task to reply to an email or follow up on the action of an email (when that’s the appropriate way to manage it, which it often isn’t). Airmail has a bunch of other features I like, but none of them are as important as its URL schemes.

It has a Markdown email composer (on Mac but not on iOS) which lets me write long informational emails to families in Drafts with appropriate links and styles in Markdown, tag them and archive them in Drafts (rather than deleting the Draft) so I can look at it in future years and reuse parts of it, and then send it off with as little friction as possible. The only problem is that there’s terrible bugs in both their raw HTML editor and Markdown composer; I’ve solved the Markdown bug, but fixing the bug requires me to go through an annoying process every time Airmail updates.

When I started using Airmail, it was a one-time purchase, and despite its many flaws, I was happy to pay a subscription of just $10/yr (in hopes that it would solve some of the flaws and keep development ongoing; only the latter has worked out). When I bought it, it worked great with Alfred’s incredible file attachment actions (thanks to custom work from Alfred’s devs), but it has [been broken for some time now](https://www.alfredforum.com/topic/14086-alfred-no-longer-attaching-files-in-airmail/) and is another reason I’ve thought of leaving Airmail.

**Day One** isn’t one of the top apps I use, but it has changed how I think about buying apps. I bought it on macOS as a standalone app initially, and after trying to push myself to get into journaling, gave up on it. At first, I felt a bit stung by the app; I thought it was essentially just a glorified notes app, storing text files as a “journal,” not really seeing the utility in it. I wasn’t yet into Markdown, and I didn’t bother to pick up the iOS app, feeling that it wasn’t worth another $10 to me.

Somewhere down the road, though, my feelings about it changed. It was [that Sweet Setup article I’d already mentioned](https://thesweetsetup.com/use-day-one-aside-differences-bear-day-one/), and something about the notion of being able to just take pictures of birthday and Christmas cards into Day One and chuck the physical versions sounded freeing. The notion of going back really began to click, and on top of that idea of putting physical things into Day One, I started to actually get into journaling.

In between I had originally bought it and had this change of heart, though, Day One shifted to a subscription model. Having not picked up the iOS app originally, if I wanted it to sync with iOS, I had no choice but to go forward with the subscription. I think at the time, my calculus was that if I had bought the iOS app originally, the subscription wouldn’t be necessary for my needs at all, which has made me _much_ more willing to jump on upfront purchase apps I see. I’ve seen a lot of them, whether they were of interest to me or not, move to subscription pricing over time, and there’s often a benefit to previous purchase-users if it later goes to subscription pricing. I’m paying $25/yr for Day One; for those who had bought the initial Mac app, they have offered that as a discount from their standard $35/yr for everyone else, which I appreciate.

Which brings me to Fantastical, the app that initially inspired to write this article quite awhile ago.[\[2\]](2 "see footnote")

#### Fantastical

When I was growing up, I had an email address from around the age of seven, I would guess. I remember loading that email address into Microsoft Outlook the day I finally got it (I played with Eudora instead of Outlook Express as a child on the versions of Windows that had it), and I was hooked. I fantasized about being an adult who could actually get to use the cool features involved in Outlook’s calendaring system for comparing availability. It seemed _so_ neat.

I was a weird kid, but it might have something to do with how much I love apps like OmniFocus today.

For the longest time, I used my calendar app on my smartphone and then eventually on my Mac (usually the stock calendar app) I used it just to manage events that were exceptions. I needed to be able to see at a glance when I’d have a doctor’s appointment coming up later in the month, or when a concert was. There was, in essence, one way I could manage my calendar effectively, and that was the most worthwhile one to me. I knew my daily schedule, so I wasn’t going to use my calendar for that; if I did, I would wind up ignoring my calendar app most of the time, and it would be a slog to find the exceptional events that I needed to stay apprised of.

When I bought Fantastical for Mac, it changed the way I was able to actually use calendars in my life. There are a whole host of great features in the app, but the biggest to me has always been its calendar sets feature. One set could be for the events I just described and another could be for my class schedule. Or for [timeblocking](https://www.macsparky.com/blog/tag/hyper-scheduling).[\[3\]](3 "see footnote") Or my school’s activity calendar. Or, you know, all of the above with me quickly jumping between each one with an easy shortcut.

There’s other great features to Fantastical too — its natural language input and support for dumping into that natural language input from outside sources like Drafts saves a lot of time — but calendar sets on its own made it worth the $50 cost of Fantastical 2. When Fantastical 3 came out and pivoted to a subscription, they also brought a bunch of other [great new features](https://www.macworld.com/article/3532431/fantastical-3-for-ios-review.html), including calendar sets on iOS, and it was a no-brainer. Some of these features require a server-side component on their end (like their new “proposed date” feature) or API access to third-party data that the developers are paying for (like integrated weather data), which further helps me justify the cost to myself, but I think I had subscribed before I’d read about those features. Recently they also added access to the new premium features in their excellent contacts app [Cardhop](https://flexibits.com/cardhop) to the same subscription bundle at $40/yr.

I wanted to lay these out for a whole host of reasons including trying to help others justify subscribing to apps that they might have, but my greater motivation was to lay out the case for what I _don’t_ subscribe to, with one app in particular in mind. Looking at my word count, though, I better split that off for a [separate post](https://mrehler.com/2021/06/30/on-subscriptions-part-two/).

* * *

1. For brevity’s sake, I won’t name iPadOS separately from iOS, but I mean to include it every time I say iOS.  [↩](1 "return to article")
2. Somewhere over a year ago. It’s been hard to write.  [↩](2 "return to article")
3. I’m not doing timeblocking in any super meaningful sense, but I’ve dabbled a bit over the last few months. I have a dedicated calendar and calendar set for it, regardless.  [↩](3 "return to article")
