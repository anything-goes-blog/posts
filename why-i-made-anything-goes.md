---
title: Why I made Anything Goes
author: LewisTehMinerz
---

Anything Goes is this site you are viewing right now, a glorified markdown parser built to make a nice-ish looking blog site. It requires
JavaScript to do anything (yes I know, boo hoo) and it doesn't even use React. But.. why?

## For Fun
I was bored and just decided to write Anything Goes for fun. I brought it up in the Discord Bots community server as a joke originally but
now that I have actually written it, I guess it's kind of useful? Probably not though, who would want to write posts on this?

## As a Project
I guess I could see this as a project. You write posts on GitHub and they get displayed on a website. It's a simple concept and pretty
simple to code, and I needed to touch up on my frontend skills anyway.

## As a Social Experiment
I was also curious about what people would write on the blog. Since it's anything (as long as you stick within the rules listed in the
README), anything can be posted, so there would be a lot of interesting reads.

## Future goals?
Based on the popularity of this project, I might expand it into a bigger platform, eventually moving the actual site off of GitHub whilst
leaving the posts on it, and actually doing it properly with server side rendering with a proper domain, as a free blog post site, much
like [Medium](https://medium.com). I was actually planning to add comments via [utterances](https://utteranc.es) but annoyingly it does not
have a JavaScript API so if I was to switch posts it would not unload and reload the new comments. I am planning to actually use it, but
for this, god no. Not whilst it's a SPA. It's impossible to do with utterances right now. If I do SSR, utterances would work fine, as the
page would be rendered serverside unlike how it is where it's rendered on the client, so you would have to reload the page anyway. I could
make it SPA + SSR as well, but I'm not sure how utterances would like that. Anyway, a bit of off topic stuff there. I am currently the only
"staff" member on this "platform", and I haven't automated post review and acceptance, so your posts will take a while to be accepted.
Automation will come at a later point but not right now. Posts don't have time tracking on them either. If I was to do this as a proper
platform and not a single HTML file hosted on GitHub, it would be time tracked (based on the commit time rather than when the server first
retrieved the post). It would also be much prettier with an actual blog design rather than this header and content system I have right
now, also having a latest posts (which I am trying to implement but that is a lot of API requests I have to make to GitHub right now...).

## Moving off of GitHub?
Anything Goes might just become completely independent of GitHub all together. It might have its own post submission feature for review by
humans, it would be much more advanced, having things like pure HTML, Markdown, RST, etc. and be less awful in general. If you ever stumble
across this post in the future, and you're wondering what I was on about with GitHub, Anything Goes started out as a GitHub organization
and two repositories; one repository containing the website, one repository containing the posts and comments. If you're reading this on
a brand new website, I probably have treated you right. It is most likely much better than the original Anything Goes site, so... be glad
I redid it.

Anyway, that is all for now. Goodbye.
