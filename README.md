# **Cormac Lawlor Operatic Baritone**

User-Centric Frontend Developent Project - Code Institute June 2019

This is my professional website to be presented to prospective employees in the operatic world. The Website highlights some of my career achievements to date including awards and prizes that I have received. It also includes some performance photographs along with some recordings to listen to.

## Demo

A live demo can be viewed [here](https://armedcor.github.io/frontend-round2/)

## UX

My primary goal when I designed this website was to provide potential employers in the Arts world with a very brief and concise overview of my achievements to date within the operatic world.  I went with a single page scrolling website to allow users to access all information as easily as possible while reducing the need to move through separate pages. I also have the option for the user to download my CV from the Navigation Bar should they want a traditional CV.

I attempted to create a more minimalist design to give the website a very modern feel while removing any unnecessary content and button clicking. At the bottom of the page, I provided links to my Linkedin and Facebook page and also a downloadable PDF version of my CV for employers.

## Technologies

1. HTML
2. CSS
3. Bootstrap (4.3)
4 JQuery

## Features

The site has smooth scrolling implemented to allow a smooth transition to each nav link. The collapsed mobile nav bar also features a piece of JQuery script to allow it auto close once a user has clicked on a link improving the UX.

## Features to Implement

Link Contact form to an email server - Requires JavaScript
Implement an extended Lightbox Photo Gallery - Requires JavaScript

## Testing

My user story achieved the intended outcome. The "About me" section details some of my career highlights to date while my "Media" and "Gallery" section showcase both myself and my work. Both the "About me" and "Quotes" sections contain some mobile responsive design to make for a cleaner more streamlined view. The headshot and one quote disappear.

If you try submitting the contact form without a Name, Email address or message you will receive an error stating these fields are required. I left the Telephone number field as optional as I appreciate some user are not comfortable leaving a personal number. If all fields are valid the page will reload.

The CV in the footer downloads to the users default download folder on click, this was done using the "download" attribute. All other links in the footer open a new browser tab. 

A smooth scrolling effect was implemented with a CSS rule to allow the page to scroll to specific anchor points instead of giving a sudden jump motion.

The site was tested using a number of different browsers, operating systems and across multiple mobile devices to ensure complete responsiveness and compatibility.
While testing I found that the gallery Modal was not responsive and stuck at one size across all platforms. This was corrected using multiple media Queries.
I also found that background images that had the attribute  `background-attachment: fixed` were zoomed-in and highly pixilated. This was corrected by adding the attribute `background-attachment: scroll` instead.


## Deployment

This site is hosted using GitHub pages, deployed directly from the master branch. The deployed site will update automatically upon new commits to the master branch. In order for the site to deploy correctly on GitHub pages, the landing page must be named index.html.

To run locally, you can clone this repository directly into the editor of your choice by pasting git clone https://github.com/armedcor/frontend-round2 into your terminal. To cut ties with this GitHub repository, type git remote rm origin into the terminal.

## Credits

### Content

All content in the "About" section of this site was written by Cormac Lawlor.

### Media

All photos on the site are the property of Cormac Lawlor. A darken filter was applied to the background images before uploading them onto the project to allow text to stand out more.

### Awknowledgements

The footer code was taken from the Example project before been modified by myself to suit my page [here](https://github.com/Code-Institute-Solutions/StudentExampleProjectGradeFive)

The script used to allow the navigation button to auto-collapse on mobile was taken from [here](https://stackoverflow.com/questions/42401606/how-to-hide-collapsible-bootstrap-4-navbar-on-click)

Thanks to all the users on the Code-Institute slack channel who helped me troubleshoot.