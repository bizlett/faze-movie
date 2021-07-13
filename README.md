# **FAZE the Movie**

![Mokeup image]()

## **Goal for this project**

FAZE is an upcoming movie, due for release autumn 2021. A contained sci-fi thriller, this movie is high stakes, high tension and high altitude - literally. This top secret mission is under wraps at the moment, but you can follow us to get the latest exclusive news as it comes in, and of course book your special ticket deals when we announce our theatres later this year. This is one you won't want to miss!

Thank you for visiting my project! If you have any feedback or questions, head over to my GitHub contact details and feel free to reach out to me. 

---
<a></a>

## Table of Contents
1. [UX](#ux)
    * [User Stories](#user-stories)
        * [First Time Visitor Goals](#first-time-visitor-goals)
        * [Returning Visitor Goals](#returning-visitor-goals)
        * [Frequent Visitor Goals](#frequent-visitor-goals)
    * [Business Goals](#business-goals)
    * [Design Choices](#design-choices)
        * [Fonts](#fonts)
        * [Icons](#icons)
        * [Logos](#logos)
        * [Colors](#colors)
        * [Structure](#structure)
        * [Imagery](#imagery)
2. [Wireframes](#wireframes)
3. [Roadmap](#roadmap)
    * [Existing Features](#existing-features)
    * [Future Features](#future-features)
4. [Technologies](#technolgies)
5. [Testing](#testing)
    * [Validator Testing](#validator-testing)
    * [Known Bugs](#known-bugs)
6. [Deployment](#deployment)
7. [Credits](#credits)
    * [Code](#code)
    * [Media](#media)
    * [Acknowledgements](#acknowledgements)

<a name="ux"></a>

## **UX**

<a></a>

### **User Stories**
#### **First Time Visitor Goals**
* As a first time user, I want to easily understand the purpose of the site.
* As a first time user, I want to easily navigate around the site.
* As a first time user, I want content to load quickly.
* As a first time user, I want to find out what the film is about.
* As a first time user, I want to know when the film is being released.
* As a first time user, I want to book tickets for the film.

#### **Returning Visitor Goals**
* As a returning user, I want to know who is in the film and what else they have done.
* As a returning user, I want to know who is making the film and what else they have done.

#### **Frequent Visitor Goals**
* As a frequent user, I want to know the latest updates on the film.
* As a frequent user, I want to see the latest content released about the film.

<a></a>

### **Business Goals**
* Create an online presence for the film
* Let users experience the story
* Offer shareable video marketing content
* Build a buzz around the film ahead of its release

<a></a>

### **Design Choices**
#### *Fonts*
I selected all my fonts from [Google fonts](https://fonts.google.com/).

The film title on the hero image text overlay has its own font in order to make it stand out. I used [Syne Mono](https://fonts.google.com/specimen/Syne+Mono?category=Monospace&preview.text=FAZE&preview.text_type=custom). I added text-shadow with the highlight mandarin color to really accentuate the film title, lifting it from the page.  

I decided to stick with a strong fonts for the headings, choosing [Tourney](hhttps://fonts.google.com/specimen/Tourney?category=Serif,Sans+Serif,Display,Monospace) for my section headings. 

The overall content is written in [Montserrat](https://fonts.google.com/specimen/Montserrat?category=Serif,Sans+Serif,Display,Monospace&query=montserrat), with PT Sans as the secondary and Gill Sans font as the failsafe fallback! 

#### *Icons*
My icons have been sourced from [Font Awesome](https://fontawesome.com/). I selected only free icons that are self-explanatory and in keeping with the stripped back design of the website. They have been styled in keeping with the website.

#### *Logos*
All of my logos are images which I have then styled with CSS. Most of my logos were sourced via Google search, I tried to source logos with transparent backgrounds for aesthetic reasons. I also used [CleanPNG](https://www.cleanpng.com/) and [PNGHut](https://pnghut.com/) for a couple of the logos, specifically to find high quality images with transparent backgrounds.
        
#### *Colours*
I used [Coolors](https://coolors.co/) to put together a palette for my website. I used my hero image as the starting point, using a colour picker to draw out blues and oranges initially. 

<img src="../assets/images/readme/coolors-palette.png" alt="coolors palette for Faze website">

I decided that blues were a little overwhelming, losing that sense of being in space that I wanted to tap into with the colours of the wesbite. I established a slightly more muted palette for the general theme, leaning more towards greys with blue hints instead incorporating the two palettes together. I kept the bright mandarin orange to accent, creating a pop of life. 

<img src="../assets/images/readme/coolors-colourblind.png" alt="coolors palette for Faze website">


#### *Structure*

I have used [Bootstrap v5.0.2](https://getbootstrap.com/) to create the overall structure of my website.

#### *Imagery*

Still images on the website were sourced from [Pexels](https://www.pexels.com/). I specifically chose landscape photos for the gallery and hero image for continuity in design as my gallery is displayed on a page instead of using a carousel or similar.

I cut my trailer together using [Microsoft Photos app](https://www.microsoft.com/en-gb/windows/photo-movie-editor). The royalty free, stock music was provided through the editing app. The stock footage in the trailer was sourced from [Pexels](https://www.pexels.com/).

All my images and the trailer have a border radius applied to give them a futuristic feel.

[Back to Top](#table-of-contents)

---

<a name="wireframes"></a>

## **Wireframes**

I used [Balsamiq](https://balsamiq.com/wireframes/) to create wireframes for my project:

<a></a>

[Desktop wireframe](../assets/wireframes/desktop.png/)

<a></a>

[Tablet wireframe](../assets/wireframes/tablet.png/)

<a></a>

[Mobile wireframe](../assets/wireframes/mobile.png/)

[Back to Top](#table-of-contents)

---

<a name="roadmap"></a>

## **Roadmap**

<a></a>

### **Existing Features**

#### Navigation

<img src="../assets/readme/nav.png/" alt="screenshot of nav bar">

I used Bootstrap to create my navbar and then styled according to the design I wished to create and in keeping with my Coolors palette. The navbar is responsive with a collapsible menu, accessed via a burger icon.

I originally planned to make my nav bar transparent, but the nav links over the image were distracting and got a little lost. I decided instead to give the nav bar a solid colour.

I opted to fix the navbar to the top so users can easily navigate the site from whichever section they are in. This negates the need to put in 'back to top' links which could break user experience. 

#### Hero Image

<img src="../assets/readme/hero.png/" alt="screenshot of hero">

My hero image spreads across 100% width of the site. It was important to me to make my image a focal point of the website to convey a sense of the cinematic. I made a decision to put a link to the trailer via a button on the image rather than via the navbar. This is because when the user first lands on the page, the image is the first thing they see. Based on my user stories, the next likely step is for the user to want to know what the film is about and when it's out.

The image I chose was a deliberate choice. I wanted something that wasn't too busy and had a space where text could sit easily over it without getting lost or covering up any important visuals. The eyeline of the woman in the image helps to draw the users eye to the text, and therefore the button to the trailer, encouraging them to click that next. 

#### Trailer

<img src="../assets/readme/trailer.png/" alt="screenshot of trailer section">

As a film, I wanted the trailer to be the main selling point rather than text describing the film. I had originally planned to design the trailer to pop up as modal over the hero image. However, in practice this looked too busy and seemed a missed opportunity to make the rest of the site more dynamic. I opted to create a trailer section instead to give the website more visual impact and energy.

I didn't want to link to a random film trailer, so opted to create one myself using stock footage from the same series as the hero and gallery images. The trailer is deliberately set after the about section to give the user a peek at what else there is to explore on the site. I set the trailer to autoplay on mute and added user controls. I made sure the border radius did not impair the users ability to access the controls.

<img src="../assets/readme/trailer-controls.png/" alt="screenshot of trailer controls">

#### About

<img src="../assets/readme/about.png/" alt="screenshot of about section">

I was keen to keep the website as light as possible on text, so wrote a short synopsis for the fictional film. The second column was even lighter on text so I used a list element for each line and corresponding imdb icon to fill the space in an even manner.

The .two-column class I used for the about section was used again in the watch and news sections. I used the class in conjunction with an id to style accordingly in line with the content of the sections and positionining I wished to achieve. 

I later decided to use border-radius to round the corners of the containers to give it a more futuristic feel. 

The imdb icons were also a later addition. I included these in response to research around user stories. 

#### Watch

<img src="../assets/readme/watch.png/" alt="screenshot of watch section">

This section wasn't originally planned as part of my wireframes. I decided to create it having reviewed the structure of my website and planned content, and decided it was too minimalist. 

In my wireframes, the news section originally covered off that tickets were due to be announced. However, in this version of the website I opted to link through to Picturehouse as the exhibitor for a UK release of this fictional film. I also created a second column for watching on demand. This meant I was able to incorporate some animation elements with a zoom overlay over the logos, linking to SVOD platforms. 

#### News

<img src="../assets/readme/news.png/" alt="screenshot of news section">

The news section was originally planned and is represented in the wireframes, but like other sections of the website, was overhauled. With the additional trailer section and watch section, I had a new structure to work with. In terms of UI, I had more sections with more interactive elements and a nice balance in terms of the static images. I decided I wanted to mirror the .two-column structure in the final section as well, and include more social links.

#### Gallery

<img src="../assets/readme/gallery.png/" alt="screenshot of gallery section">

My gallery was originally planned to be different size images displayed closely together with no gap. However, this didn't fit with the overall design and artistic vision I had in mind for the website. I opted instead to style the images as a grid with small column gap. I applied a border radius to give a futuristic feel - sort of like you're looking through the windows of a space shuttle.

I created several media queries for the gallery to drop the number of columns from 4 to 1 on different viewports.

#### Footer

SCREENSHOT TO BE ADDED

My footer contains deliberately discreet financier logos (no links are purposeful) and links to terms of use, a privacy policy and industry regulators.

#### Scrollbar

<img src="../assets/readme/scroll-bar.png/" alt="screenshot of custom scroll bar">

I decided to style the scrollbar at a late stage in response to user feedback. I used -webkit- extensions to style it in order to cover as many different browsers in one go. I styled the scrollbar in line with my Coolors palette. 

<a></a>

### **Future Features**

User responses from testing have been very useful when thinking about future designs:

*"I signed up to the newsletter but got no confirmation to say it worked"*

In a future version, I would add custom error messages and confirmation that information has been submitted. 

*"Clicking on the photo didn't open it or give it the option to zooom in"*

In a future version, I would add an image modal to give functionality for images to be opened.

*"I was kind of expecting the Watch links would link to the film's page..."*

If this was a real film, once the film was released these images would link to the appropriate page on the streamer website. To manage this expectation, in a future version I would disable the links and edit the text to note that the film will be released on these platforms from December 2021.

Other features which could be added:

* Reviews section
* Blog page featuring content as part of the release plans. This would have a comments section for fans of the film and potential audiences to comment
* Mini-game page - an interactive viral campaign which allows the user to make choices for the character about what to do next. Based on challenges the protogonist faces in the film to enable a user to experience the world firsthand

[Back to Top](#table-of-contents)

---

<a name="technologies"></a>

## **Technologies**

### **Languages**
* [HTML](https://en.wikipedia.org/wiki/HTML)
* [CSS](https://en.wikipedia.org/wiki/CSS)
* [JavaScript](https://en.wikipedia.org/wiki/JavaScript)

### **Libraries & Frameworks
* [Font Awesome](https://fontawesome.com/)
* [Bootstrap](https://getbootstrap.com/)
* [Google Fonts](https://fonts.google.com/)
* [PNG Hut](https://pnghut.com/)

### **Tools**
* [Github](https://github.com/)
* [Gitpod](https://gitpod.io/workspaces)
* [Balsamiq](https://balsamiq.com/)
* [W3C HTML Validation Service](https://validator.w3.org/)
* [W3C CSS Validation Service](https://jigsaw.w3.org/css-validator/)
* [Tiny PNG](https://tinypng.com/)

[Back to Top](#table-of-contents)

---

<a name="testing"></a>

## **Testing**

<a></a>

### **Validator Testing**


<a></a>

### **Known Bugs**

[Back to Top](#table-of-contents)

---

<a name="deployment"></a>

## **Deployment**

[Back to Top](#table-of-contents)

---

<a name="credits"></a>

## **Credits**

<a></a>

### **Code**

* [Anouk Smet](https://github.com/AnoukSmet/Naturazy) for README inspiration!

<a></a>

### **Media**

* [Mikhail Nilov](https://www.pexels.com/collections/space-astronauts-mars-srn3hh1/)
* [Josué AS](https://unsplash.com/@yehoshuaas)
* [Nasa](https://unsplash.com/@nasa) 

<a></a>

### **Acknowledgements**

* [Simen Dahlin](https://github.com/Eventyret) for support in creating this website
* Code Institute Slack community
* Stack Overflow community
* My partner Chris for his endless patience as I wrote this instead of planned our wedding...

[Back to Top](#table-of-contents)

---
