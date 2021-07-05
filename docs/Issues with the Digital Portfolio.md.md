# Issues with the Digital Portfolio
The whole reason why I decided to recode Deltaline in HTML was mainly because I already knew how to do code in HTML, and in Python. Soon I will be moving it to Vue.js and/or Django (to hopefully to use python as well). The Google Sites version has some major issues, and mostly regarding load times. 

## Loading Times

![](img/test2.png)

*Lighthouse Test on the Google Sites version (the home page)*

![](img/test1.png)


*Lighthouse Test on the self-made (hosted on Netifly) version (home page)*

As you can see, there is a massive improvement when it comes in loading times with the self-coded version. This was done on my laptop running the latest version of chrome and running Windows 10 Pro as well. All the conditions were the same when testing (the same chrome extensions, etc)

This was one of the biggest reasons why I decided to make the website myself. Without Google's slow font api, and with full control over how I add images and other content, this allows for a lag-free experience. I'll try my best to reduce as much lag as possible.

## How the Website Looks 

Google Sites is very basic in design; it was meant to be easily deployed without having to touch any of the HTML, CSS, PHP, JS, or .Net code and framework. And since it's very basic in design, it doesn't allow for much control and how the website is built. Essentially, it's just the worse version of wordpress. So I decided to just rewrite the whole entire thing from the start. 

## Optimizations

Google Sites only accepts .png, .jpg, and .gif image files. Nothing else. This isn't good for a website where it needs to load in HD assets, and takes a toll on Google Sites. With Netifly, it allows for compression and combined with Cloudflare, it allows for a very fast loading experience. In order to optimize the website, I used only svg files in order to reduce loading times, and mainly used the Bootstrap lib for mobile support.