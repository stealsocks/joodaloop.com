---
title: "Building Faster Sites"
date: 2019-02-14T15:36:09-06:00
toc: true
description: "Speeding up page loads for fun and profit."
summary: 12
---


## Meta 
To start off with, here's some rules of thumb. 

* Static sites will load faster than ones that rely on Javascript-based data-fetching. 
* An HTML file with local scripts and CSS will load faster than one that has links to external files. Which in turn is faster than adding in images, fonts and other media files. 

## Testing 

You need to know what parts of your page need optimizing before you get started. This is where testing tools come in: they take in a webpage URL and generate a performance report for that particular page. I really like [Yellow Lab Tools](https://yellowlab.tools/about), but you can also use [WebPageTest](https://www.webpagetest.org/), [GTMetrix](https://gtmetrix.com/), or Google's [PageSpeed Insights](https://pagespeed.web.dev). 

## Images 

Pop all your images into [Squoosh](https://squoosh.app/) and see how low you can get the size before quality starts to deteriorate visibly. Or use something like [Kraken](https://kraken.io/web-interface), if you don't want to adjust the quality manually. As far as I can tell, using [.webp](https://en.wikipedia.org/wiki/WebP) files instead of regular JPEGs provides negligible benefits for most images. And the latter is almost universally supported. 

## CSS & JS files 

## Using Pre-fetch 
Check out [Paco's site](https://paco.me/). You see how fast those page transitions are? They don't even feel like page loads, but a local app. As far as I can tell, it's because he uses Next.js's [component](https://nextjs.org/learn/basics/navigate-between-pages/client-side). The component, in turn, uses the [pre-fetch](https://developer.mozilla.org/en-US/docs/Web/HTML/Link_types/prefetch#:~:text=The%20prefetch%20keyword%20for%20the,fetching%20and%20caching%20the%20resource.) attribute to load pages in the background. So when the user clicks on a link, they jump to a page that's already been fetched. <link rel="prefetch" href="bad-advice.html" as="document">

## Fonts 
First, convert them to WOFF2, which makes them 30% smaller than WOFF, and more ~60% smaller their TTF or OpenType counterparts. You need to set up cache-headers for these. On Netlify, mine look like