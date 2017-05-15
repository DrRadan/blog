---
layout: post
title: "A Quick Look at the Reply-to-Retweet Ratio"
date: 2017-05-15 16:00
published: false
preview_image: http://www.fastforwardlabs.com/cinephile_tsne/images/Cover.png
feature: false
post_type: Demo
author: Sepand
author_link: https://twitter.com/s3pans
interview_with: Mike
interview_with_link: https://twitter.com/mikepqr
---

Twitter users can retweet, like or reply to a tweet. If a tweet from a
prominent account gets more replies than retweets then [that's usually Not
Good](http://www.esquire.com/news-politics/news/a54440/twitter-ratio-reply/).

Take, for example, this recent tweet from United Airlines. It got three
times more replies than retweets. Those replies are not filled with praise, and
that ratio was a sign to United's PR team that they were in trouble, in case it
wasn't already obvious.

![United Airlines tweet](/images/2017/05/united_airlines_tweet.png)

##### [Tweet from United Airlines](https://twitter.com/united/status/851471781827420160)

Which politician sends the worst tweets according to this reply-to-retweet
ratio measure? And without wishing to add to Donald Trump's problems, are
things getting worse for him?

We scraped<sup><a name="footnote1ref" href="#footnote1">1</a></sup> this information from the accounts
belonging to Donald Trump, Hillary Clinton, Bernie Sanders, Paul Ryan, and
weird Twitter favorites Mike Huckabee and dril. Explore the visualization
below.

<iframe class="ffl-demo" src="http://www.fastforwardlabs.com/tweetratio/" height="400px"></iframe>

Things are getting worse for Donald Trump since his inauguration, but it's
clear that Paul Ryan is by far the worst tweeter in this group. Here's the
worst of his tweets, which received 27 times more replies than retweets.

<blockquote class="twitter-tweet" data-lang="en"><p lang="en"
dir="ltr">VERIFIED: MacArthur Amendment strengthens AHCA, protects people with
pre-existing conditions. <a
href="https://t.co/6W7bDEO40r">https://t.co/6W7bDEO40r</a></p>&mdash; Paul Ryan
(@SpeakerRyan) <a
href="https://twitter.com/SpeakerRyan/status/859442620187193345">May 2,
2017</a></blockquote> <script async src="//platform.twitter.com/widgets.js"
charset="utf-8"></script>

<a name="footnote1" href="#footnote1ref">1</a>. Note we wrote ugly scraping code to
collect this information because the official Twitter API does not return reply
count. You can see the code (and use it to download information for another
account) on [GitHub](https://github.com/fastforwardlabs/tweetratio). Our visualization only shows tweets since
January 2016 that received more than 50 retweets.