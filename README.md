# Lets Go Vegan

![Cute Pig](/assets/images/baby-pigs-unsplash.jpg)


# Table of Contents <a name="home"></a>
1. [Introduction to my Project](#introduction)
2. [UX](#ux)
    1. [Website Goals](#webgoal)
    2. [User Stories for How to go Vegan](#userstory)
    3. [My Wireframes](#wireframe)
3. [My Features](#features)
    1. [Phase 1 Features](#phase1)
    2. [Phase 2 Features Left to Implement](#phase2)
4. [Technologies](#technologies)    
5. [Testing](#testing)
    1. [Tests completed](#testcomp)
6. [Deployment](#deployment)
7. [Credits](#credits)
    1. [Content](#content)
    2. [Media](#media)
    3. [References](#refrences)
9. [Acknowledgements](#acknowledgements)

## Introductions to my Project <a name="introduction"></a>
My project is to help people transition to vegan, it is to encourage someone to take the first step in the journey to a more sustainable, compassionate healthy lifestyle.

If you are curious about what going Vegan means? Then my website will help with motivation and reasons why going vegan is the best choose you can make for 
the animals, the planet and your health.

If you need help in your transition, let me support you, just join my go vegan challenge. 

To see the live project [click here](https://nikkikobako.github.io/MS1-Go-Vegan/)

:house:[ Table of Contents](#home)

## UX <a name="ux"></a>
For full UX document please see [MS1 UX Design Document](https://github.com/nikkikobako/MS1-Go-Vegan/blob/master/assets/documentation/How%20to%20go%20Vegan.pdf)

### Website Goals <a name="webgoal"></a>

* An informative website to encourage people to transition to vegan
* Easy to use to help, not hinder a transition to a vegan life
* Ability to get in touch for more help


### User Stories for How to go Vegan <a name="userstory"></a>

* As a user I can see what being vegan means before I decide to convert
* As a user I can get help and support to transition to vegan so I am not doing it on my own
* As a user I want to investigate the reasons why someone becomes vegan
* As a user I am curious about what veganism is and what it involves
* As a user I want some inspiration of what I can cook 

### My Wireframes <a name="wireframe"></a>
I used Balsamiq Wireframes to create my Wireframes. They include 4 mobile pages, 
4 desktop pages and 1 for tablet as all other tablet views are the same as desktop.

[MS1 Vegan Wireframe](https://github.com/nikkikobako/MS1-Go-Vegan/tree/master/assets/wireframes)

#### Amendments to Wireframes
Since creating the wireframes, as part of testing I have amended to improve the user experience as follows

* For the large screen recipe page, I amended to have 2 recipes per row, as the page looked very empty
* For all sizes for the why go vegan page I have removed the scroll option for the text as not a good UX experience
* For the tablet screen why go vegan page I have amended to the same as mobile 1 column width as the screen looked to crowded
* For the XL screen on the why page I added collapsible buttons as the text was different sizes and the buttons give a uniform view
* For the Why page the Let' Go Vegan Link was displaying, but this is the destination of the link so made a decision to remove only on the why page 
    and allow the So Why Go Vegan Header to display instead

:house:[ Table of Contents](#home)

## My Features <a name="features"></a>
The project consists of four pages, displaying the home page on initial load.

* Home page can be accessed via the logo in the header or via the navigation menu from any page
* Why go vegan can be accessed via the text "Let's Go Vegan! for mobile view and "Let's Go Vegan Together" on tablet and large screen 
as well as the navigation menu from any page
* The Recipe page can be access via the navigation menu from any page
* The Challenge page can be accessed via the footer email icon on tablets and larger screens and via the navigation menu from any page

### Phase 1 Features <a name="phase1"></a>
1. Home page gives a minimalist view with a small text area to catch the users attention
2. The Why page has a lot of text which on mobile and tablet view is split into sections by the pictures this gives the user the reasons to become vegan
3. The Why page for desktop is 3 sections and to give a consistent view has a button to collapse the main text to allow a clearer look
4. The user can learn how to become vegan from the Why pages, the links on the page give a wealth of information
4. The user can explore food choices on the recipe page to give ideas and inspiration of how tasty vegan food is
5. The user can get help to transition by joining the challenge by signing up on the Challenge page

### Phase 2 Features Left to Implement <a name="phase2"></a>
1. Form on the Challenge page to have code behind it to actually store the data
2. New page on exactly how to transition to vegan
3. Add additional useful applications and links, may have a separate page 
4. Page for sanctuaries can visit in the North West of England and then in the rest of the UK 
5. Page for a photo gallery of everything vegan

:house:[ Table of Contents](#home)

## Technologies Used <a name="technologies"></a>
The project used a number of technologies to build the website

* HTML5 - Used to design the basic view of my website, including the text on why to go vegan
* CSS - Used to style the content into a user friendly version
* [GitPod](https://www.gitpod.io/) - Used to write my HTML and CSS and to store my images, recipes, documentation and wireframes
* [GitHub](https://github.com/) - Used to version control my website, store the committed code and deploy my website to live
* [Bootstrap framwork including JQuery](https://getbootstrap.com/) - Used to provide mobile first approach and to style content for different media devices
* [FontAwesome](https://fontawesome.com/) - Used for all my footer icons which included my challenge link and social media icons for YouTube, Twitter and Facebook
* [Canva](https://www.canva.com/) - Used to create my logo and favicon
* [TinyPNG](https://tinypng.com/) - Used to compress my pictures to ensure does not cause issues loading on different devices
* [Google Font ](https://fonts.google.com/) - Used for all of the text fonts throughout my webpages
* [W3C CSS Validation Service](https://jigsaw.w3.org/css-validator/) - Used for testing my HTML and CSS to ensure no errors
* [Adobe Acrobat Reader](https://get.adobe.com/uk/reader/)
* [Google Docs](https://docs.google.com/document/u/0/)

:house:[ Table of Contents](#home)

## Testing <a name="testing"></a>
Testing has been completed using the following

1. Initial testing was via GitPod and the developer tool inspect to show my pages as mobile, tablet and full screen
2. The code was then published via git hub and tested on the following devices
    1. Samsung S8 mobile phone
    2. Samsung Galaxy S2 tablet
    3. Oukitel C15 Pro mobile phone
    4. iMac desktop
    5. Microsoft surface Pro
    6. Browser Chrome
    7. Browser Firefox 
3. The code was shared on [Slack](https://slack.com/intl/en-gb/) for testing by the CodeInstitute community
4. HTML was ran through [W3C Validation Service](https://validator.w3.org/) to ensure no errors
5. CSS was ran through [W3C CSS Validation Service](https://jigsaw.w3.org/css-validator/) to ensure no errors


### Tests completed <a name="testcomp"></a>

1. Loaded each page code individually to the W3C validators to ensure no errors :heavy_check_mark:
    1. index.html
        1. Error from validator as used px with height in html, which is not required, removed px for all pages
        2. Warnings for the comment not liking the extra --- so removed for all pages
    2. whyvegan.html
        1. Error for the health text as used UL and needed to set the paragraphs around the text not the UL
    3. food.html 
    4. Challenge.html 
        1. Error issue with label input for the form, added id
        2. Warning for date not supported on old browser, left warning as recommendation is Pollyfill which requires coding
        3. I have 1 error I cannot fix as the drop down works in this format error is line 147 - The form attribute must refer to a form element
    5. style.css
        1. Warnings for border and colour being the same but this is by design
        2. Warning for -webkit-background-size type code which is for older websites
2. Checked all links on the website pages to ensure work on mobile, tablet and desktop :heavy_check_mark:
    1. Noticed the Let's Go Vegan Link was also on the why page, as this is the destination of the link so made a decision to remove only on the why page  
    and allow the So Why Go Vegan Header to display instead
3. Check devtools for errors :heavy_check_mark:
    1. Warning showed no favicon on live site, fixed bug causing this
4. Checked form to ensure warnings given if fields left empty :heavy_check_mark:
5. Checked form email to ensure would not accept an invalid type email :heavy_check_mark:
6. Test the collapse function and button only appears on large screens, not mobile or tablet :heavy_check_mark:
7. Read all text to ensure makes sense and no spelling mistakes
8. Test to ensure all media sizes work and changes as per the UX design

:house:[ Table of Contents](#home)

## Deployment <a name="deployment"></a>

### Project Creation
Go Vegan project was created via GitHub using the CodeInstitue template to then open in GitPod. All coding was done in GitPod and pushed back to GitHub 
for storage and version control using the "git add." followed by "git commit -m" and finally the "git push" command. On this occasion I did not use any 
branching, I only used the master for version control.

### Project Deployment to Live
Once I reached the stage of wanting to test on mobile and tablet I then published my website to live using GitHub via the following steps

1. Open my GitHub project [MS1 Go Vegan](https://github.com/nikkikobako/MS1-Go-Vegan)
2. Go to Settings
3. Scroll down until reach the section GitHub Pages
4. Change the branch option from none to master and saved
5. This then gave me a live website [Go Vegan](https://nikkikobako.github.io/MS1-Go-Vegan/)

:house:[ Table of Contents](#home)

## Credits <a name="credits"></a>

### Content <a name="content"></a>
The entire site is fictional and created by myself

### Media <a name="media"></a>
The photos used in this site were obtained from [pixabay](https://pixabay.com/?rf=jimdo), [Unsplash](https://unsplash.com/),
[Pexels](https://www.pexels.com/)] and google search images.
Each photo has the origin in the title to show where it was obtained from.

My logo was created using [Canva](https://www.canva.com/), I also used my logo for the favicon

:house:[ Table of Contents](#home)

### Refrences <a name="refrences"></a>
I have used a number of references to useful people, sites and tools that can help someone go vegan. These sites are free and readily available
for anyone to use.

* [Earthling Ed](https://www.youtube.com/channel/UCVRrGAcUc7cblUzOhI1KfFg)
* [Mick the Vegan](https://www.youtube.com/channel/UCGJq0eQZoFSwgcqgxIE9MHw)
* [Vegan Calculator](https://thevegancalculator.com/)
* [Dr Michael Greger](https://nutritionfacts.org/)
* [Dr Neal Barnard](https://www.pcrm.org/yourbodyinbalance)

## Acknowledgements <a name="acknowledgements"></a>

* I received inspiration for this project from Veganuary which is how I became vegan - [Veganuary](https://uk.veganuary.com/)
* For my layout I was inspired for the home page from a google search of images
* I have used google search to solve a number of issues, this included sites [W3Schools](https://www.w3schools.com/) and [Stack Overflow](https://stackoverflow.com/) 
* I used the slack community for support and help when I encountered some of my puzzling issues
* My mentor Akshat Garg helped with industry standard tools and a few suggestions for UX readability

:house:[ Table of Contents](#home)
