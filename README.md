# MobileView
Mobile View Template Using Overscroll from Jonathan Azoff and iPhone Mobile Preview from beeker.io

Overscroll: https://github.com/azoff/overscroll

Mobile Preview: http://beeker.io/display-website-in-iphone-html-css-javascript

https://github.com/beeker1121/website-mobile-preview

-----

The combination of these two scripts solved an issue I was having in a class. We were required to create a simple mobile-only version of a website, and then add it to our body of work.  Since the site was not responsive and designed specifically to be displayed on a small screen, it became stretched out when viewed on a desktop.  I needed a way to restrict the viewport, but a simple iframe did not work due to the difference in resolution on mobile vs desktop. The mobile site within an iframe at the site's optimal width appeared much larger than a phone screen, which did not make for a good design aesthetic.

Basically, I wanted to mimic Chrome DevTools Device Mode using CSS and JS.

Beeker.io's Mobile Preview, or bioMp, solved the size issue by scaling the whole site down to fit within the desired dimensions by matching the CSS resolution of an iPhone screen. In my case, it needed to be 300px wide. I slightly modified the code to use a different photo of an iPhone that I preferred instead of what was included in the project.

To take this one step further, I wanted the displayed webpage to act as it would if you were actually looking at it on a phone, i.e., dragging to scroll, while also allowing for overscroll if you drag and release. For this, I implemented Jonathan Azoff's Overscroll script within the mobile site. 

One final modification was a custom semi-transparent round cursor I created to further mimic Device Mode. 

While the mobile site in this example is not responsive, the page containing the mobile site view is. When viewing the portfolio page on a screen below 455px, the entire iPhone mobile preview is hidden, and the regular mobile version is displayed.
