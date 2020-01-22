---
layout: post
title: How I Coded A Website Plugin Making $600 Per Month
---


![How-I-Coded-A-Website-Plugin-Making-$600-Per-Month-Hero]({{ site.baseurl }}/images/open-uri20190313-4-1m8svpb.png)

<div>
  <a style="display: flex; align-items: center;" target="_blank" href="https://www.starterstory.com/stories/how-i-coded-a-website-plugin-making-600-per-month">
    <h2 style="margin: auto 0px">Featured in:</h2>
    <img src="{{ site.baseurl }}/images/starter-story-logo.png" alt="trennd-marker" width="150px" />
   </a>
</div>

### Hello! Who are you and what business did you start?

Hi! I’m Josh and I created [Wheely Sales](https://wheelysales.com/), a lucky wheel popup that works on any e-commerce platform. It’s basically like the Wheel of Fortune from the [classic TV game show](https://en.wikipedia.org/wiki/Wheel_of_Fortune_(American_game_show)) - but fully customizable for your online store!

For a chance to win a prize or discount, visitors enter their email address and spin the wheel. Since it’s something fun and different for users, it has much higher opt-in rates (~12%) than regular exit popups. I also conform to the “eat your own dog food” premise and use Wheely Sales on its own landing page! :)

I’ve grown revenue from $0 to $600/month in just 4 months since getting started and over 1.1 million people have seen the wheel on my customers’ websites in that time.

### What's your backstory and how did you come up with the idea?

I have a background as a freelance software developer which has allowed me to bring various new app ideas to life in the past few years (in the time between other app development gigs).

> I learned the hard way that if nobody has built anything similar yet, it’s probably a big red flag. Competition is validation.

But before Wheely Sales, all of my own personal app projects either had zero product/market fit, or worse - I had no actual clue how to monetize them. I built them simply because I thought they were a cool product that nobody had done before. Or I thought they had a chance to become huge. “Monetization will come later”, was my go-to thought.

My best example of this was Etherest which was an API that lets you interact with the Ethereum blockchain. It reached the first page on Hacker News for 24 hours and then interest generally fizzled out.

I learned the hard way that if nobody has built anything similar yet, it’s probably a big red flag. Competition is validation. And you need to know how your product will make money in month 1. So my new plan was to find existing successful products that have proven the market, but that might not serve all the market. Which is where I could step in.

I did my research and noticed the lucky wheel popup format had started appearing and worked really well at converting traffic. Both Spin-a-sale and Wheelio on the Shopify app store had hundreds of great reviews. Even on StarterStory, Eddie at Flyby mentioned how Spin-a-Sale “was the driving force in our email growth” and was converting at 12%!

But they were only available as a Shopify app. Other huge platforms like WooCommerce, BigCommerce and Squarespace were not provided for. For me, this was enough validation to just go for it! So I built Wheely Sales to be compatible with ANY website/platform and fill this gap in the market.

![]({{ site.baseurl }}/images/open-uri20190313-4-1rl40mk.png)

### Take us through the process of building the product.

It took just over 1 month working full-time to code up the initial version of Wheely Sales. This was time I had between finishing a previous software contract and looking for my next freelance gig.

The app was originally lacking some functionality that might have been considered essential. For example, users had to customize their wheel prizes, text and branding but they couldn’t preview or test the wheel before putting it live on their e-commerce store in front of customers! But I just had to get something out the door and in front of potential customers to see if it sticks. This was my big concern.

> You don’t have to make the next new shiny billion dollar app. You could instead take a product that’s already working and serve it to a new market in a different way.

As a developer used to locking myself in a room and building things, I didn’t know how to reach, market and sell to people. If I could figure out how to do this.. well then I could justify working on the app’s code and feature list some more.

The wheel pop up itself consists of plain old javascript files and assets. The most complicated part of this was the spin physics, but I actually found code to do this for $15 on [ThemeForest](https://themeforest.net/) which saved a lot of time.

Then, I overhauled all of this code so that it’s fully customizable to any customer’s brand colors, logos, and text. The most time-consuming part was ensuring that it all adapted to mobile screens, worked across different platforms (Wordpress/BigCommerce/Shopify/anything else) and across all the different browsers (Chrome/Safari/Firefox/etc). This was quite a headache to achieve!

Finally, I turned all this into a super simple 1-line script that anyone can paste into their site and install in two minutes just like Google Analytics.

The Wheely Sales backend runs on Express.js and uses MongoDB. And there’s also a user dashboard for wheel customization, leads collection and data analytics (which uses MeteorJS and React).

![]({{ site.baseurl }}/images/open-uri20190313-4-b2n2rm.png)

### Describe the process of launching the business.

There wasn’t really a big launch for Wheely Sales. I did consider how I could launch it - my ego wanted to for sure! But I didn’t see how it would really help. The usual places people launch are Hacker News and Product Hunt as far as I’m aware.

But these audiences don’t exactly align with my target audience for Wheely Sales which is ecommerce store owners. I suppose I could have launched with an ad campaign, but I didn’t have the funds for this!

I’m also a little biased from my experience launching my app Etherest - it attracted a few thousand site visitors from a “Show HN” post on Hacker News that reached the front page for 24 hours. But the long-term impact of a traffic spike like this can sometimes be pretty underwhelming and frankly demoralizing.

For Wheely Sales I did however set up a slick looking landing page using Webflow, with a video demo of the product above the fold as soon as you open the page. I knew that I had to have visitors at least see the product in action if nothing else before they left the page.

I increasingly find with other product/service websites that you sometimes can’t immediately figure out what they’re actually selling - and I’ll be damned if I fall into that pattern!

Wheely Sales has subscription pricing with a 10-day free trial. The free trial is very effective since users get to see real results within days and can then justify the cost with the huge numbers of email subscribers they convert. I decided to price by the number of wheel views since this scales well with both the cost of serving the popup to more web visitors and also the value attained by the customer with more views/subscribers. There are three pricing tiers:

- Small Business plan: $29/month for up 25,000 wheel views
- Medium Business plan: $99/month for up 100,000 wheel views
- Big Business plan: $299/month for unlimited wheel views

My first paying customer was an absolute breeze - I woke up one morning with a payment confirmation email and that was it. It’s a really strange transition to selling a product rather than time. Where someone you’ve never met, spoken to or even messaged pays you (from Italy in this case) and you didn’t actively do anything for them specifically. Occasionally things go wrong though and my second customer wasn’t so smoothly acquired! After helping to onboard and install them on BigCommerce at midnight due to time differences, I had to quickly debug and fix the wheel in Firefox which looked like this...

![]({{ site.baseurl }}/images/open-uri20190313-4-15cornt.png)

I use Intercom which is great because it gives you a live chat interface to onboard potential customers. But at the same time, this real-time nature (especially the ‘seen’ notification!) really turns up the heat in times like these.

### Since launch, what has worked to attract and retain customers?

My target customer is any e-commerce store owner actively looking to improve their email opt-in rate and grow their email list. And since Wheely Sales runs on any ecommerce platform and most people want more email subscribers, this is basically everyone!

I attracted initial customers using email outreach and forum/Facebook group participation. I would specifically find websites using adjacent plugins that also help conversions/opt-ins and then reach out. This works because these are people who are proactively trying to improve their website conversions and are also willing to pay for a solution.

To breakdown the process, for example I found social proof apps like ProveSource or opt-in bars like HelloBar. Then you can use sites like [NerdyData](https://nerdydata.com/) to find which websites run these plugins, and then visit each website to assess the prospect’s potential. If good, then you use [Hunter.io](https://hunter.io/) to get their email address and reach out to them explaining how you can help them specifically. With cold emails like this, the trick is quality over quantity, concisely explaining your value and making it about their business not your product.

Facebook groups have also been a source of some leads, but you have to regularly participate in a non-promotional way and provide value, or you will get banned for marketing almost immediately. Specifically, I find interesting articles that my potential customers would find valuable. I then post a summary of these to ecommerce groups and reply to any comments or messages. I’m not directly posting a link to Wheely Sales in the group, but I get 5-10 people every week who message me directly in response. I’ve been able to start a conversation with them and sometimes I can recommend Wheely Sales as a way to grow their ecommerce.

A big part of attaining and retaining users has been providing great customer support. I try to respond ASAP to any messages that come through Intercom. This is especially important since the app needs to be installed on customers’ online stores to get started. I’ve found that the customers I interact with the most via Intercom generally go on to be the most satisfied and loyal customers!

### How are you doing today and what does the future look like?

As a bootstrapped app most of the $600/mo business revenue is profit and it’s growing slowly month on month.

But it’s been critical to carefully manage and monitor costs since Wheely Sales is bootstrapped and served to hundreds of thousands of web visitors per week. For example, I was using Amazon S3 initially to serve static assets, but after a big website with 3 million views per month installed Wheely Sales I quickly noticed $50/day AWS costs. I promptly moved to serving these assets behind Cloudflare’s CDN! Despite this, I still think it’s better to get something out there initially and worry about scaling issues when you actually get to scale as happened here.

The two priorities going forwards are expanding the product’s feature set and also exploring new customer acquisition channels. I’ve recently added Mailchimp and Zapier integrations, and I’m currently listening to customer feedback to prioritize what’s next. The real challenge is figuring out how to reach the next order of magnitude in terms of customer acquisition, so in the next few months I’m going to start some small experiments with Facebook ads and other paid channels.

### Through starting the business, have you learned anything particularly helpful or advantageous?

I’ve learned so much, but one piece of advice I don’t hear too often elsewhere is to say no to user feature requests that take focus away from the core value proposition. This is even harder when the feature might convert them to a paying customer! But if you try and cater to everyone you actually cater to nobody.

For example, I added a feature that lets you provide a prize URL link instead of a coupon code as a wheel prize. This would allow blogs to use Wheely Sales with their lead magnets such as ebooks and other free downloads. But very few customers actually ended up using this feature and now it potentially distracts and confuses new users. So avoid feature bloat!

Another big one is to always follow up with leads that have gone cold. You may think that you’ve lost them and shouldn’t pester them, but from my experience people just get busy and forget. They actually appreciate the follow-up, it shows you’re serious and they convert more often than you’d expect.

### What platform/tools do you use for your business?

- MeteorJS & ReactJS - the web stack I know and can build things fast with
- Digital Ocean - for file storage (9x cheaper than AWS S3!)
- Google Analytics - of course!
- MailChimp - email onboarding (they have a generous free plan)
- G Suite - Drive and email
- Cloudflare - website speed & caching
- Webflow - landing page (less bloated than Wordpress)
- Intercom - customer communication & onboarding

### What have been the most influential books, podcasts, or other resources?

I can honestly say that both IndieHackers.com and StarterStory.com have been tremendous for providing me real-life examples for inspiration, motivation & learning.

### Advice for other entrepreneurs who want to get started or are just starting out?

You don’t have to make the next new shiny billion dollar app. You could instead take a product that’s already working and serve it to a new market in a different way.

Also, persistence and patience are key. This is something I personally find difficult to remember. You may get stuck at particular revenue levels and customers may fail to convert, but if you keep chipping away then you’ll get there.
