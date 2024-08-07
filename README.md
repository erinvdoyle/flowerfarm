# <Black Sheep Farm>

## Welcome to Black Sheep Farm, Cut Flower Farm & Venue <add logo and heading text>![alt text](http://url/to/img.png)
![alt text](https://github.com/[username]/[reponame]/blob/[branch]/image.jpg?raw=true)

The Black Sheep Farm website is an invitation for its visitors to connect with nature. This flower farm and events venue is set in the Wicklow Mountains of Ireland and offers a variety of outdoor activities and purposes: Garden walks, weekend yoga, floral design classes, a cut flower garden to build and bring home a bouquet, and an event space to host special occasions.

Users of the site will be able to find out about the people behind the farm and their origin story, beginning with a move from hectic city life to the Wicklow Mountains, and a mission statement for the "why" behind the farm. All of the information to either plan a day visit or inquire about booking the farm is contained within the Events and Visit pages. There is a class schedule newsletter to subscribe to and a contact form for events. The site is intended for adults and their family memebers and friends of all ages and backgrounds: Anyone who would enjoy spending time in a beautiful garden setting.

## Why Black Sheep Farm? 
We were tasked for our first project with Code Institute to build a site with a minimum of three pages ---. I wanted to create something I felt passionate about, so a romanticized version of my own home with its deep connection to nature fit that parameter. I chose to create this site and name it so as in a different life, my home and the land around it could be Black Sheep Farm. 

Because a wellness website was one of our project prompts, I gave the business a focus on slow-living, sustainability, and spending time outdoors. This lent itself to the plant and floral-based color palette and the style choices made along the way. It's so simple to get caught up in the demands of modern life. Sometimes we all need to stop and take a breath, feel the sun on our faces, listen to birdsong, and appreciate the beauty around us; if this site can evoke that sense, or better yet, encourage its viewer to do so, then it has been successful. Every project is a journey in itself, and on this one, I gathered visual inspiration from talented photographers and learned to let the design of the site follow organically.

<add screenshot from amiresponsive>

## Table of Contents
- [UXDesign] (#uxdesign)
- [Features] (#features)
- [FutureFeatures] (#futurefeatures)
- [Testing] (#testing)
- [Deployment](#deployment)
- [Credits](#credits)
- [Bugs] (#bugs)


## UX Design <add image of dahlias>
The design began with a photo of a field of dahlias for inspiration and the building of wireframes in Balsamiq. 

The 5 Planes of UX Design guided this process:

1. STRATEGY -
   To achieve a visually pleasing web experience that evokes a connection to nature and invites its visitors to plan either a day or an event out at the farm.

2. SCOPE -
   i.  An enticing landing page that displays the beauty of the farm's flowers while inviting visitors to explore the site with a simple layout.
   ii. A feel good origin story about literal and metaphorical black sheep and a mission statement to connect with the reader.
   iii. Visit and Events pages to display what the farm offers.

3. STRUCTURE -
   Four pages with clear purposes. Landing, About (titled "Our Story"), Visit, and Events.

4. SKELETON -
   Planned and depicted in wireframes

5. SURFACE - 
   A color palette based off of floral hues for images and feature elements and a neutral grey background to tie into the logo and farm name. Cards representing each page of the site are used on the landing page for visual interest. Images from the farm are used for the front of the cards and brief explanatory text and a link to the page described reveal on hover. Background colors on the back of the cards are taken from the landing page images using a color picker. Dark grey text is used in favor of black for ease of reading.

## Features   
- Header and Navigation
  - The header is in a fixed position and remains static at the top of the page.
  - The navigation element features at the top inside the header where the logo and name are located on the left side. These are clickable and return the user from any page or position on the site to the landing page. 
  - For mobile screens, the right side features a toggle bar which opens a menu when clicked to display links to the four pages: Home, Our Story, Visit, and Events.
  - For tablet-sized screens and larger, this toggle gives way to links to the four pages. 

- Index.html
  - The landing page features a hero image with one of the farm's mascots at the forefront: A black sheep. Cover text at the bottom of the image lists the farm's full name.
  - Beneath the hero image and cover text, four flip cards introduce the three remaining pages and a coming soon feature: A bouquet box. The front of these cards show an image relevant to the page content (Dahlias for Our Story/about, a garden pathway for Visit, and a decorated table for Events). These cards flip using the CSS transform property. The brightly colored back side of each card contains a short explanation of each page and a link.

- Our Story
  - This about page features a newspaper-like format with four images sized to echo the landing page's flipcards. The main content is split into two containers: The left side contains the images and a brief introduction, while the right side contains text about the owners and their vision for the farm. The background colors are an earthy pale peach and a muted sage green to give the page a calming, comforting, and homey feel appropriate to the content. 

- Visit 
  - The Visit page contains a call to subscribe to the class schedule. The input box and a description of the classes offered is overlayed over a background image of a bouquet being arranged. The right half of the screen displays four images with border and padding such that they appear in the style of polaroid photographs. Each image is captioned to describe the class or farm activity they depict: Garden yoga, floral arrangement, family-friendly garden walks, and the on-site cafe.

-Events
  - This page introduces the different opportunities to book the farm as the venue for a special occasion. There is a hero image of an events table, text below it to detail types of events, and an image with a contact form overlayed so that users can get in touch with the owners about scheduling an event.

- Footer
  - The footer houses four icons spaced evenly across the bottom of the page. These icons link to the farm's social media: Facebook, X, Instagram, and Youtube.

- Site Consistency
  - Neutral and compimentary floral colors paired with uniformly sized images are used to create a cohesive feel. Each page features either a hero image with text beneath, or a split screen style format, or a combination of both, to maintain consistency.

## Future Feature Developments
- Bouquet CSA: A sign up and info page for a monthly subscription bouquet box (as shown on flipcard #4 on the landing page).
- Flowers: A feature page with images of each garden and the varieties of flowers grown.
- A dynamic bi-weekly calendar on the Visit page to view and reserve a spot for upcoming classes. 
- A scrolling or dynamic image gallery of events.
- "LambCam": Livestream video of the farm's lambs.
- Streamable content: Yoga and meditation classes for non-local visitors and an audio gallery of Black Sheep Farm nature sounds, forrest bathing, etc.

## Deployment

## Credits
- Content 
  - Flip Card tutorial from W3Schools
  - Ribbon tutorial from W3Schools
  - Adding a form to an image W3Schools
  - Footer tutorial from FreeCodeCamp

- Media
  - Logo Icon from Icon8
  - Web Font "Sail" from Google Fonts
  - Font Awesome for favicon, burger menu, and social media icons
  - imagecolorpicker.com color picker for background colors inspired by images
  - Images from freepik.com and floretflowers.com
 

## Testing
- Feature testing
- Browser compatibility
- Responsiveness
- Lighthouse testing (consider using WAVE as an extra accessibility test) 
- Code validation


## Bugs
- Solved Bugs
  - When I deployed my site, I realized that my header left a gap at the top of the screen that became visible on some mobile devices when the user scrolled. I added a property of "top: 0;" to solve this issue.
  - When I began testing my deployed site on different screens and devices, I realized my photos were loading slowly. I converted them from jpg to webp to lower the resolution and decrease load time.
  - The form text and content on the Events and Visits pages, as well as the text of the "Our Story" div on the about page, overflowed their containers when tested on mobile device landscape dimensions. Adjusting devtools to the proper dimensions for landscape was something I neglected to do and I did not catch the bug until testing landscape mode on my own device. I adjusted the height of each container and added a negative margin-bottom to the Visit form container.