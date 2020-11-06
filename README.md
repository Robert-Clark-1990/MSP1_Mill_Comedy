# Milestone Project 1: Mill Comedy - Comedian Website

## [Mill Comedy](https://robert-clark-1990.github.io/MSP1_Mill_Comedy/)

![Website on display](assets/docs/website.jpg)

This is the website for the up and coming comedian/podcaster/screenwriter, Milly Armstrong Clark. 
It is designed to be responsible and accessible on a range of devices, making it easy for users to keep up to date with Milly's projects or upcoming events and communicate with her through the use of a contact form.

This project has been built using the five planes of UX design to develop a site that is focused in its needs and objectives, and provides a high quality experience for the user.


# Strategy

The two main site objectives for this website are as follows: 

* To create an experience that gives the user a clear understanding of Milly’s creative stylings through the use of colour, images, and written content.

* To showcase a creative curriculum vitae of Milly’s work for potential clients or producers who may be interested in working with her.

The user needs are outlined below in the User Stories.


# User Experience (UX)

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


#### Images
Striking images of comedian, Milly Armstrong Clark have been used throughout the site to uphold a state of continuity.
These images reflect the style of comedy used in her work, building consistensy in both the site and her work as soon as the user interacts with the site.


#### Wireframes

In preparation for this project, a basic wireframe of each page and how it would be viewed in desktop, tablet and mobile has been created.
The wireframe for this project can be viewed [here](assets/doc/mc-wireframes.pdf).


#### Mock-ups

In preparation for this project, a basic moc-up of each page has been created to show the intended style of the website as a whole.
The mock-ups for this project can be viewed [here](assets/doc/mc-mockup.pdf).


# Features

  ----------  INSERT FEATURES HERE ----------


# Technologies used

### Languages Used

1. HTML5

2. CSS3


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

8. [Online Convert](https://image.online-convert.com/convert-to-webp)

    Online Convert was used to turn images into webp format.


# Testing

## Site performance

During the testing process, the website was subjected to a Lighthouse report to identify and fix common problems that affect the site's performance, accessibility and user experience.
The report brought back the following results.

![Performance Test One](assets/docs/lighthouse.png)

It was clear there was work to be done on improving the site's performance, especially with the hover image on the home page. 
Upon review, it was discovered a fix would be to convert images from jpeg or png to webp, so this was done using an [online converter](https://image.online-convert.com/convert-to-webp).
This reduced load times, bringing the performance up into the 90s.

![Performance Test Two](assets/docs/lighthouse2.png)

## Site Containers

Throughout development, the website seemed unresponsive and clung to the margins of the browser despite efforts made to counter this. 
In a last ditch attempt to fix it, the entire homepage was rebuilt from scratch to see if the issue would persist, and low and behold, the issue was the lack of a container div, 
within which the row and col divs had free reign to hug the browser margins. This fix has made the site much more attractive to view.


# Deployment

Deployment for this project was a straightforward process:

1. From the GitHub repository, click on settings.

2. Scroll down to the section entitled GitHub Pages.

3. From the dropdown menu beneath Source, selected the Master branch and hit save.

4. This will create a link, visible just below the GitHub Pages title in a green box.


# Credits

### Content

* All written content was created by the developer, Robert Clark with permission from Milly Armstrong Clark.


### Media

* All images were created by the developer, Robert Clark, with permission from Milly Armstrong Clark.

* All podcasts and videos provided used with permission from Milly Armstrong Clark.


### Acknowledgements

* Thanks to [Milly Armstrong Clark](https://www.instagram.com/millcomedy/) for allowing this project to be based on her incredible work.

* Thanks to Slack User Healycian90 for their help recovering work not pushed to GitHub.

* Thanks to Slack User Ciaran Brady for their help locating the image swap hover code.

* Thanks to [Creative Programmer](https://codepen.io/creativeprogrammer/pen/RpBpgm) for their image swap on hover code that was used for the homepage of this project.

* Thanks to [Andor Nagy](https://codepen.io/andornagy/pen/RNeydj?editors=1100) for their responsive navbar that was used as a guideline and adapted for this project.

