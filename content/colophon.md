---
title: "Colophon"
date: 2019-02-14T15:36:09-06:00
toc: true
description: "About this site."
---

_Snowfall animation adapted from a demo by [Alvaro Montoro](https://community.codenewbie.org/alvaro_montoro/creating-a-snowfall-effect-with-html-and-css-2p4), now available (and customizable) at [snowfall.css](https://snowfall.joodaloop.com)._

Principles
----------

Design choices and the overall philosophy of the site are guided by the following principles.

### Speed

The internet has gotten faster, but average page load times have [stayed the same](https://www.nngroup.com/articles/the-need-for-speed/). This kinda sucks, and this site tries to lower that average.


<table>
  
 <thead>
 		<tr>

<th scope="col"> Test </th>
<th scope="col"> Result </th>
     
</tr>

  </thead>

  <tbody>
	    <tr>
		      <td> <a href="https://yellowlab.tools/result/ghj1rut4fo"> Yellow Lab Test </a></td>
		      <td>98/100 </td>
	    </tr>
	    <tr>
		      <td><a href="https://pagespeed.web.dev/report?url=https://joodaloop.com/">PageSpeed </a></td>
		      <td> 100/100</td>
    	</tr>
    	<tr>
		      <td><a href="https://www.512kb.club/"> 512kb Club </a></td>
		      <td> Approved member </td>
    	</tr>
  </tbody>

</table>


<!-- It scores a perfect _100_ on [PageSpeed](https://pagespeed.web.dev/report?url=https://joodaloop.com/), and _99/100_ on the [Yellow Lab](https://yellowlab.tools/result/ghj1rut4fo) test. It is also a member of the [512kb club](https://www.512kb.club/), weighing in at 99kb. -->

Thus, the majority of it's load time is taken up by latency, not bandwidth. That, in turn, is minimised using Netlify's global CDN and prefetching/caching.

### Fun

The site has no obligation to make sense, I can add whatever I like in the manner that I feel is most amusing. Dark mode switches will hide in pictures and headers, snowflakes will float across the screen. You can't stop me, it's my site.

### Quality

There are annoying bugs that must be dealt with, quality is choosing to care about them.

"But the joy of web design & typography is that just its presentation can matter a little to all your pages." Gwern

### Simplicity

Simplicity does not imply minimalism. Nor does it necessarily involve strict rules like "No Javascript or animations!"

The real goal is to have the site be as easy as possible to maintain, modify, and add to. This involved picking a simple folder heirarchy, basic color palette, two stylesheets, and zero external dependencies.

### Consistency

Pick a simple set of guiding rules, and stick by them whenever possible. In this case, I chose a particular design pallete, and try to maintain it across the site. It isn't easy to resist the desire to have a site as cool as [aaronzlewis.com](https://aaronzlewis.com/), y'know.

Each page attempts to maintain consistent formatting (center column with menus on one or both sides), design patterns (b&w boxes and tables, similar border-radius) and structure (title and sub-titles).

Content
-------

I hate doing things that I know I won't care about in a year (or more) from now. So the idea of a [long site](https://gwern.net/About#long-site) was an obviously appealing one. [This post](https://www.cyberpatterns.xyz/p/twittercapital) is the closest you can get to defining the _opposite_ of what I want to do.


<table>
  
 <thead>
 		<tr>

<th scope="col"> Page </th>
<th scope="col">Purpose</th>
     
</tr>

  </thead>

  <tbody>
	    <tr>
		      <td> <a href="useful.html"> Useful </a></td>
		      <td>There are certain topics that I've been asked to talk or write about before for. Posts listed on this page were written mainly for utilitarian purposes (how to do X). </td>
	    </tr>
	    <tr>
		      <td><a href="bad-advice.html"> Bad Advice </a></td>
		      <td>Things that I have done that worked out well, but would usually be considered terrible advice.</td>
    	</tr>
    	<tr>
		      <td><a href="lists.html"> Lists & Highlights </a></td>
		      <td>Primarily curation.</td>
    	</tr>
    	<tr>
		      <td><a href="essays.html"> Essays </a></td>
		      <td>A list of my best essays, and a blogroll.</td>
    	</tr>
    	<tr>
		      <td><a href="personal.html"> Personal </a></td>
		      <td>About me.</td>
    	</tr>
    	<tr>
		      <td><a href="colophon.html"> Colophon </a></td>
		      <td>The page you're on right now.</td>
    	</tr>
  </tbody>

</table>

Target Audience
---------------

People with too much time on their hands.

Or anyone who cares about the web, economics, math, people, ideas, terrible advice, [magic ink](lists/things-i-think-about-often.html#Information%20architecture), or me.

Etymology
---------

The site name is . There is a pleasing visual symmetry to it.

## Inspiration {#inspiration}

Stealing ideas for specific elements, data representation, page types, content and .


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
  </tbody>

</table>


## Stack


This site is a collection of hand-written HTML files. Hosted on Github, served by Netlify.

Eventually, I might have to pick a static site generator to manage the sheer number of pages I plan to add, and to make writing easier with Markdown. But we'll cross that bridge once we get to it. Until then, I've found other ways to do things.

Features
--------

The design choices and constraints were largely decided by the principles set out above, and manifested themselves in certain specific ways:

*   Table of contents: The table is available on iPads too, but is hidden on mobile.
*   Always-accesible menus: Visitors should never have to scroll back up to go where they want to. Both the global navigation links and the table of content links stay fixed while you scroll through the page.
*   Dark mode: Monotone dark mode available (if you can find the switch), with smooth toggling and 10% brightness reduction on dark mode images. User preferences are stored locally.

Media
-----

Images are compressed using [Squoosh](https://squoosh.app) and uploaded directly to the site repository. Netlify's CDN is responsible for delivering and caching them alongside each page.

## Fonts


The main font used across this site is [Petrona](https://en.bestfonts.pro/font/proxima-soft), designed by Mark Simonson. It's one of the few fonts that has the full range of possible font-weights.

It is served (and cached locally) as a variable WOFF2 file. 

## Analytics


Site analytics provided by [Umami](https://umami.is/), a really cool self-hosted, open source, GDPR-compliant analytics project. This means no cookies, tracking or personal data collection.