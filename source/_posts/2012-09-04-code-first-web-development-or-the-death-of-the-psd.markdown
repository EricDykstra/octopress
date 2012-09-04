---
layout: post
title: "Code-First Web Development - Or - The Death of the PSD"
date: 2012-09-04 07:44
comments: true
categories: 
- Web Development
- Web Design
- Process
---

There is a revolution happening in the world of web design and development. Designing a website in a raster Photoshop file and handing it over to a person or team to "chop" it into HTML and CSS doesn't make sense any more in a world of countless different displays and rapid iteration web development.

What kind of display are you reading this post on? A 27" 2nd display, 13" laptop display, an Android smartphone, and a retina iPad display are all vastly different mediums. In 2002, when more than half of displays were 800x600 resolution, and most of the rest were 1024x768, it made sense to design a website with 800x600 in mind. Now, however, designing a website for one resolution in Photoshop just doesn't make sense. As retina displays (and other high pixel density displays) become more popular, it makes even less sense to start from raster-based PSDs.

The solution is to start with wireframing the UI, and then jumping straight into the code. Why create all the elements in Photoshop when many of them can be created in scalable, resizable, retina-friendly CSS? Whether you prefer pen and paper or like to use a mock-up tool such as Balsamiq, it doesn't really matter; the idea is that you get the design and feel down in wireframe, and then go straight to coding a working website. With HTML5 and CSS3 templates and frameworks such as HTML5 Boilerplate and Twitter Bootstrap, it's easier than ever to start building a responsive, grid-based website. This blog is currently powered by a blogging framework called Octopress that has these responsive features built in. Even though I haven't taken the time to customize it very much yet, it looks great on any size display, from mobile devices to large external displays. I have the framework, the next step is to turn it into what I want it to look like. 

A common pitfall of using these frameworks is that sites end up looking like a website based on a specific framework. Another site of mine, [Fantasy SOS](http://fantasysos.com/), is based on Twitter Bootstrap. It's not the prettiest thing ever, and it is obvious that it's a Bootstrap site, but it took less than an hour to customize it and give it a distinct personality. A couple more hours and I can make it look like it never was a Bootstrap site to begin with. This trap can easily be avoided by wireframing your site first, and fitting the framework into your idea, rather than having the framework shape your site.

Another huge advantage of designing within a working website is that it makes rapid development much easier. Instead of going back to Photoshop whenever you want to change the color or size of a button, it's just a line or two of code in your CSS. If you want to run an A/B test, a few lines of code and you can have a completely different call to action. If you're designing for a client, and you comment your HTML and CSS sufficiently, they can make their own changes with a bit of coaching. Rapid development is so essential to many businesses these days, and and building a website with a code-first mentality (removing Photoshop) brings you one step closer to production with every change.

I realize that designers may be resistant to relinquish Photoshop, and I myself had been playing around in that program and figuring it out for years before I started doing any sort of real web development, but the days of coming up with a complete layout in Photoshop are over. For elements that can't easily be made in CSS, it's time to start using Illustrator (if you aren't already). When SVG support becomes universal, you can have scalable images baked into your code and you will want to be ready when that happens. Not every designer will be willing to learn how to turn a wireframe with notes into HTML and CSS, but the ones that do will be at a distinct advantage. Think of yourself as an executive at a company that wants a new website. Between two equally talented designers, would you prefer the one that shows you an image file and says "how's this?" and goes on to describe how elements interact, or would you prefer the one that sends you a link to a working mockup of a website with working transitions?

The days of mocking up a website in Photoshop from wireframe all the way to the step just before implementing it in HTML/CSS are coming to an end. How long before it happens is anyone's guess, but I believe anyone involved in web design should be learning the skills it takes to cut Photoshop out of the picture. When the scale tips, bosses and customers aren't going to be satisfied just seeing a mockup as a jpg file.

Agree? Disagree? Let me know in the comments or send me an [email](mailto:eric@ericdykstra.me) with your thoughts and I'll get back to you.