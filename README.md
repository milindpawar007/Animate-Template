# Animate-Template
## `TITLE` & `PAGE` :mag:
**ANIMATED-TEMPLATE** - A Template project for making great landing pages with animations

:arrow_right_hook: [Check this out!](https://https://milindpawar007.github.io/Animate-Template/) :leftwards_arrow_with_hook:

## `WHAT` is the `MOTIVATION` behind this project? :bulb:
:telescope: The modern web is now based on components. Every webpage/webapp we come across are build with components. Some common examples are menu bar, search bar, navigation bar, share-ability to common social media platforms etc. Of course some of these components needs to be hooked up to bankend services to perform the desired tasks — thats another thing, but to re-create these components from scratch would be very tedious and time consuming.

Enter [Tailwind CSS](https://tailwindcss.com/) - A Utility first CSS Framework for rapidly building custom designs -- Where we leverage the power of pre-built components to make out webpages/webapps. :white_check_mark: 

Then we take it one notch higher — even the basic webpages (i.e landing page, profile page, shopping card page) have the same properties/functionalities these days — So why not leverage the power of pre built Template pages :interrobang:

Enter [Creative Tim and their free Tailwind starter kit](https://www.creative-tim.com/learning-lab/tailwind-starter-kit/presentation). I found some components for popular front-end frameworks like React/Angular/Vue etc  -- that can potentially be connected to a backend service to update those components. :link:

Lessons? - Don’t reinvent the Wheel! Build around it!! :rocket:


##How do you load third-party script efficiently?
If a third-party script is slowing down your page load, you have several options to improve performance:

Load the script using the async or defer attribute to avoid blocking document parsing.

Consider self-hosting the script if the third-party server is slow.

Consider removing the script if it doesn't add clear value to your site.

Consider Resource Hints like <link rel=preconnect> or <link rel=dns-prefetch> to perform a DNS lookup for domains hosting third-party scripts.

Use async or defer
JavaScript execution is parser blocking. This means when the browser encounters a script it must pause DOM construction, hand this over to the JavaScript engine and allow script execution before proceeding with DOM construction.

The async and defer attributes change this behavior.

With async, the browser downloads the script asynchronously while it continues to parse the HTML document. When the script finishes downloading, parsing is blocked while the script executes.

With defer, the browser downloads the script asynchronously while it continues to parse the HTML document. The script doesn't run until the parsing is complete.
<img src="https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/loading-third-party-javascript/images/image_13.png"></img>

## `WHAT` is this project `ABOUT`? :clipboard:
This project demonstrates the ideas behind creating **Reuseable UI Components** which can potentially be hooked up to a backend webservice for dynamically generating/displaying the information in the Components

## `HOW` is this project `IMPLEMENTED`? :gear: 
This project is implemented with the following steps
* Download the ***starter kit*** from the ***creative tim*** site.
* Find the html for the ***landing page*** -> get playful and try to get hang of how things are here (everything is foms and cards!)
* Comment on the HTML doc for better understanding
* Modify the local assets with some cloud asset pictures from the ***Unsplash Page***
* Get Random user pics from ***RandomUser*** for the headshot/display pictures
* Impleted ***AOS(Animate On Scroll)*** animation library for scroll based animations (the CDN for AOS is implemented here)
* Get ***PLAYFUL!!!***

## `WHAT` are the basic `BUILDING-BLOCKS` behind this project? :hammer_and_wrench:
* [Font Awesome](https://fontawesome.com/) -> The one with those awesome icons!
* [Tailwind CSS](https://tailwindcss.com/) -> The one for rapidly building custom designs!
* [Creative Tim](https://www.creative-tim.com) -> The one with the Ready-to-Enhance templates!
* [Animate On Scroll](https://michalsnik.github.io/aos/) -> The one with the Animate on scroll library!
* [Unsplash](https://unsplash.com/) -> The one with those high quality free photos!
* [Random User](https://randomuser.me/) -> The one for generating random user properties!

## `WHAT` are some of the `LEARNING-RESOURCES` you used? :books:
* [Loading 3rd party JS](https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/loading-third-party-javascript#use_async_or_defer)
* [HTML formatter](https://webformatter.com/html)

## `WHAT` are some of the possible future `ENHANCEMENT` ideas for this project? :nut_and_bolt:
* Try to optimize the Animations for better UX
* Download the REACT/ANGULAR/VUE components from Creative tim, hook it up to a backend webservice for the possible features
* Change the UI animations with your assets to make it your own!
* Make it more responsive/accessible for mobile devices.
* Enhance the performance of the page
