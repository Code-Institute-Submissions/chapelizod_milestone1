# Chapelizod Visitor Information

Chapelizod is a small village close to Dublin city center in Ireland. With many
historical features, it is a relatively large tourist attraction compared to 
other similar sized towns in Ireland.

"Chapelizod Visitor Information" is a website that aims to provide information
to potential visitors to the town, so that they may plan their visit. Travel 
information such as bus routes is provided. The site features photographs of 
historical buildings and places of interest that a tourist may decide they want 
to see. The website provides podcasts that give historical information that 
should make visitors trips more interesting. Social media links to the town 
council are provided that will give up to date information about events in the 
town. Residents of the town could also find some use for the site, perhaps they 
want to discover some of the history of the town or find the latest news on 
events.

The website is also designed to work on smartphones. This will allow any 
visitors who are already in the town use the website on the move, allowing them 
to enjoy their visit more and be reminded of the town's attractions.

## UX
 
**Goals of the website**

The main goal of the website is to provide information to anyone interested in 
the town. It should be easy to use, compatible with a wide variety of devices 
and browsers. Information should be easy to locate & fast to load. The main 
visitors to the site are expected to be tourists.

Another goal is to increase the towns social media presence. It is thought that 
increased social media presence will bring more tourism to the town.

**User stories**

*User story 1*

As a potential tourist to the town, I visited the site on my computer. I was 
able to see all of the attractions of the town and plan my visit.

*User story 2*

As a travelling visitor to the town, I visited the website and was able to 
easily find out which bus route to take.

*User story 3*

As a visitor in the town, I was able to visit the website on my smartphone
enabling me to find directions to the landmarks I wanted to see.

*User story 4*

As a resident of the town, I was able to easily find links to the towns social 
media presence/

# UI design

**Color scheme**

The color choices were made to reflect the historical nature of the town - a 
key selling point. Heavy use of color was avoided and used only in necessary 
places such as photographs and videos. The main colors used were black and 
white along with some light blue. A dark blue was used to put particular 
emphasis on the social media links in order to encourage the visitor to join 
the towns social network groups.

**Layout (desktop)**

The site consists of four pages, styled very similarly to give a consistent 
user experience. The color scheme consists largely of black and white with 
hints of light blue throughout. This scheme was chosen to help portray the 
historical nature of the town.

To help guide development, wireframes were produced using the "Pencil" 
wireframing tool. See the section "Technologies Used" for more detailed 
information about Pencil.

*Home page*

![Home page on desktop](/assets/wireframes/desktopindex.png)

Wireframe 1: The home page. Here we see the main page of the website that will 
be the first port of call for a user. We see that the navbar contains the 
website name and a short description of the sites purpose. We see that there is 
a large image in the center of this page. This image will attempt to show one 
of the main attractions of the town to a user upon visiting the site. We also 
see that travel information and social media links are presented straight away 
without a user having to click on any buttons, this is to help promote the town 
by giving the user information at a glance.

*About page*

![About page on desktop](/assets/wireframes/desktopabout.png)

Here we see the "about" page. This page will give more detailed information 
about the towns attractions. It will also attempt to sell the town to a 
potential tourist by giving some historical information. Note that the navbar 
has the "about" button highlighted. This indicates that the navbar should 
provide feedback to the user. This will help make the user experience as 
satisfying as possible. Note that the social media links and travel information 
are still prominent on the page.

*Images page*

![Images page on desktop](/assets/wireframes/desktopimages.png)

Here we see the "images" page. This page presents the user with a carousel of 
photographs from the town. The photographs will highlight some of the more 
attractive features of the town as well as providing directions to that 
attraction.

*Media page*

![Media page on desktop](/assets/wireframes/desktopmedia.png)

The "media" page provides videos that highlight the culture of the town as 
well as its scenic beauty. A podcast is also provided here that is intended to 
teach the visitor some of the historical features of the town.

**Layout (mobile)**

*Home page*

![Home page on mobile](/assets/wireframes/mobileindex.png)

Here we see the same home page as above only this time as how it should be 
rendered on a smartphone. Note that the navbar is reactive and has collapsed 
into a single button. This should make the user experience more pleasing for 
smartphone users. The image has shrunk to fit a smaller screen. We see that 
te side by side nature of the footer cells has changed to a vertical 
orientation.

*About page*

![About page on mobile](/assets/wireframes/mobileabout.png)

Here we see the mobile version of the about page. It contains the same 
information as the desktop version only this time, the grid has reorganized 
itself to render better on a small screen. Bootstrap provides excellent
functionality to achieve this.

*Images page*

![Images page on mobile](/assets/wireframes/mobileimages.png)

The images page is very similar to the desktop version only on smaller devices, 
the images shrink to save the user from having to scroll around to see all of 
the image.

*Media page*

![Media page on mobile](/assets/wireframes/mobilemedia.png)

The media page is similar to the desktop version. Again we use Bootstrap to 
re-orientate that grid to provide a better user experience for smartphones.

## Features

The website consists of four pages, index.html, about.html, images,html and 
media.html. Each page uses the Bootstrap framework extensively. The Bootstrap 
documentation was consulted regularly to ensure each page was responsive.

Bootstrap.js enables the use of a carousel on the images page as well as 
helping to implement a collapsible menu. The navbar used at the top of each 
page reacts to mouse hovers and provides feedback to the user.

### Features Left to Implement

It would be preferable to have the option of changing the language of the site 
to accommodate tourists that do not speak English. This would help increase the 
potential number of tourists that might visit.

A map feature showing the location of places of interest would be another nice 
and useful feature. Perhaps this feature could tie in with Google maps to 
provide the tourist with spoken directions to the area they want to visit.

It will be necessary to move the captions from the carousel images to an area 
underneath the images as they are not currently displaying properly on mobile 
devices.

The jumbotron used on the home page could be updated to show a slide show of 
images from the town as opposed to the static image.

## Technologies Used

The following technologies and frameworks were used in the development of this 
website:

*Icons*

Fontawsome (https://fontawesome.com/)

*Fonts*

Google fonts (https://fonts.google.com/)

*Website layout and functionality*

Bootstrap (https://getbootstrap.com/)

*IDE*

Cloud 9 (https://aws.amazon.com/cloud9/)

*Wireframing*

Pencil (https://pencil.evolus.vn/)

*Photograph editing*

Paint.net (https://www.getpaint.net/)

*Video hosting*

Youtube (https://www.youtube.com/)

## Testing

Testing was performed on a wide variety of devices and browsers to check for
compatibility and responsiveness.

![IPad mini Safari Home](/testing/testing1.jpg)

Test 1 The "home" page rendered on an IPad mini in horizontal orientation, using 
the Safari browser.

![IPad mini Safari About](/testing/testing2.jpg)

Test 2 The "about" page rendered on an IPad mini in horizontal orientation, using 
the Safari browser.

![IPad mini Safari Media](/testing/testing3.jpg)

Test 3 The "media" page rendered on an IPad mini in horizontal orientation, using 
the Safari browser.

![Iphone 6s Home](/testing/testing4.jpg)

Test 4 The "home" page as seen on an IPhone 6s.

![Iphone 6s Pictures](/testing/testing5.jpg)

Test 5 The "pictures" page as seen on an IPhone 6s.

![Desktop Chrome Home](/testing/testing6.jpg)

Test 6 The "home" page as seen on a desktop computer, running Windows 7, 
using Chrome browser

![Desktop Internet Explorer Pictures](/testing/testing7.jpg)

Test 7 The "pictures" page as seen on a desktop computer, running Windows 7, 
using Internet Explorer browser

![Desktop Firefox Media](/testing/testing8.jpg)

Test 8 The "media" page as seen on a desktop computer, running Windows 7, 
using Firefox browser

## Deployment

As the project was developed, regular commits were made to Github. Commits were 
made as new pages were added to the website. Once all pages were added, commits 
consisted of styling improvements and error corrections.

Development took place on the Cloud 9 platform. One serious issue encountered 
when using this platform presented itself when final deployment was attempted. 
Cloud 9 rendered the webpage perfectly with absolute file paths, while the 
final hosting platform (Github pages) did not render the site properly with 
absolute file paths.

In total, the project resulted in 20 commits to Github.

**Commit summary**

Commit number 20: updates to Readme

Commit number 19: added UX section to readme

Commit number 18: Changed home page image

Commit number 17: Updates to Readme, adjusted some font sizes on footer

Commit number 16: Fixed errors with file paths

Commit number 15: minor changes to directory structure

Commit number 14: Minor styling changes made to media page

Commit number 13: updated media page to be more responsive, made adjustments to home page

Commit number 12: added media page, updated directory structure

Commit number 11: added about page

Commit number 10: added pictures page

Commit number 9: Improved layout, improved look of icons

Commit number 8: Updated readme, adjustments to index page

Commit number 7: Removed cards from footer, added row+cols for better look

Commit number 6: Added photos & fonts

Commit number 5: Styled footer cards

Commit number 4: Added jumbotron and cards to index.html

Commit number 3: Worked on Readme.md, styling on index.html

Commit number 2: Basic directory structure setup

Commit number 1: Initial commit

## Credits

Videos used with the permission of Chap.ie

Podcast used with permission of Chapelizod historical society.

Photographs by Andrew Dempsey.