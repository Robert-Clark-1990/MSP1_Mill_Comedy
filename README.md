# Milestone Project 1: Mill Comedy - Comedian Website

## [Mill Comedy](https://robert-clark-1990.github.io/MSP1_Mill_Comedy/)

![Website on display](assets/docs/website.jpg)

This is the website for the up and coming comedian/podcaster/screenwriter, Milly Armstrong Clark. 
It is designed to be responsible and accessible on a range of devices, making it easy for users to keep up to date with Milly's projects or upcoming events and communicate with her through the use of a contact form.

This project has been built using the five planes of UX design to develop a site that is focused in its needs and objectives, and provides a high quality experience for the user.


# User Experience (UX)

### Project Goals

The two main site objectives for this website are as follows: 

* To create an experience that gives the user a clear understanding of Milly’s creative stylings through the use of colour, images, and written content.

* To showcase a creative curriculum vitae of Milly’s work for potential clients or producers who may be interested in working with her.


### User Stories

#### First-time visitors

1. As a first-time visitor, I want to be able to easily understand the purpose of the site, and navigate through the sections with ease.

2. As a first-time visitor, I want to be able to find information pertaining to Milly Armstrong Clark's upcoming or ongoing projects.

3. As a first-time visitor, I want to be able to easily locate social media links, and be able to contact Milly through an inbuilt contact form.

#### Returning visitors

1. As a returning visitor, I want to be able to easily locate necessary information such as podcast or stand up video links.

2. As a returning visitor, I want to be able to easily access links to social media.

#### Potential Client

1. As a potential client, I want to be able to gain an understanding of Milly’s creative style through the content provided.

2. As a potential client, I want to have an easily accessible contact form to reach Milly.


### Design

#### Colour Scheme

A colour palette of pink, purple and white have been selected to match the predetermined palette used for the "Tea with the Morale Queen" podcast.


#### Typography

There are two main fonts that have been used for the website:

1. "Alatsi" is used for all headings and list items.

2. "Roboto" is used for all paragraph text.

Headers are displayed in uppercase to fall in line with the guidelines of the "Tea with the Morale Queen" brand.


#### Images
Striking images of comedian, Milly Armstrong Clark have been used throughout the site to uphold a state of continuity.
These images reflect the style of comedy used in her work, building consistency in both the site and her work as soon as the user interacts with the site.


#### Wireframes

In preparation for this project, a basic wireframe of each page and how it would be viewed in desktop, tablet and mobile has been created.
The wireframe for this project can be viewed [here](../doc/mc-wireframes.pdf).

![Website on display](assets/docs/wireframes.png)


#### Mock-ups

In preparation for this project, a basic mock-up of each page has been created to show the intended style of the website as a whole.
The mock-ups for this project can be viewed [here](../doc/mc-mockup.pdf).


# Features

### Existing Features

1. Home page - This page utilises a clean, professional look to welcome users to the site. A comedic element exists on the homepage, wherein the user can hover over the image of Milly which swaps it to an image of her pulling a face.

![Home Page](assets/docs/homepage-design.png)


2. About page - Allows users to read short background on Milly's life, both personally and professionally, with an image of her to accompany it.

![About Page](assets/docs/about-design.png)


3. Podcast page - Allows users access to a clean page detailing Milly's podcast, Tea with the Morale Queen, with an embedded element to listen to the most recent podcast, subscribe via a selection of icons, and a support button for those looking to support the podcast.

![Podcast Page](assets/docs/podcast-design.png)


4. Stand Up page - Following a brief description of her comedic style, users can watch sets from Milly's previous performances.

![Stand Up Page](assets/docs/standup-design.png)


5. News page - Allows users to view a page of news articles presented in date order, with images and necessary links provided.

![News Page](assets/docs/news-design.png)


6. Contact page - A clean contact form for users to get in touch with Milly.

![Contact Page](assets/docs/contact-design.png)


### Future features to implement

1. Wildlife Work - In order to expand on the full vision of Milly's work, a page dedicated to her wildlife work will be added at a future date.

2. Sign Up Form - Upon the creation of a mailing list, this will be implemented into the site, with a modal Call to Action on the homepage, a link in the footer, and inclusion on the Contact page.

3. Media - A media page will be added at a future date to include official images of Milly for professional use.


# Technologies used

### Languages Used

1. [HTML5](https://en.wikipedia.org/wiki/HTML5)

   This site uses HTML5 as it's main language.

2. [CSS3](https://en.wikipedia.org/wiki/CSS)

   This site uses CSS3 for it's styling.


### Frameworks, Libraries & Programs Used

1. [Bootstrap v4.5.3](https://getbootstrap.com/)
    
    Bootstrap was used to assist with the responsiveness and styling of the website.

2. [Google Fonts](https://fonts.google.com/)
    
    Google Fonts was used to import the "Alatsi" and "Roboto" fonts.

3. [Font Awesome](https://fontawesome.com/)
    
    Font Awesome was used on all pages to provide icons for aesthetic and UX purposes.

4. [Git](https://git-scm.com/)
    
    Git was used for version control, utilising the Gitpod terminal to commit to Git and Push to GitHub.

5. [GitHub](https://github.com/)
    
    GitHub was used to store the project.

6. [Adobe Photoshop](https://www.photoshop.com/en)
    
    Adobe Photoshop was used to create the background, and edit photos used throughout the website.

7. [Codepen.io](https://codepen.io)

    Codepen was used for reference of homepage hover functionality.

8. [tinypng.com](https://tinypng.com/)

    Tinypng was used to optimise jpg and png images to increase performance.


# Testing

## Bug fixes

### Site Containers

Throughout development, the website seemed unresponsive and clung to the margins of the browser despite efforts made to counter this. 

<section>
    <div class="row">
        <div class="col-md">

In a last ditch attempt to fix it, the entire homepage was rebuilt from scratch to see if the issue would persist, and low and behold, the issue was the lack of a container div, 
within which the row and col divs had free reign to hug the browser margins. This fix has made the site much more attractive to view.

<section>
    <div class="container">
        <div class="row">
            <div class="col-md">

### Home page heading on mobile

As the project began to come together and the site was tested on different screen sizes, the issue arose that the heading on the home page was too large for mobile screens.
To fix, the h1 attribute in the media query section was ruduced from 500% to 300% to ensure it fit on all screen sizes.


## Site performance

During the testing process, the website was subjected to a Lighthouse report to identify and fix common problems that affect the site's performance, accessibility and user experience.
The report brought back the following results.

![Performance Test One](assets/docs/lighthouse.png)

It was clear there was work to be done on improving the site's performance, especially with the hover image on the home page. 
Upon discussion with mentor Anthony Ngene, it was discussed using online image optimiser [tinypng.com](https://tinypng.com/) which reduced image sizes by 70-90%.
This reduced load times, bringing the performance up into the 90s.

![Performance Test Two](assets/docs/lighthouse2.png)


## W3 HTML Validator

### Home Page

* Validator returned with: **Heading cannot be a child of another heading.**

   To fix: closing tag added to h2 elements.

* Validator returned with: **Heading cannot be a child of another heading.**

   To fix: closing tag added to h2 elements.

* Validator returned with: **Empty heading.**

   To fix: closing tag added to h2 element "Comedian".

* Validator returned with: **Heading cannot be a child of another heading.**

   To fix: closing tag added to h2 elements.

* Validator returned with: **Heading cannot be a child of another heading.**

   To fix: closing tag added to h2 elements.

* Validator returned with: **Empty heading.**

   To fix: closing tag added to h2 element "Morale Queen".

* Validator returned with: **Heading cannot be a child of another heading.**

   To fix: closing tag added to h2 elements.

* Validator returned with: **End tag div seen, but there were open elements.**

   To fix: closing tag added to h2 elements above that had been left open by mistake.

* Validator returned with: **Unclosed element h2.**

   To fix: closing tag added to h2 elements.

* Validator returned with: **Empty heading.**

   To fix: closing tag added to h2 element "Professional Tea Drinker".

### About Page

* Validator confirmed **no errors or warnings to show**.

### Podcast Page

* Validator returned with: **Bad value 102x for attribute height on iframe element: Expected a digit but saw x instead.**

   To fix: x digit was removed.

* Validator returned with: **Bad value 350px for attribute width on iframe element: Expected a digit but saw p instead.**

   To fix: px digits were removed.

* Validator returned with: The **frameborder attribute on the **iframe element is obsolete.**

   To fix: frameborder was removed.

* Validator returned with: **The scrolling attribute on the iframe element is obsolete.**

   To fix: frameborder was removed.

* Validator returned with: **Bad value support for attribute type on element button.**

   To fix: Support value was changed to Submit, with relevant fixes made to the accompanying css.

* Validator returned with: **The element a must not appear as a descendant of the button element.**

   To fix: button was rewritten with thanks to code on [w3docs](https://www.w3docs.com/snippets/html/how-to-create-an-html-button-that-acts-like-a-link.html) that turned it into a form element.

### Stand up Page

* Validator returned with : **The frameborder attribute on the iframe element is obsolete.**

   To fix: frameborder was removed.

### News Page

* Validator confirmed **no errors or warnings to show**.

### Contact Page

* Validator confirmed **no errors or warnings to show**.


## W3C CSS Validator

* Validator returned with : **193: .swap-on-hover img | Value Error : top only 0 can be a unit. You must put a unit after your number : 10**

   To fix: changed to add a %

* Validator returned with : **216: .about-image | Value Error : right only 0 can be a unit. You must put a unit after your number : 5**

   To fix: changed to add a %

* Validator returned with : **229 .podcast-image | Value Error : right only 0 can be a unit. You must put a unit after your number : 5**

   To fix: changed to add a %

* Validator returned with : **397 | only 0 can be a unit. You must put a unit after your number**

   To fix: Unnecessary media query deleted.


# Deployment

This project was created using **Gitpod**, and pushed to **GitHub**. To deploy this page to GitHub from it's GitHub repository, the following steps were taken:

1. Visit [GitHub](https://github.com/) and log in.

2. From the repositories, select **Robert-Clark-1990/MSP1_Mill_Comedy**.

3. From the GitHub repository, click on **Settings**.

2. Scroll down to the section entitled **GitHub Pages**.

3. From the dropdown menu beneath **Source**, selected the **Master branch** and hit **save**.

4. This will create a link, visible just **below the GitHub Pages title**, which will take you to the deployed website.

### Running this project locally

To clone this project into Gitpod you will need:

1. A GitHub account.

2. Access to the Chrome browser.

Then follow these steps:

1. Install the Gitpod Browser Extensions for Chrome and restart your browser.

2. Log into Gitpod and navigate to the Project GitHub repository.

3. Click the green **"Gitpod"** button at the top of the repository.


# Credits

### Content

* All written content was created by the developer, Robert Clark with permission from [Milly Armstrong Clark](https://www.instagram.com/millcomedy/).


### Media

* All images were created by the developer, Robert Clark, with permission from [Milly Armstrong Clark](https://www.instagram.com/millcomedy/).

* All podcasts and videos provided used with permission from [Milly Armstrong Clark](https://www.youtube.com/channel/UCm8_k81-p_cEimTHmhDOB-w).

* Confidence for Breakfast artwork was created by the developer, Robert Clark, used with permission from [Melanie Judson](https://www.instagram.com/confidenceforbreakfast/).


### Code

* Hover Code for images on the Homepage was from [Creative Programmer](https://codepen.io/creativeprogrammer/pen/RpBpgm) on Codepen.

* Responsive Navbar was used as a guideline and heavily adapted from [Andor Nagy](https://codepen.io/andornagy/pen/RNeydj?editors=1100) on Codepen.

* Button that acts as an external link from [w3docs](https://www.w3docs.com/snippets/html/how-to-create-an-html-button-that-acts-like-a-link.html).


### Acknowledgements

* Thanks to [Milly Armstrong Clark](https://www.instagram.com/millcomedy/) for allowing this project to be based on her incredible work.

* Thanks to mentor Anthony Ngene for his advice and guidance throughout the project.

* Thanks to Slack User Healycian90 for their help recovering work not pushed to GitHub.

* Thanks to Slack User Ciaran Brady for their help locating the image swap hover code.

* Thanks to [Creative Programmer](https://codepen.io/creativeprogrammer/pen/RpBpgm) for their image swap on hover code that was used for the homepage of this project.

* Thanks to [Andor Nagy](https://codepen.io/andornagy/pen/RNeydj?editors=1100) for their responsive navbar that was used as a guideline and adapted for this project.

* Thanks to [w3docs](https://www.w3docs.com/snippets/html/how-to-create-an-html-button-that-acts-like-a-link.html) for their button that acts as an external link.