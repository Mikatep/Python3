<h1 text-align="center">Mediterranean Flavours</h1>

Mediterranean Flavours it's a blog style application created for the community to share ideas and recipes from Mediterranean countires

![Alt text](/static/images/mockup.png)

## Author

Miriam Cordoba Capote (Github handle: Mikatep)

## User Experience (UX)

-   ### User stories

    -   #### First Time Visitor Goals

        1. As a First Time Visitor, I want to easily understand the main purpose of the site and learn more about the web application.
        2. As a First Time Visitor, I want to be able to easily navigate throughout the site to find content.
        3. As a First Time Visitor, I want to be able to find valuable information. And I also would want to locate their social media links to get a faster stream of information.

    -   #### Returning Visitor Goals

        1. As a Returning Visitor, I want to be able to check if the web applicaction is adding new features.
        2. As a Returning Visitor, I want to be able to find new recipes and an increasing community.

    -   #### Frequent User Goals
        1. As a Frequent User, I want to check if the web application keeps updating the site to keep up with the latest financial news.
        2. As a Frequent User, I want to check to see if there organizations is increasing the information available in the website, and may moving forwards providing a more premium service.
        3. I'd like to see the community growing, and the application evolving towards a better conexion between user.


-   ### Design
    -   #### Colour Scheme
        -   The three main colours used are:
         Dark #020202 used mainly for text within the body element and as changing color over hover effects for some of the links.

         #fff and antiqute white, for hover effects and some text and brand-name.

         Bright green #558b2f used for text and hr and card-headers.

         Bright red #d50000 used for social links hover, and buttons.

    -   #### Typography
        -   The Roboto font is the main font used throughout the whole website with Sans Serif as the fallback font in case for any reason the font isn't being imported into the site correctly.
        - The Pacifico font is used for Nav-Bar components titles and some of the links. 
        - Fonts were imported from Google Fonts.

    -   #### Imagery
        -    The large, background image selected for the nav-bar represents tipycal mediterranean vegetables and products.

   ## Features

   ### Existing Features

- __Navigation Bar__

  - Featured on all the pages, for the unregistered and unlogged user the full responsive navigation bar includes links to the Logo-name, Home page, Register, Log in and contact. The navigation bar is placed in each of the pages and is identical in each page to allow for easy navigation.
  - For the registered and logged user the nav-bar also shows home, profile, log out, and contact pages.
  - This section will allow the user to easily navigate from page to page across all devices without having to revert back to the previous page via the ‘back’ button. 

__Main Sections__

- Main section holds an accordion in the main page that shows the recipes from the database. And holds the user main Profile in the profile page, and forms in Registration, Log In, and Contact Us page.

__Footer__

-  Featured on all the pages, the full responsive footer includes a brief description of the organization, social links and the name of the creator of the web application (myself). The footer is placed in each one of the pages and is identical in each page to allow for easy navigation.


__Form Contact Us__

-  Form to contact the organization fully functional. The organization gets one email with the user data, and the user get one email to confirmed the email has been sent.

## Technologies

- Bootstrap 4.3
- Javascript (contact form)
- Flask + Python
- HTML
- CSS
- FontAwesome
- GoogleFonts
- MongoDB*

*See below further information about the database used for this project.

### Important Information regarding the choice of non-relational-database

- In this case, I have modeled my relational database on a non-relational database system., MongoDB. I have used the Mongodb best practice and guidance used when migrating relational database platforms to non-relational database platforms as my guide in this case.  I have used the following mapping:

![Alt text](/static/images/Relational.png)

- The second main reason for the election of a Non-relational Database vs a relational database is that I didn't have access to neither of the new guidance for Milestone project 3 due to technical problems with Code Institute, till few days prior the submission of this project, being the desing of the project on a very advance state at that precise moment.


## Testing 

-  The Website was tested on Google Chrome, Microsoft Edge and Firefox
-  The website was viewed on a variety of devices such as Laptop, Samsung Tablet, and several android phones
-  A big amount of testing has been done using google chrome inspect tool to ensure the responsive design was working properly.
-  Friends and family were asked to check the website and give feedback throughout the different steps of the process.

### Validator Testing 

-  Html
No errors were returned in any of the pages when passing through the official W3C validator.

A warning was returned reccomending to always add a header to every section however it has been ignored for designed purposes and to stay close to the original wireframe.

-  CSS

No errors were returned whe passing through the official Jigsaw validator.

- PEP8 Online

- JSHint for Javascript.

### Unfixed Bugs

There's an unfixed bug on the profile page of the user when the user wants on the "see my recipes" section.

### Content 

- All the text in the website is original, however some of the following websites has been used to check information for the recipes, and some extract of text has been used for the database:

![Alt text](https://www.recipetineats.com/spanish-churros-recipe/)
![Alt text](https://spanishsabores.com/antonias-salmorejo-recipe/)

- Grids, buttons, navs and forms have been created using bootstrap 4.3 templates.
- Icons in the footer are from www.fontawesome.com
- Pverall information and guidance was extracted from Code Institute (Authentication, MondoGB etc...)
- README.me file has been taken from a template from Code Institute.
- Developed using VS code and Github.

### Media

- All the images used in the website are owned by the following websites

![Alt text](https://www.recipetineats.com/spanish-churros-recipe/)
![Alt text](https://www.wikipedia.org/)
![Alt text](https://www.picjumbo.com/)

## Deployment

- The project has been deployed using Heroku app and can be seen life here.

![Alt text](https://mediterranean.herokuapp.com/)
