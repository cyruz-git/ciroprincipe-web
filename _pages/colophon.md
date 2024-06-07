---
permalink: /colophon/
layout: page
title: Colophon
---

<div class="alert alert-info" role="alert">
This page is meant to provide information and credits about the tools and technologies used to build this site. Any 
content, code, art and software copyright is held by its respective owner. All site content is publicly accessible on
[GitHub](https://github.com/cyruz-git/ciroprincipe.info){: class="alert-link"}.
</div>

I created this site from the ground with the following tools and minimalism in mind:

{: class="dl-horizontal"}
Static Generator:
: [Jekyll](http://jekyllrb.com/) using [Poole](https://github.com/poole/poole) as a reference.

Markdown Parser:
: [kramdown](http://kramdown.gettalong.org/), with GitHub Flavored Markdown enabled.

Tag Generator:
: <del>[Jekyll Tag Page Generator](https://github.com/danieldevries/jekyll-tag-generator) plugin.</del> After the 
  migration to GitHub I ditched the **Tage Page Generator** plugin for a static tag page. My old implementation is 
  [forked on GitHub](https://github.com/cyruz-git/jekyll-tag-generator).

Style:
: [Bootstrap](http://getbootstrap.com/) for a consistent and minimal framework, with some customizations.

Fonts:
: [Lato](http://www.latofonts.com/lato-free-fonts/) font for the Header, through the 
  [Google Fonts API](https://www.google.com/fonts).

Art:
: [Ionicons](http://ionicons.com/) on the [landing page]({{ "/" | relative_url }}).

Various Guides:
: [PixelCog](http://pixelcog.com)'s 
  [Jekyll From Scratch - Core Architecture](http://pixelcog.com/blog/2013/jekyll-from-scratch-core-architecture/)  
  [PixelCog](http://pixelcog.com)'s
  [Jekyll From Scratch - Extending Jekyll](http://pixelcog.com/blog/2013/jekyll-from-scratch-extending-jekyll/)
  
The site is <del>self hosted on a [Crissic Virtual Private Server](https://crissic.net/) using 
[nginx](http://nginx.org/) as a web server and pushed through [rsync](http://rsync.samba.org/)</del> hosted on 
[GitHub](https://github.com), pushed through <del>[SourceTree](https://www.sourcetreeapp.com/)</del> 
[GitHub Desktop](https://desktop.github.com/) and served by [Cloudflare Pages](https://pages.cloudflare.com/).
