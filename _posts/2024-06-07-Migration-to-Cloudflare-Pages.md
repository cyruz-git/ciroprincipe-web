---
layout: post
title: Migration to Cloudflare Pages
tags: site github news bootstrap sass cloudflare
---

Almost 9 years passed since my last blog update. Honestly I wouldn't care about updating it anymore, but recently I 
found myself playing with [Cloudflare](https://www.cloudflare.com) a lot and I thought to consolidate everything 
there (domain, DNS records and website) migrating my site to [Cloudflare Pages](https://pages.cloudflare.com).

I migrated from [GitHub](https://github.com), updating [Bootstrap](https://getbootstrap.com/) to the last v3 available 
(catching up with their recent stuff would have been too much). I received a hell of a warnings so first thing I 
disabled **SASS** (why did I enable it in first place?). Then [Jekyll](https://jekyllrb.com/) complained about other 
stuff as well, like some gems not being updated or whatever, so I tried to sort out everything on local before the 
deploy.

Luckily Cloudflare has some migration guides available 
([1](https://developers.cloudflare.com/pages/migrations/migrating-jekyll-from-github-pages/) and 
[2](https://developers.cloudflare.com/pages/framework-guides/deploy-a-jekyll-site/)) so I got some assistance in the 
process.

My interest in the website is fading, so I didn't plan to dedicate more than 1 hour to this migration, specially after 
reading that it should have been painless. Maybe it is, if your versions are current, but that was not my case.

Lesson learned I have to say. See ya in **X** years.
