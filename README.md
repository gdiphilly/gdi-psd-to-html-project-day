Photoshop for Web Design
======================

Materials for PSD to HTML Project Day, developed by [Zoe Rooney](http://zoerooney.com) for Girl Develop It - Philadelphia. Template forked from [Intro to Web Concepts](https://github.com/girldevelopit/gdi-intro-web-concepts).

The is more of a working session/ guided practice session than a class. There's meant to be very limited group lecture time and a lot of work time with support from a high TA-to-learner ratio. It's roughly designed for a single, 5 hour day, but is pretty flexible timing-wise since it's so open-ended.

## Suggested course description is below:

By now, you may have taken a couple of HTML/CSS classes or dabbled with it on your own. It's time to take what you've learned and practice your skills by building a webpage from scratch.

Join us in a group setting and create a site from a design file we provide. Experienced TAs will be there to get you started and help you out along the way. The main purpose of this class is to provide you with supported work time focused around a common, simulated but realistic project to reinforce your skills. You will learn the process of breaking down a mockup, best practices in getting started, and gain experience constructing the main elements of a webpage.

We will NOT be spending much time on the Photoshop aspects of this process in this class, instead focusing on the problem-solving and strategy that goes into "reading" a design file and building a website from that file, while practicing our HTML and CSS skills. You don't necessarily need Photoshop - all assets and information about typography/ font styles will be provided - but you may find it useful and interesting to be able to reference the PSD while you work.

If you want to become a front-end developer, you should attend this session. Come prepared with a laptop, snacks/drinks & determination!

Note: This is a working session, NOT a lecture. It is limited to 15 spots. You must score at least 50% on [this quiz](http://pixelpushstudio.com/gdi/jquizzy.htm) to register.

## Theme customization

You can change theme colors by changing the theme css to any of the following options:
```html
  <link rel="stylesheet" href="css/theme/gdidefault.css" id="theme">
  <link rel="stylesheet" href="css/theme/gdilight.css" id="theme">
  <link rel="stylesheet" href="css/theme/gdisunny.css" id="theme">
  <link rel="stylesheet" href="css/theme/gdicool.css" id="theme">
```
You can change the text editor theme by changing the highlight.js css to the following options:
```html
  <link rel="stylesheet" href="lib/css/dark.css">
  <link rel="stylesheet" href="lib/css/light.css">
```
You can change transition by changing the reveal transition property in Reveal.initialize
```javascript
  Reveal.initialize({
  				transition:  'default', // default/cube/page/concave/zoom/linear/none
  			});