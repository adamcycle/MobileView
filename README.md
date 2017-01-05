# MobileView
Mobile View Template Using Overscroll from Jonathan Azoff and iPhone Mobile Preview from beeker.io

Overscroll: https://github.com/azoff/overscroll

iPhone Preview: http://beeker.io/display-website-in-iphone-html-css-javascript

-----

The combination of these two projects solved an issue I was having in a class. We were required to create a simple mobile-only version of a website, and then add it to our body of work.  Since the site was not responsive and designed specifically to be displayed on a small screen, it became stretched out when viewed on a desktop.  I needed a way to restrict the window size, and I did not want to use an iframe due to the difference in resolution on mobile vs desktop. The iframe would have to be larger than normal which did not make for a good design aesthetic within my class portfolio site, and it was not an accurate representation of the mobile site.

I basically wanted to find a way to display the site the way Chrome DevTools Device Mode displays a responsive site and accomplishing this with CSS and JS.

Beeker.io's Mobile Preview, or bioMp, solved the size issue by scaling the whole site down to fit within the desired dimensions by matching the CSS resolution of an iPhone screen. In my case, it needed to be 300px wide. I slightly modified the code to use a different photo of an iPhone that I preferred instead of what was included in the project.

To take this one step further, I wanted the displayed webpage to act as it would if you were actually looking at it on a phone, i.e., dragging to scroll, while also allowing for overscroll if you drag and release. For this, I implemented Jonathan Azoff's Overscroll project within the mobile site. 

One final addition was a custom semi-transparent round cursor I created to further mimic Device Mode. 
