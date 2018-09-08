---
layout: post
title: Heidi's Teriyaki
description: A Simple Restaurant Info Website
img: /img/heidi-front.jpg
---

Having an online presence with readily available business information is integral to a business' success, especially for small family-owned businesses that aren't prepared for such changes that technology is bringing about. Businesses like these either adapt, or eventually are cornered out by the competition, especially in areas that are affected by nearby gentrification.

Heidi's Teriyaki Express is a Vietnamese cuisine restaurant based in Silverdale, WA. It is also *my* personal favorite Asian restaurant to eat in all of Washington State, which is why I offered my expertise in building out a cheap and simple option for the restaurant to establish an online presence. The owner, Alex, is a quick-to-learn individual but he needed some initial help first.

<div class="img_row">
	<img class="col one" src="{{ site.baseurl }}/img/heidi-jekyll.png" alt="" title="Jekyll"/>
	<img class="col one" src="{{ site.baseurl }}/img/heidi-ghp.png" alt="" title="GitHub Pages"/>
	<img class="col one" src="{{ site.baseurl }}/img/heidi-googleg.png" alt="" title="Google G"/>
</div>
<div class="col three caption">
	Jekyll, GitHub Pages, and Google
</div>

This is where I come in---at the time, I was a sophomore in college on track for a Business Administration - Management Information System degree and I was researching affordable ways to build an online brand. Sure, having professional social media, a LinkedIn, university email addresses, etc. was all good standard practice. However, nothing says business like having your own personal website.

<a href="https://www.heidisteriyaki.com">www.heidisteriyaki.com</a> is a simple statically generated website built on <a href="https://jekyllrb.com">Jekyll</a> (Markdown + Liquid + HTML + CSS), <a href="https://pages.github.com">GitHub Pages</a>, <a href="https://domains.google">Google Domains</a>, and <a href="https://www.siteleaf.com">SiteLeaf</a> for a Content Management System. It costs a mere $12 a year, which is just the annual registration fee for the domain name. Webstack technologies are changing all the time and often dependencies are hard to keep track of if the developer is not constantly keeping up to date with mailing lists and security patches.

<div class="img_row">
	<img class="col one" src="{{ site.baseurl }}/img/heidi-siteleaf.png" alt="" title="SiteLeaf"/>
	<img class="col two" src="{{ site.baseurl }}/img/heidi-front.jpg" alt="" title="Heidi's Teriyaki Storefront"/>
</div>
<div class="col three caption">
	Jekyll, GitHub Pages, and Google
</div>

As a result, I went with a static website generator, Jekyll, which is written in Ruby and developed by GitHub's co-founder, Tom Preston-Werner. My reasoning for this is because static websites are fast, secure (no database, nothing worth hacking), and relatively cheap and easy to maintain. Jekyll is actually fully supported by GitHub as well, through GitHub Pages and they recently implemented free SSL certificates by partnering with Let's Encrypt---giving them that nice secured green lock symbol and SEO prioritization from Google. I realized early on that I wouldn't have time to figure out Liquid for the templating so I decided on a simple Jekyll <a href="https://github.com/midzer/urban-theme">theme</a>, developed by <a href="https://github.com/midzer">midzer</a> that would effectively suit the needs for a restaurant website. Jekyll itself takes a bit of time to understand, but once that baseline knowledge is established, the rest comes easy.

The website needed some key information on the restaurant: contact info, hours, address, and a menu. All other items such as an interactive map, Vietnamese character accents, and menu photos were secondary. To get this information, I needed to communicate with the owner that the information that I received was accurate and true as such information can be misleading online due to the nature of user-contributed information. As an owner of a small family-owned restaurant, I knew that Alex would not have the time to type out and push this information onto the website, so I took on the responsibility of doing so myself.

Afterwards, GitHub Pages' role came in. Serving the role of both hosting and generating the static content on GitHub's leased cloud space, and at no cost to the developer. The GitHub platform itself is easy enough to use once the developer gets the basics of git down, at least for the initial development. Once all of the content has been uploaded, a developer may view their website using their personal GitHub URL for the project, until the developer is ready to switch it over to a custom domain.

Google Domains is very simple to use and provides a wide variety of tools to accommodate a developer's web project. A non-squatted .com address can be leased at a low cost of $12 a year and comes with easy-to-use configuration resources to allow a developer to map their resources correctly for DNS and name record configuration purposes. Additionally, Google Domains provides free alias email forwarding (up to 100 aliases) so that the owner's business can be contacted at a custom professional email address such as info@heidisteriyaki.com. At the point of switching the developer's project over to the custom domain, they are allowed to go into their project settings and force https redirection for that custom domain.

The final piece of the puzzle is SiteLeaf, the Content Management System (CMS). As a developer, I would have no trouble utilizing a workstation to do all my website updates. However, this project would have to be handed off to the client, Alex, a non-technical user. SiteLeaf fully supports Jekyll GitHub Page repositories and has a free plan, which made it an obvious choice when selecting a cheap and simple CMS for this project. Teaching Alex to use this system was fairly simple as most of his website updates would pertain to menu item changes and change of business hours (simple Markdown and HTML, both of which are documented very well and readily available). He would never have to even touch any of the more developer heavy resources of the project.

There you have it, a professional online presence at the low-low cost of $12 a year.
