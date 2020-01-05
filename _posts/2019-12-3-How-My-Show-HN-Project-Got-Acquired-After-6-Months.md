---
layout: post
title: How My Startup Got Acquired After 6 Months
---

_I couldn’t find the service I needed, so I built it for myself. And that was the start._

<div>
  <a style="display: flex; align-items: center;" target="_blank" href="https://marker.medium.com/how-my-show-hn-project-got-acquired-after-6-months-954f81ca6a18">
    <h2 style="margin: auto">Featured in:</h2>
    <img src="{{ site.baseurl }}/images/marker-logo.png" alt="trennd-marker" width="150px" />
   </a>
</div>

![How-My-Show-HN-Project-Got-Acquired-After-6-Months-Hero]({{ site.baseurl }}/images/1_dNYHIevehfo4Vw1nprlVBQ.jpeg)

_That’s me (right!) at a Japanese temple for New Year’s. That dragon is supposed to give you luck :)_

### Short version

👨‍💻 Spent two months building an app to detect trends.

🙂 Launched as a Show HN and reached #1 on Hacker News (briefly!).

📈 Another four months growing and improving.

🐦 People continued to like and tweet about the project.

🤯 Failed to monetize.

🎉 Enough traction to get acquired by Brian Dean, founder of [Backlinko](https://backlinko.com/).

🕺🏼 New focus, name, and design overhaul: 👉 [ExplodingTopics.com](https://explodingtopics.com/)

### Long version

I should preface this by saying that I was tremendously lucky with how things turned out, and I’m not recommending this as a reproducible guide for anyone.

Instead, I’d like to give thanks to the people who supported the project — all those good folks on Hacker News, Indie Hackers, and even Reddit.

And personal shoutouts to [Vincent of Threader](https://threader.app/) (who convinced me to write this story!), [Adrian Love](https://www.linkedin.com/in/adrian-love), Daniel Eckler, and my wife, Akane.

All your feedback helped to continuously improve the project, and your encouragement was great fuel in the absence of revenue.

### How it started

I began work on Trennd.co in April while living in Japan. Back then, it was called TrendList.io.

I started to realize that it’s 100 times easier to bootstrap a profitable online business if you ride a big market trend. Jump on the opportunity before the competition gets too fierce.

A great example of this is Jon and Justin at [Transistor.fm](https://saas.transistor.fm/), who spotted a growing B2B market for podcast hosting and bootstrapped a SaaS for it.

Another classic example: Pieter Levels tapped into the digital nomad and remote work trend while scratching his own itch with [Nomad List](https://levels.io/product-hunt-hacker-news-number-one/) and Remote OK.

Market awareness and market timing were both critical for these guys. On top of execution skill, of course.

But businesses also take years of sales, marketing, and general hard work even after you’ve launched. I’d like to know that life force is going into a growing opportunity, not a shrinking one.

I needed something that could surface opportunities by automatically monitoring the web for new topics so I can then plug them into Google Trends.

Heck, it could even check Google Trends itself so I don’t have to.

I needed a shiny new app or tool to play with. 😛

But I couldn’t find anything, so I started to build it for myself.

The first version was literally just a CLI tool that output trend graphs to the console.

I thought I might as well package it as a B2C SaaS product. But whoa no, not another sales grind. Especially B2C.

Let’s just put it up for free and see if I can even build an audience (basically an email list) around it first.

As I proclaimed on the about page, “Revenue is obviously at zero right now. It will likely stay there for a while. Probably forever.”

Not wanting to miss the opportunity to try a fancy new web stack, I wrapped the tool up into a [NextJS](https://nextjs.org/) web app. This choice was primarily to capitalize on the out-of-box server-side rendering it offers. That way, I could actually get this project to rank properly on Google for all the various trends.

I listed Trennd in early May (way before it was finished) on Product Hunt’s Ship service. Admittedly though, I probably should’ve done much more than this and actually talked to potential users/customers before writing any code.

But I was very bullish on the concept since I was building Trennd to solve my own problem. 👹

![trennd-product-hunt-ship]({{ site.baseurl }}/images/1_MJH0oWpKXo20PakeR961ZQ.png)

But with a total of 153 subscribers from PH Ship two months later, it definitely felt like there might be more cost-effective ways to acquire initial users than the $80 per month there. But the brand exposure and potential support from those guys on launch is still valuable.

By May 20, I felt I had something that I could finally start to show people.

But around the same time, I also realized that Trend List was the brand name of Trendlist.org. This is a contemporary graphic design site with a domain authority of 38 and a huge presence on Google SERPs. I really didn’t want to compete from day one just to show up on Google when people search the brand name.

![trendlist-serp]({{ site.baseurl }}/images/1_kZLsWOIFYNohjPhR8As77g.png)

Though maybe I was a wimp and should have fought them for Trend List brand-name dominance.

Anyway, I found three other names that I’d be more than happy with: Trendful, Trennd, and Trend Geek. I threw Nice Trend Bro into the running at my wife’s encouragement.

Then I realized this rebrand could be a fantastic marketing opportunity in itself. So I decided to run a public vote on the new name via twitter poll as a fun and novel way other people could get involved. Plus this way I’d ensure it’s a solid name that works for everyone.

With the Twitter poll underway for a week, I wanted to capitalize on this seven-day window and get as many votes as possible.

## Reddit prelaunch

I quickly got it up on Reddit as an initial prelaunch. I mainly wanted to get some initial users to help iron out any wrinkles and bugs and to point out any big holes in terms of functionality.

And as a professional “wantrepreneur,” I’m often lurking on r/entrepreneur and thought the business-minded folks might find Trennd useful there.

But I went in with my guard up. I know full well these guys will chew you up and spit you out in an instant if they sense you’re there solely to promote.

So I found 57 of the most interesting trends I had at the time and used them as a shield going into the post. I made sure to provide value first and ask for feedback second. I stuck around the comments section all day, replying to everyone who took the time to comment.

![trennd-reddit]({{ site.baseurl }}/images/1_9IwTDAOi13xcPcTjNQoq9A.png)

The response to this Reddit post was huge! It received more than 500 upvotes across three subreddits. One kind stranger even gave me Reddit Gold.

In my book, Reddit Gold = Validation. Listen up PG 😘

In terms of numbers, Reddit brought:
* 80 email subscribers
* 50 user sign-ups
* 1,000 traffic

Not a bad start.

I also got a huge amount of awesome feedback on how I can improve the app and make it more valuable. Like requests for:
1. Better data granularity for shorter time frames.
2. Enabling keyword trends as well, not just Google Topics.
3. Plus dozens of smaller things, like moving the trend close button to the top right so it’s easier to click on mobile.

After this Reddit success, the twitter poll had more than 100 votes for the new name. It was a close run between Trendful and Trennd.

And somehow Pieter Levels came across Trend List, loved the concept, and voted for the name Trennd!

![trennd-twitter-poll]({{ site.baseurl }}/images/1_rg_Y1cUko94Wn_QtRYOYyg.png)

I’m a huge fan of Pieter Levels and Nomad List. I was watching his Bali video about his maker journey literally days before starting Trend List! So, for him to vote and like the idea was both uncanny and amazing.

In the end, the name Trennd won by a small margin.

Following all this initial traction, Trennd was featured on Harry Dry’s killer [Marketing Examples](https://marketingexamples.com/) blog.

![marketing-examples]({{ site.baseurl }}/images/1_xam1tdaWi2lfQxIweX4dKA.png)

I also made the front page of Indie Hackers with the top milestone. Love the IH community, so this was a big deal to me!

![indie-hackers]({{ site.baseurl }}/images/1_URtMgiMLp7v8VDof3lpfVA.png)

After the first five weeks, I was absolutely chuffed with the results. (That’s British slang for “very pleased”!)

I hadn’t set any goals, but 353 email subscribers were way beyond anything I expected.

And I was even more pumped that the initial feedback was so overwhelmingly positive.

I’ve made some other small products, but they were like trying to push a massive boulder uphill. Every time I stopped pushing for new customers, it would roll back down on me. Old customers would churn and weren’t replaced.

But this one felt obviously different. It was the first thing I made that people just shared automatically, and it kind of took flight by itself.

And with an email list in the hundreds, I started a weekly email newsletter called Trennds for the Weekend. My primary goal was to make no-fluff, straight-to-the-point emails with a carefully curated list of the most interesting and fresh trends each week.

![trennd-newsletter]({{ site.baseurl }}/images/1_brqSbKjHKaOa6uF-biJhrg.png)

The newsletter was the one thing I made sure happened every week. It was great motivation to get things done to have something to talk to the readers.

Plus, it was an invaluable way to keep in touch with Trennd’s growing audience and have an open channel for feedback. If I started to go in a wonky direction in terms of trend quality, web design, email format, bugs, or anything, really, somebody would usually let me know via an email reply and help to straighten the ship’s course.

Next up was a Show Hacker News launch, which I expected to be a giant flop, as most things usually drown in the noise.

## Show HN launch

Friday at 10 p.m., I’m at my desk in Japan, ready to post to Hacker News. My wife had already gone to bed, and I figured this was the best time to post since people were awake in both the United States and Europe. Plus, I could reply to any comments and keep check on things through Saturday morning JST if necessary.

I drafted my opening thread comment and hit submit.

“Sorry, your account is too new to submit this site.”

Oh, man. I’d been thinking about this submission all day, and I couldn’t even post. 🤦🏼‍♂️

Anyway, I emailed the mods at Hacker News to explain, and they very quickly and kindly marked it ready to go through. My account was made in 2017, but it turns out that “too new” can also mean not having participated much in the community.

Flash-forward to the following Friday. This time, it went through.

We made sure to phrase the title to resonate with the audience. On Hacker News—and in most places, I suppose—simple, clear, and humble work best. this is where fellow indie maker Vincent was awesome: He helped me get this title spot-on, along with a bunch of other great advice that made a huge difference.

The post immediately moved onto the Best of Show HN page and then quickly onto the main page.

![trennd-hacker-news]({{ site.baseurl }}/images/1_6ZnYwtKn47fjnUQbU6bIsw.png)

Traffic increased to 400 concurrent users on Trennd, and we briefly peaked at number one.

![trennd-hacker-news-ranking]({{ site.baseurl }}/images/1_4S9sMZxLJIMUfujogzGJnA.png)

It was at this point that Trennd got the infamous “Hacker News hug,” and the site died. The free MongoDB Atlas database plan did not appreciate this flood of connections. I had a frantic 15 minutes where the website was down while I upgraded to the paid tier.

It’s a shame that I lost this quarter-hour of Hacker News prime time. I’ve since implemented some server-side caching that prevents the database from getting hammered.

But since I recovered quickly, we remained near the top of the front page for 12 more hours, which is good enough for me. Let’s not be greedy. 😛

I manned the comments section into the early hours of the morning and got some great discussion and a tremendous amount of positivity from the crowd.

## Twitter bonanza

Just as I started to think everything was over and we were back to normality, the buzz started to spill over and have a huge domino effect onto Twitter.

Dozens and dozens of people tweeted about Trennd.

Thankfully, I’d updated the Twitter preview image beforehand. (Thank you Michael!). There was a pretty placeholder image and sweet description when dozens of people shared and tweeted about Trennd.

And then, the cherry on top of it all was that Rand Fishkin of Moz tweeted about it! Unbelievable! This made my month. 🍒

![trennd-rand-fishkin]({{ site.baseurl }}/images/1_1A4lpTM21lCJrVI_eBsexA.png)

The number of likes and retweets on the back of this was insane. I’m a Twitter newbie, so to get this kind of exposure blew my mind! 🤯

It also led to us getting picked up by the Hacker Newsletter and Kottke.org, which drove some good traffic our way.

![trennd-analytics]({{ site.baseurl }}/images/1_JBxCnE4AysMjHvtjJJSSfg.png)

All this combined to rocket us above 2,000 email subscribers:

* Subscribers: 2,163 🎉
* Visitors: 28,353 🕵️‍♀️
* Pageviews: 124,026 👀

It was really cool how ready people were to contribute and add trends of their own. It confirmed my hypothesis that we could crowdsource the surfacing of new trends to some extent, similar to how Product Hunt crowdsources new products.

But with this came the issue of quality control. One visitor, for example, added “donkey porn” as a new trend, and it may well be trending, but I had to moderate it away. 🤫

At this stage, I felt I’d truly validated interest in the project with more than 2,000 subscribers. Marketing to get another X-hundred subscribers wasn’t going to change anything.

I needed to make the platform more powerful, so I held off on a Product Hunt launch, thinking I’d keep that powder dry.

## Monetization (or lack thereof)

I also started to think long and hard about how to monetize the site at this time. I needed it to at least pay some of its own bills and maybe even some of mine!

In the medium to long term, I knew a premium version of Trennd was the way to go.

But I couldn’t figure out what this should look like, and I wanted to do it right.

There’s no point damaging hard-earned goodwill by pushing out a rushed premium product too soon or something that’s the wrong fit.

Somebody did ask for a “private Trennd dashboard,” where they could favorite trends and get personal alerts. They even said they’d pay $100 to $200 per month for it. Turns out, they found Trennd immensely valuable to discover new programming languages sooner so they could make Udemy courses around them. (Being the first to get a course out and get good reviews is like a winner-take-all market and can be very profitable.)

But to me, all the value seems to be in the trends themselves and spotting hotter trends sooner, not the ability to put certain ones into a personal dashboard. Users would just use the free version! Plus, how many tech-course creators are out there? For better or worse (I think better!), I dismissed it as a dead end.

Instead, I began to look for a community or affiliate sponsor and started to have pricing conversations with people, even though I was still small fry in terms of traffic and a few thousand email subscribers.

I managed to set up a nice sponsorship “swap” with Unreadit (which is awesome—check it out!). That was a good fit that worked out well for both of us.

It drove a bit of traffic and some new subscribers and gave me some stats about how well Trennd sponsorship slots converted for future potential sponsors. But it didn’t bring in any cash money since it was just a swap.

![trennd-sponsor-swap]({{ site.baseurl }}/images/1_7hUqgZtsgUUO9azxDCpSXA.png)

Having that deal in place, however, did give me an excuse to scuttle back into my code cave. 🦀

## Code cave

This was with the view to making Trennd more robust and sustainable for the long term.

The number one challenge was and still is the noise-to-signal ratio. Nobody wants to click through page after page of trends to find the ones that are relevant to them. They need to be able to slice and dice the trends in more ways and dimensions that are relevant to them.

I hunkered down in my little white room in our Japanese “mansion” (which in Japan basically means an apartment).

![trennd-mansion]({{ site.baseurl }}/images/1_HIGH4gfPT38T7JYXuaRIIQ.jpeg)

_Sorry about the clutter. We’d just moved in when this was taken!_

I added things like absolute search volume data and the ability to sort on it, more consistent categorization standards, and automatic classification of trends.

With the data granularity, you can see that the three-month chart data was weekly at first. Pretty crummy with only 12 data points.

![trennd-data-before]({{ site.baseurl }}/images/1_9k4BA819tHQsz1t_EGnMEA.png)

But then below that, with daily data points, you can really see the difference.

![trennd-data-after]({{ site.baseurl }}/images/1_CUEsZa_YkdgO1eQXMsemQw.png)

Anyway, I’ll stop boring you with the various small additions and improvements I made over this time. Back to the story. 😛

## Traction despite inaction

I’d done zero marketing for more than a month. 🤦‍♂️

The hype last month around the Hacker News launch and in the Twittersphere naturally died down, along with the web traffic.
It’s way too easy to put marketing on the back burner and keep building in general. That’s where I’m personally most comfortable.

But I know too well that marketing should be an ongoing crusade alongside product improvement.

The most successful indie hackers I see around have systemized routines that enable them to continually output valuable content.

But to my surprise, the mailing list count was still ticking up every day despite all this, and the site seemed to reach a healthy equilibrium of 100 to 300 daily visitors.

![trennd-subs]({{ site.baseurl }}/images/1_Ep_WNGikyvpani8y68rxyQ.png)

These were both big green flags to me. (I’m not sure if green flags are actually a real thing. Emojipedia doesn’t think so… 🚩)

Pieter Levels tweeted about us again out of the blue! This was several months after the first time and drove several thousands of visitors to the site.

![trennd-levelsio]({{ site.baseurl }}/images/1_8yXgNFYA79QIApf13ufzbQ.png)

## Acquisition

All kinds of people had been putting themselves forward, asking to get involved. And this was happening on a semiregular basis!

The problem is that co-founders bring a huge amount of risk with them—differences in vision, work ethic, and so many other things.

They’re big unknowns, so I’d decided to stick by myself and the devil I know.

That is, until I received the following email from:

![trennd-brian-email]({{ site.baseurl }}/images/1_iOWjxsY6hRdOFMNtJ_2ypA.png)

I thought I recognized that name. Googling Brian Dean… Oh, snap!

Yep, it’s Brian Dean of Backlinko.com 😮

![backlinko]({{ site.baseurl }}/images/1_DBiTYdk-O0U17jFBz9npWg.png)

More Googling. Interesting—he’s acquired things before. I don’t think he’s joking around.

![backlinko--glenalsopp]({{ site.baseurl }}/images/1_DilpGXymthtAZH1gmKs-Ew.png)

My wedding was just days prior, and we were off to Okinawa for four days, so my call with Brian had to wait. Best to play hard-to-get anyway. 😜

![trennd-skype]({{ site.baseurl }}/images/1_5GZDZ4o2bb-6MmaC8IxFDQ.png)

Then, one call and one hour, 21 minutes, and 31 seconds later — we had a deal.

And we virtually shook hands over Skype video! 🤝

As for the acquisition number, that’s why you’ve read this far, right?!

It’s really difficult to put a price on something that’s not making any money yet. Well, actually it’s not. Most people would just say $0. And traffic was growing but spiky and low in an absolute sense.

But at the same time, we were massively excited by the potential, and the concept was partially validated and derisked given the initial traction obtained.

We settled on an amount equivalent to how much I’d earn as a U.S.-based engineer working six months and then multiplied by X for the traction/success factor already achieved. And I still have a stake in the project going forward.

So I can’t retire yet, but it’s a huge win!

The main thing is that now I don’t have to worry quite so much about paying rent every month, and I can start to think more big picture in general.

And perhaps even more important, it provides validation to myself (and my wife!) that I can keep working on these “projects” of mine and not get a “real job” just yet.

To be honest, I didn’t know if I was just crazy and wasting my time for six months.

To my Japanese in-laws, I was the slightly strange, unemployed “freeter” at home on my computer all day.

![trennd-freeter]({{ site.baseurl }}/images/1_qh1-MnCHLHswxIdx7WCdZg.png)

I have to say, writing during the process made a huge difference. It keeps you sane as a solo founder and allows you to track your own progress at a high level.

Also, being as open as possible and sharing metrics such as subscriber growth, traffic, and revenue helped attract support and keep me accountable when it was only me working on it.

And overall, this all helped create a story around the product, without which people don’t have reason to care.

## What’s next

It’s awesome to have Brian behind the project now. This is fantastic news for Exploding Topics. He’s a massive name in the SEO industry, of course, but he’s also a super-smart guy who really knows his stuff and enables us to take the project to the next level.

He has a great instinct for direction, based on years of experience and success online. This includes his “headache detector,” as he calls it, which can foresee potential problems way further in advance than I can.

We’ve also fast-forwarded to putting new features in front of Brian’s huge audience to see what they think.

I no longer need to grow Trennd’s audience via a trend community/discussion platform slowly over months and years while also trying to wrestle with product-market fit.

Instead, we can focus on building a better product. This means the core value of trend discovery and getting people hotter trends faster.

To this end, we’ve been able to refocus on the backend. Now we monitor way more places on the internet as sources for interesting new topics and keywords across health, business, marketing, fashion, and more.

We’ve also decided to niche down. This is a vital step and something I’d been sweating and delaying for several months. But with Brian’s help, this is something we’ve been able to move forward on.

The problem is there are so many different potential customers: indie makers like me looking for their next project idea, investors looking for a company stock pick, affiliates seeking the next hot product, or people just seeking to feed their curiosity.

We’ve settled on professional bloggers.

These writers are our new focus, because they constantly need fresh content ideas across a range of categories to write about. And if they’re one of the first to write about an exploding topic, that makes a huge difference to their results.

They also potentially make for good customers. (Even though we don’t have our premium version yet!) It’s still good to choose a nice market where people immediately “get” the product and are willing to pay for it if it provides value.

This market has proven itself before too, as Nathan Barry of ConvertKit said about going from $1,000 to $10,000 MRR:

> Niche down as small as possible. Going from a generic email marketing company to “email marketing for professional bloggers” was critical. ([Source](https://www.indiehackers.com/forum/ama-im-nathan-barry-the-founder-of-convertkit-968-000-mo-be0b361a63))

We’ve renamed it, too. I know, I know. I’ve already rebranded from Trend List to Trennd, and now we’re doing it again? But hear me out.

This product spreads by word of mouth very well.

But try telling your friend, “Check out Trend, but with two Ns. Oh, and it’s .co, not .com.” Not good. 😅

So we’ve gone with [ExplodingTopics.com](https://explodingtopics.com/).

Lovely. Easy to remember. Easy to spell. Has a balanced look on paper, too, but maybe that’s just me.

And the word “topics” aligns better with our new target audience.

Plus, we now have a sweet new design. I feel it’s much more intuitive and way sexier in general. 🤩

![trennd-exploding-topics]({{ site.baseurl }}/images/1_iqJ9QDAebnTgU6A8Gome-A.png)

Before, it looked like a project. _Now, it looks like a product._

But otherwise, that’s it! Glad you made it to the end. Hope you enjoyed the story.

Until next time, 😘
Josh
