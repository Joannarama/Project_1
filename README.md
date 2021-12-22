

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
The target audience are individuals who want to have software built usually to support their current business processes. They may visit the site via links on a search engine results page, through advertising, social media or from a back link on some online press coverage. They may be at the early idea stage or have more particular requirements already thought out, the website will assure the user that whatever point they're at in their journey, we're here to support them. 

### User Requrements and Expectations

A clear, informative and easy to navigate interface
- Links and functionality that work as they would expect
- An easy-to-find means of contacting the company
- Accessibility



## Design
The current Devhaus website was built a number of years ago and the company has evolved from this point to the stage where the website is not in line with the current ethos and offerings of the company. 

Working with a Co. Wexford based designer in 2021, a new design was conceived to bring the site up to date and convey a sense of modernity and professionalisim in line with the company's current capabitities. 

### Design Choices

The website design is a justaposition of strong accent colours with bold graphics based on the Devhaus branding and the use of white space which gives structure and clarity ensuring the content is easy to navigate, read and access. 
   
The calls to action stand out and attract the eye, encouraging the user to make a particular user journey to the contact us page. 

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