# The purpose of this project



This static website was made to provide information on Nikola Tesla as well as his personal life and inventions to interested third-party individuals. The language and layout of the site are aimed to be friendly and inviting regardless of the educational background of the interested individual or individuals.

The site contains a total of five sections including a contact section.

The target audience is individuals interested in Nikola Tesla - regardless of their geographic location and the website was made in English so that it would accommodate a larger audience.

This website is the first of five projects that needs to be completed in order to receive a diploma in Software Development from The Code Institute.

Requirements for the project are that the website has to be static and responsive using HTML5 and CSS3.

A live version of the project can be found here -

https://petragabud.github.io/NTCI/

# Table of Content

 - UX
-   User Demographic
  -   User Stories
  -   Existing Members
   -   New Users
 -   User Goals
 -   Requirements
  -   Design
 -   Colors
  -   Typography
  -   Images
-   Features
  -   Existing Features
  -   Header and Navigation Section
 -   About us Section
 -   Contact Section
 -   Footer Section
 -   Features Left to Implement
 -   Technologies used
 -   Testing
 -   Validator Testing
 -  Unfixed bugs
 -   Development and Deployment
 -   Content
 -   Media
 -   Credits

## UX

### User Demographic

This website is meant for:

-   Students of various ages (10-25+) interested in general facts about the subject (the website stands as an intro into Teslas life and career)
    
-   Professors or Teachers (in subjects of Science or History) who wish to present their students with a real-life example of a man who changed the world with his willpower and brilliant ideas
    
-   Tourists who are visiting the beautiful Republic of Croatia and want to know more about historical figures from that area
    

### User Stories

#### Existing Users

-   As a Member: I want to be able to see facts about Nikolas's life and work.
    
-   As a Member: I want to be able to use his quotes for my essays and papers or future school projects.
    
-   As a Member: I want to be able to contact the WebMaster.
    

#### New Users

-   As a new User: I want to learn more about the subject.
    
-   As a new User: I want to contribute with new content by messaging the info email and submitting my ideas on improving the site.
    

### User Goals

-   Find information regarding the subject (Nikola Tesla)
    
-   Contact local society with my ideas
    

### Requirements

A static responsive website that incorporates the technologies I have learned so far that contains some advanced functionality. The development process needs to be well documented through a version controls system such as GitHub.

Required technologies: HTML, CSS

### Design

This is my first project so I made multiple versions of it for esthetic and functionality testings - this submission is a culmination of all of those versions. There are parts of the projects which were influenced by various sources - they will be credited properly in this ReadME as well as the comments in the code.

This site was made as a single-page website that has been divided into multiple sections. I wanted the website to look like it has a flow and isn't difficult to use.

I chose to put a background picture as the only picture because I didn't want to slow down the loading times or mess up the functionality of the site.

The site has been divided into the following sections:

-   Home
    
-   Biography
    
-   Fun Facts
    
-   Famous Quotes
    
-   Contact

- Thank You Page
    

Also, the navigation on top has been programmed as static so that the users could quickly go to the subject they are interested in without scrolling.

#### Typography

The [Google Font Montserrat](https://fonts.google.com/specimen/Montserrat?query=mont) was chosen as the main font with a fallback of Sans-Serif. Font weight of 300 has been used on the website.

#### Image

Image has been chosen in accordance with color and content. The purpose of the website is to give a friendly look and express quality. The image has been sized in order for the page to be load up quicker.

## Features

The History on Nikola Tesla website is a single-page website that consists of these sections:

-   Header
    
-   Navigation Menu
    
-   Home
    
-   Biography
    
-   Fun Facts
    
-   Famous Quotes
    
-   Contact Form and Email
    
-   Footer (with Social Media links and Copyright information)

- Thank You Page (after submission of the contact form)
    

In order to make navigation easier between the sections, the navigation bar is fixed on top when the user scrolls thru the page.

### Existing Features

#### Header and Navigation Section

-   The Header is text based and aligned to the Center of the page
    
-   The Navigation Menu is right under the Header and is aligned to the Center of the page
    
-   The Navigation Menus position is fixed and therefore it follows the user as the user scrolls down the page.
    
-   Menu items are anchored to sections on the website.
    

#### Home Section

-   The home section consists of a title and a paragraph nested inside of a brown border-box.
    

#### Home Section

-   The home section is a brief intro to some of the accomplishments of the subject.
    

#### Biography Section

-   This section contains a Title and four paragraphs with facts about the individual's life and inventions.
    

#### Contact and Registration Section

-   The section contains a registration form and contact details for the Website admin.
    
-   It can be used for getting more information, giving an input or simply saying hello.
    

#### Footer Section

 -   The Footer contains four social media links (Facebook, Twitter, YouTube, and Instagram) The code for the Footer is borrowed from the Love Running - Project.
    
 -   The purpose of the Footer is to provide easy access for the User to the different social media platforms where the History has a presence.
    
   #### Thank You Page
 - The purpose of the Thank you page is to make sure that the users are aware that their message has been sent and that they will get their responces.

### Features Left to Implement

-   A subscription area so that users can become members and receive updates on content.
    

### Technologies used

-   [HTML](https://en.wikipedia.org/wiki/HTML)
    
-   [CSS](https://en.wikipedia.org/wiki/CSS)
    

## Testing

Test of functionality and appearance of the website has been dealt with throughout all stages of the development phase.

The test has been conducted using Google Chrome, Mozilla Firefox, and Safari. Testing different devices and screen resolutions have been conducted using Google DevTools.

Listed are the main issues discovered. (I did not document the details of the mistakes I did during the development of the website but will use the final fixing stage as an example):

-   On smaller screens, the border boxes became fixed and did not adjust to the size of the screen and content as needed
    
I changed the values from Pixels into em and percentages

-   The Navigation and Social Media icons become (start overlapping) distorted on smaller screens
    
    Added Margins and Padding to solve the problem

Apart from these issues, there have been several minor issues. The majority of these have been due to not putting the spaces, dashes, or other signs where necerassy.

In testing with the W3School Validator 0 issues popped up.

### Validator Testing

-   HTML - 0 Errors and Warnings found by W3Schools validator

-   CSS
    
-   No errors were returned when passing through the official (Jigsaw validator)
    
-   Lighthouse testing
    
Performance: 99

Accessibility: 100

Best Practices: 92

SEO: 97

### Unfixed bugs

I curently fixed all the bugs that the site had.

## Development and Deployment

The development environment used for this project was GitPod in combination with JS Fiddle. To track the development stage and handle version control regular commits and pushes to GitHub has been conducted. The GitPod environment was created using a template provided by Code Institute.

The live version of the project is deployed on GitHub pages.

The procedure for deployment followed the "Creating your site" steps provided in [GitHub Docs.](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site)

1.  Log into GitHub.
    
2.  Locate the GitHub Repository that shall be deployed live.
    
3.  At the top of the repository, select Settings from the menu items.
    
4.  Scroll down the Settings page to the ”GitHub Pages" section and click on the ”Check it out here!”
    
5.  At the ”Source” section choose ”main” as Branch and root as folder and click ”Save”
    
6.  The website will deploy and the pages refreshes to provide the live link to the project.
    

The live link can be found here - [https://petragabud.github.io/NTCI/](https://petragabud.github.io/NTCI/)

## Content Credits

The background image is from Wikipedia.

Parts of The Code used are from talkerscode.com and w3schools.com

Facts (content) are from [https://www.britannica.com/biography/Nikola-Tesla](https://www.britannica.com/biography/Nikola-Tesla)

Facts and quotes are from [https://mocomi.com/nikola-tesla-biography/](https://mocomi.com/nikola-tesla-biography/)

## Media

-   The image came from Wikipedia and I hosted it on Imgur after I resized it Cloud Convert
    

## Mentor Credits

Martina Terlević

P.S. thanks to Pelikantapenten whom I've never met but used as a template for a ReadMe file.

### Sources used for Inspiration and Functionality:

W3 schools

Talkers Code

Love Running Project - Code Institute



