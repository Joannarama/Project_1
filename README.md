

1. [Project Goals](#project-goals)
    1. [User Goals](#user-goals)
    2. [Site Owner Goals](#site-owner-goals)
2. [User Experience](#user-experience)
    1. [Target Audience](#target-audience)
    2. [User Requrements and Expectations](#user-requrements-and-expectations)
    3. [User Stories](#user-stories)
3. [Design](#Design)
    1. [Design Choices](#design-choices)
    2. [Colour Scheme](#colour-scheme)
    3. [Fonts](#fonts)
    4. [Images and Video](#images-and-video)
    5. [Structure](#structure)
    6. [Wireframes](#wireframes)
4. [Technologies Used](#technologies-used)
    1. [Languages](#languages)
    2. [Frameworks & Tools](#frameworks--tools)
5. [Features](#features)
    1. [Logo and Navigation Bar](#logo-and-navigation-bar)
    2. [Footer](#footer)
    3. [Homepage](#homepage)
    4. [About Us](#about-us)
    5. [Our Animals](#our-animals)
    6. [Fundraising](#fundraising)
    7. [Contact Form](#contact-form)
    8. [Map and address](#map-and-address)
6. [Development](#development)
    1. [Building and Maintaining](#building-and-maintaining)
    2. [Commits](#commits)
    3. [Deployment](#deployment)
    4. [Cloning](#cloning)
7. [Testing](#testing)
    1. [HTML Validation](#html-validation)
    2. [CSS Validation](#css-validation)
    3. [Accessibility](#accessibility)
    4. [Performance](#performance)
    5. [Responsiveness](#responsiveness)
    6. [Browser compatibility](#browser-compatability)
    7. [Testing user stories](#testing-user-stories)
8. [Bugs](#Bugs)
9. [Credits](#credits)
10. [Acknowledgements](#acknowledgements)

## Project Goals

### User Goals
The aim of this webiste is to provide the user with information about the software development company, Devhaus, that is clear and easy to access. The user will learn about the company's location, capabilities and service offering. They will be able to review projects that have been developed by Devhaus by clicking on the relevant links on the home page. 

The user will easily be able to contact Devhaus via the Contact Us form.

### Site Owner Goals
The goal of the site for the owner is to have a professional, clean and informative website that will impress visitors to the site at first glance, will provide them with easy to understand and accessible information on the company's achievements and software services. Overall, the website will act as a shop window, laying out the company's wares. 

The website is clear and easy to read and the flow of information is logical. Calls to action are placed in the header, main body and footer of the site to assist the user with straightforward navigation. The overall design and content of the site will build confidence in the user and they will gain a comprehensive understanding of the company's business. 

## User Experience

### Target Audience
- People looking to adopt an animal.
- People looking to attend a fundraising event

### User Requrements and Expectations

- A simple and intuitive navigation system
- Quickly and easily find relevant information
- Links and functions that work as expected
- Good presentation and a visually appealing design regardless of screen size
- An easy way to contact the animal shelter
- Simple content that the user can skim read
- Accessibility

### User Stories

#### First-time User 
1. As a first time user, I want to know where the animal shelter is located
2. As a first time user, I want to know the animals available for adoption
3. As a first time user, I want to know more about the animal shelter
4. As a first time user, I want to know about any fundraising activities
5. As a first time user, I want to be able to contact the animal shelter

#### Returning User
6. As a returning user, I want to know which animals are available for adoption
7. As a returning user, I want to know about any fundraising activities
8. As a returning user, I want to be able to contact the animal shelter

#### Site Owner 
9. As the site owner, I want users to find information about upcoming fundraising activities.
10. As the site owner, I want users to find information about available animals ready for adoption.
11. As the site owner, I want users to get to know the animal shelter. 
12. As the site owner, I want the users to be able to contact us.
13. As the site owner, I want users to be able to see where we are located.

## Design

### Design Choices

The webpage was designed with the feeling a customer might get while dining at the restaurant. It is calm, warm and inviting. Some of the imagery on the page has a round shape with a border to resemble food served on a plate.
   
### Colour Scheme
- Create a modern colour scheme with soft tones
- Primary background of the website will be white, so this would need to form part of the palette.
- The goal is to choose gender-neutral colours.
- Final palette colours that were chosen were #F4F9F4 #C4E3CB #8AAE92 #616161
- Source: https://colorhunt.co/palette/f4f9f4c4e3cb8aae92616161
- Following accessibility testing, a fifth color was added which was a darker version of #616161. The new color is #1A1A1A.

### Fonts
- Create a modern look with soft lines
- Final font chosen was Montserrat Alternates by Google Fonts
- Source: https://fonts.google.com/specimen/Montserrat+Alternates?query=Montserrat+Alternates


## index.html
**Error:** Statement h3 not allowed as child of element span in this context. (Suppressing further errors from this subtree.)
**Solution:** Change span to div.

**Error:** An img element must have an alt attribute, except under certain conditions. For details, consult guidance on providing text alternatives for images.
**Solution:** alt attribute added to the image to resolve this error. 

Error: Attribute alt not allowed on element a at this point.
Solution: I removed the alt attribute which caused the error.

Error: No p element in scope but a p end tag seen.
Solution: I had placed a h tag withing the p tag. This caused the error and removing the p tag resolved the issue. 

## services.html
Error: An img element must have an alt attribute, except under certain conditions.
Solution: alt attribute added to the image to resolve this error.

Error: No p element in scope but a p end tag seen.
Solution: I had placed a h tag withing the p tag. This caused the error and removing the p tag resolved the issue. 

## contact.html
No errors

## CSS
1 Error found:
File not found: https://fonts.googleapis.com/css2?family=Quicksand:wght@300;400,600&display=swap: Bad Request
I am using the suggest @import approach and this is breaking the validation. I do not know how to fix.