---
title: "This design"
date: 1984-01-02
draft: false
translationKey: "this-design"
weight: 2
summary: "Hugo + PaperMod + GitHub Pages + Cloudflare"
description: "Hugo + PaperMod + GitHub Pages + Cloudflare"
---
---
I needed a simple tool to publish my thoughts—platform-independent, but with a bit of flexibility.

My first idea was to use my primary language, Python, and build something with Django. But that quickly felt like too much work for what I needed. I wanted something even simpler—no servers, no containers, no cloud ops, nothing like that.

Next, I thought about website builders. Out of the various options, I was leaning toward Squarespace, but $25 a month for a site with no traffic seemed a bit much at this stage. I also looked at Tilda—the blog templates didn’t impress me, it’s still paid, and the menu was laggy when I tried it. There are other options out there, but they’re all more or less the same story.

Alright, what about something ready‑made in JavaScript? In theory, that’s possible, but it’s still a different language and I’d wind up slowing myself down. Besides, I don’t need fancy design or dynamic content—the focus should be on substance.

That means I need something even simpler…

I remembered you can host things for free on GitHub Pages. I started digging and found static site generators (SSG): just write in Markdown, the engine does the rest. Jekyll has long been supported by GitHub, but I didn’t like the themes—and why bother if there’s something faster like Hugo with the minimalist PaperMod theme, which fits my goals perfectly.

Okay, time to try things out. And that’s the point—just try, because I didn’t want to waste time on learning curves and fiddling. I wanted the fastest possible way to validate the idea and as little friction as possible. If it works, great; if not, I’ll try something else.

Lets vibe code!

I started tossing tasks into Cursor and asking Perplexity a few questions at the same time. First, I wanted to figure out how to tweak the theme for myself and create an environment I’d actually want to spend time in. After a few hours of trial and error with different models (yes, I like switching things up), the main structure was done: minimal visuals, just the essentials. Then I tossed in a few example thoughts—just to get a sense of where this could go.

Of course, I wouldn’t want to stick with a default domain from GitHub or anyone else—Netlify or Vercel, same deal.

I probably spent a couple hours weighing the pros and cons of different domain names—after all, it’s a strategic decision you rarely change. In the end, I settled on the current option (actually two, with redirection). But then came the question: where to register?

Seems simple, but it’s not—given the current geopolitics. What are the risks? Can I pay? Can I transfer if needed? What’s the risk of them blocking my account? Is the registrar popular enough that I won’t run into UX weirdness? I considered GoDaddy, EuroDNS, and Cloudflare—chose Cloudflare because I trust it more, though of course there are always nuances.

Locally, the MVP was done. No reason to wait—that’s kind of the point: spend as little time as possible and ship small, regular changes. I created a new repo for GitHub Pages, set up DNS in Cloudflare, pushed the code, and GitHub kicked off the build. Aside from a minor DNS validation hiccup, everything was up and running weirdly fast. New updates reach users in about 30 seconds.

The result: a free site, minimalist design, incredibly easy to maintain, and most importantly—the site solves my problem of sharing thoughts with the least time and effort possible.
