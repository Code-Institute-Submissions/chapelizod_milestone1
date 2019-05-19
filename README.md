# Chapelizod Visitor Information

Chapelizod is a small village close to Dublin city center in Ireland. With many
historical featues, it is a relativly large tourist attraction compared to 
other similar sized towns in Ireland.

"Chapelizod Visitor Information" is a website that aims to provide information
to potential visitors to the town, so that they may plan their visit. Travel 
information such as bus routes is prvided. The site features photographs of 
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
the town. It should be easy to use, compatible with a wide vareity of devices 
and browsers. Information should be easy to locate & fast to load. The main 
visitors to the site are expected to be tourists.

Another goal is to increase the towns social media presence. It is thought that 
increased social media presence will bring more tourism to the town.

**User stories**

*User story 1*

As a potential tourist to the town, I visitied the site on my computer. I was 
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

The "media" page provides videos that hightlight the culture of the town as 
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
itself to render better on a small screen. Bootstrap provides exelent 
functionality to acheive this.

*Images page*

![Images page on mobile](/assets/wireframes/mobileimages.png)

The images page is very simial to the desktop version only on smaller devices, 
the images shrink to save the user from having to scroll around to see all of 
the image.

*Media page*

![Media page on mobile](/assets/wireframes/mobilemedia.png)

The media page is simailar to the desktop version. Again we use Bootstrap to 
reorietate that grid to provide a better user experiece for smartphones.

## Features

In this section, you should go over the different parts of your project, and describe each in a sentence or so.
 
### Existing Features
- Feature 1 - allows users X to achieve Y, by having them fill out Z
- ...

For some/all of your features, you may choose to reference the specific project files that implement them, although this is entirely optional.

In addition, you may also use this section to discuss plans for additional features to be implemented in the future:

### Features Left to Implement

It would be preferable to have the option of changing the language of the site 
to accomodate a wide range of languages.

A map feature showing the location of places of interest would be another nice 
and useful feature. Perhaps this feature could tie in with Google maps to 
provide the tourist with spoken directions to the area they want to visit.

Move the captions from the carousel images to an area undereath the images as 
the captions are not currently displaying properly on mobile devices.

## Technologies Used

In this section, you should mention all of the languages, frameworks, libraries, and any other tools that you have used to construct this project. For each, provide its name, a link to its official site and a short sentence of why it was used.

- [JQuery](https://jquery.com)
    - The project uses **JQuery** to simplify DOM manipulation.



Pencil (link)
Paint.net (link)

Fonts: Tangerine gives a nice historic look for headings
Pathway Gothic One gives an nice historic look but is more readable than Tangerine.

## Testing

![test1](/testing/testing1.jpg)

![test2](/testing/testing2.jpg)

![test3](/testing/testing3.jpg)

![test4](/testing/testing4.jpg)

![test5](/testing/testing5.jpg)

![test6](/testing/testing6.jpg)

![test7](/testing/testing7.jpg)

![test8](/testing/testing8.jpg)

## Deployment

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub Pages or Heroku).

In particular, you should provide all details of the differences between the deployed version and the development version, if any, including:
- Different values for environment variables (Heroku Config Vars)?
- Different configuration files?
- Separate git branch?

In addition, if it is not obvious, you should also describe how to run your code locally.


## Credits

Video used with permission of Chapelizod Tidy Towns.

Chapelizod walkthrough thanks to HERITAGE media

Podcasts used with permission of Chapelizod historical society

Beautyful Chapelizod by allthatsbeautiful1

Photographs by Andrew Dempsey.

chap.ie

### Content
- The text for section Y was copied from the [Wikipedia article Z](https://en.wikipedia.org/wiki/Z)

### Media
- The photos used in this site were obtained from ...

### Acknowledgements

- I received inspiration for this project from X
