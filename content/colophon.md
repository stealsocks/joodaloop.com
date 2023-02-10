---
title: "Colophon"
date: 2019-02-14T15:36:09-06:00
toc: true
description: "About this site."
---

_Snowfall animation adapted from a demo by [Alvaro Montoro](https://community.codenewbie.org/alvaro_montoro/creating-a-snowfall-effect-with-html-and-css-2p4), now available (and customizable) at [snowfall.css](https://snowfall.joodaloop.com)._

Principles
----------

I find it easy to make design choices when I've already chosen a set of constraints/rules to adhere to. For this version of my site, I chose the following principles:

### I. Speed

The internet has gotten faster, but average page load times have [stayed the same](https://www.nngroup.com/articles/the-need-for-speed/). This kinda sucks, and this site tries to lower that average.

<div class=quote> “What was the average device in 2016? It sure wasn't a $2,000 M1 MacBook Pro, that's for sure.” <br> “No, it was a $600-$700 device. Think (best-case) 2-core, 4-thread married to slow, spinning rust.” <a href="https://infrequently.org/2022/12/performance-baseline-2023/#the-performance-inequality-gap-is-growing">Alex Russell</a> </div>

It tries to achieve an seamless SPA-like user experience while being a collection of regular HTML pages. You can see more about how I achieved this in the [Features](#features) section.
<table>
  
 <thead>
 		<tr>

<th scope="col"> Test </th>
<th scope="col"> Result </th>
     
</tr>

  </thead>

  <tbody>
	    <tr>
		      <td> <a href="https://yellowlab.tools/result/ghzoms6oxw"> Yellow Lab Test </a></td>
		      <td>100/100 </td>
	    </tr>
	    <tr>
		      <td><a href="https://pagespeed.web.dev/report?url=https%3A%2F%2Fjoodaloop.com%2F&form_factor=desktop">PageSpeed Insights</a></td>
		      <td> 100/100</td>
    	</tr>
    	<tr>
		      <td><a href="https://www.debugbear.com/test/website-speed/56BFQUcy/overview">DebugBear</a></td>
		      <td> Lab score: 100%</td>
    	</tr>
    	<tr>
		      <td><a href="https://speedvitals.com/report/joodaloop.com/2OYA4U/">SpeedVitals</a></td>
		      <td> Grade: A (100%) </td>
    	</tr>
    	<tr>
		      <td><a href="https://gtmetrix.com/reports/joodaloop.com/GO6PsdMd/">GTMetrix</a></td>
		      <td> Grade: A </td>
    	</tr>
    	<tr>
		      <td><a href="https://www.512kb.club/"> 512kb Club </a></td>
		      <td> Approved member </td>
    	</tr>
    	<tr>
		      <td><a href="https://250kb.club/page/3/">250kb Club</a></td>
		      <td> Approved member</td>
    	</tr>
  </tbody>

</table>

Pages weigh an average of 15kb after the fonts have been cached. Thus, the majority of it's load time is taken up by latency, not bandwidth. That, in turn, is minimised using Netlify's global CDN and prefetching + caching.


### II. Thoughtfulness

How can I make navigation as seamless as possible? How can I maintain a high level of information density with a minimal (yet beautiful) layout? These are the questions that guided most of design for this version of the site.

There are also annoying bugs and imperfections that will pop up across platforms and viewports, caring for quality means choosing to care about them. If you see one, please [let me know](https://twitter.com/joodaloop).

<div class=quote> “The joy of web design & typography is that just its presentation can matter a little to all your pages.” <a href="https://gwern.net/design#benefit">Gwern</a> </div>

It might seem wasteful to put so much effort into tiny details like "should the transition delay on this hover efect be 0.4s or 0.45s?", but I consider it to be reasonable investment.




### III. Simplicity

Simplicity does not imply minimalism. Nor does it necessarily involve strict rules like "No Javascript or animations!"

The real goal is to have the site be as easy as possible to maintain, modify, and add to. To pick a simple set of guiding rules, and stick by them whenever possible. Let constraints guide creativity, etc, etc.

In my case, this involved picking a simple folder heirarchy, basic color palette, one stylesheet, and zero external dependencies or [JS frameworks](https://infrequently.org/2023/02/the-market-for-lemons/).



## Content

I hate doing things that I know I won't care about in a year (or more) from now. So the idea of a [long site](https://gwern.net/About#long-site) was an obviously appealing one. 

<!-- [This post](https://www.cyberpatterns.xyz/p/twittercapital) is the closest you can get to defining the _opposite_ of what I want to do. -->


<table>
  
 <thead>
 		<tr>

<th scope="col"> Page/Section </th>
<th scope="col">Purpose</th>
     
</tr>

  </thead>

  <tbody>
	    <tr>
		      <td> <a href="#"> Useful </a></td>
		      <td>There are certain topics that I've been asked to talk or write about before for. Posts listed on this page were written mainly for utilitarian purposes (how to do X). </td>
	    </tr>
	    <tr>
		      <td><a href="#"> Lists & Highlights </a></td>
		      <td>Primarily curation.</td>
    	</tr>
    	<tr>
		      <td><a href="#"> Notes </a></td>
		      <td>Messy, unstructured writing-in-progress.</td>
    	</tr>
	    <tr>
		      <td><a href="/bad-advice"> Bad Advice </a></td>
		      <td>Things that I have done that worked out well, but would usually be considered terrible advice.</td>
    	</tr>
    	<tr>
		      <td><a href="/essays"> Essays </a></td>
		      <td>A list of my best essays.</td>
    	</tr>
    	<tr>
		      <td><a href="/personal"> Personal </a></td>
		      <td>About me.</td>
    	</tr>
    	<tr>
		      <td><a href="/colophon"> Colophon </a></td>
		      <td>The page you're on right now.</td>
    	</tr>
  </tbody>

</table>

Target Audience
---------------

People with too much time on their hands.

Or anyone who cares about the web, economics, math, people, ideas, terrible advice, [magic ink](/lists/things-i-think-about-often#information-architecture), or [me](/personal).

<!-- Etymology
---------

The site name is . There is a pleasing visual symmetry to it.
 -->

## Inspiration {#inspiration}

These are some of the people from whom I've stolen ideas for specific design elements, data representation, page types, content and philosophies of site-building.


<table>
  
<thead>
<tr>

   <th scope="col">Site</th>
   <th scope="col">Influence</th>
     
</tr>

  </thead>

  <tbody>
	    <tr>
		      <td> <a href="https://arcana.computer"> arcana.computer </a> </td>
		      <td> Simplicity + personality. </td>
	    </tr>
	    <tr>
		      <td> <a href="https://manuelmoreale.com/"> Manu </a> </td>
		      <td> Beautiful minimal layout + elegant serif. </td>
	    </tr>
	    <tr>
		      <td><a href="https://aaronzlewis.com/"> Aaron Z. Lewis </a> </td>
		      <td> The best personal website on the internet, if you ask me. The sheer variety of pages (<a href="https://aaronzlewis.com/starterpack/">starter pack</a>, <a href="https://aaronzlewis.com/cocoon/">cocoon</a>) was most inspiring.</td>
    </tr>
    <tr>
		      <td><a href="https://www.zachleat.com"> Zach Leatherman </a> </td>
		      <td> <a href="https://www.zachleat.com/web/style-guide/">style guide</a> </td>
    </tr>
  </tbody>

</table>



## Stack


This site is generated using [Hugo](https:/gohugo.io), chosen for it's [speed](https://www.zachleat.com/web/build-benchmark/) and feature set. The layout uses a custom theme (that I intend to make open-source in the future) and uses no external libraries or frameworks.

This setup costs me exactly $0 a month for hosting, and $10 a year for the domain.

| Service | Purpose |
|-|-|
| [Github](https://github.com) & [Git](https://git-scm.com/) | Hosting and version control. |
| [Netlify](https://netlify.com) | Deployment, SSL certificates, CDN and caching. |
| [Google Domains](https://domains.google.com/) | Domain provider with the most transparent pricing. |


Features
--------

The design choices and constraints were largely decided by the principles set out above, and manifested themselves in certain specific ways:

- **Table of contents:** To aid navigation, a list of page headers is auto-generated by Hugo's `.TableOfContents` [variable](https://codingreflections.com/blog/hugo-table-of-contents) and added to the center column. It is available on horizontal iPad and desktop screens, but is hidden on mobile.

- **SPA-like navigation:** I just use a small script to store the leftmost menu's scroll-position to LocalStorage and retrieve it on page refresh. Page loads also use an animated fade-in effect to make naviagation feel smooth. 

    Navigation is sped up by using [instant.page](https://instant.page), which prefetches pages whenever you hover over a link. I use an inlined, minified [version](https://instant.page/5.1.1) of the script so as to avoid loading an external file. 

    (Check out [Brian's site](https://brianlovin.com/writing/how-my-website-works) for a better example of this personal-website-as-SPA idea, but that's an *actual* Next.js SPA, and requires so much [effort](https://adamwathan.me/2019/10/17/persistent-layout-patterns-in-nextjs/)).


- **Information hiding**: Hovering over page numbers will reveal the description for that page. Allows me to maintain higher information density alongside the clean book-like look.

## Media


Images are compressed using [Squoosh](https://squoosh.app) and uploaded directly to the site repository. Netlify's CDN is responsible for delivering and caching them alongside each page.



## Fonts

The main font used across this site is [Petrona](https://fonts.google.com/specimen/Petrona), designed by [Ringo R. Seeber](https://github.com/RingoSeeber/Petrona). It's one of the few fonts that has the full range of possible font-weights, for both italic and normal styles.

They were [converted](https://henry.codes/writing/how-to-convert-variable-ttf-font-files-to-woff2/) from `.ttf` to `.woff2` files using Google's [woff2 library](https://github.com/google/woff2). This takes the file size from 217kb to ~90kb. 

I then used [pyftsubset](https://clagnut.com/blog/2418) to reduce the number of glyphs to just the [Basic Latin](https://jrgraphix.net/r/Unicode/0020-007F) (0020-007F) and the first half of [General Punctuation](https://jrgraphix.net/r/Unicode/2000-2038) (2000-2038) subsets, which brings them down to ~45kb.

Font files are served and [cached locally](https://stackoverflow.com/questions/52308658/netlify-headers-cache-control-for-static-assets) by Netlify. 


## Analytics

Site analytics provided by [Umami](https://umami.is/), a really cool self-hosted, open source, GDPR-compliant analytics project. This means no cookies, tracking or personal data collection.

I host my version using the generous free tiers on Netlify (server) and Supabase (database).