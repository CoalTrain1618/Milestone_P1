![Men of Wales logo](/assets/images/MenofWalesLogo_small.webp) 
# Men of Wales

The Men of Wales website is the central function of the Men of Wales grassroots charity. This charity aims to improve the mental health and wellbeing of men across South Wales by facilitating group walks for new and current service users. The website features current group walks for visitors to view and book, and also offers direction to other services that can help with mental health.

### Wedsite multi device display here
---

## Images of page features here

### Home Page

#### Navbar 
![navbar-colapsed](/assets/images/website-features/nav-bar-feature-collapsed.png)
![navbar-expanded](/assets/images/website-features/nav-bar-feature.png)

I chose to use Bootstrap framework as a base for the collapsing Navbar, to allow for a responsive and clean design across all screen sizes.
* Contains navigation links to all pages for quick and easy access for the visitor
* Replicated across all pages

#### Footer

![footer](/assets/images/website-features/footer.png)

The footer design is simple and concise, allowing users to navigate to the charity’s social media, copyright information, and a home link to return to the main page. The footer is pushed to the bottom using the website’s flex column design, with a flex 1 property on the {main} element to ensure it takes growth priority.

#### Walking image carousel 

![walking-carousel](./assets/images/website-features/walk-picture-carousel.png)

Image carousel section for quick display of walks long with facts and navigation. Used Bootsrap for base carousel framework, then customised to suit.

* Images of past group walks for visitors scrolling the home page
* Facts for why walking is great
* Join us button for quick navigation to walks page

#### Need Help Support card

![support section](./assets/images/website-features/supportcard.png)

Support card on the homepage is for visitor navigation to the need help page.

* This card is coloured differently to allow for easy visual identification in case a visitor is in crisis.
* Features get support button, navigates to support page

#### Walkers words text carousel

![walk review carousel](./assets/images/website-features/walk-review-carousel.png)

Autoplay text carousel for walkers reviews. Used Bootstrap autoplay (no controls) carousel for base. Then customised to be text only.

* Features walkers words for visitors to hear from other users.

#### About us shortcut card

![About us section](./assets/images/website-features/aboutUsSection.png)

About us allowsthe visitor an option to learn about the organisation whilst at near the bottom of the page.

### Walk Page

#### Walk Cards
 
![Walk Cards](./assets/images/website-features/walkCard.png)

The Walk card is designed with Bootstrap's row class design. Cards are designed to give visitor an insight as to what to expect fromt the walk.

* Image of Walk
* Location of walk, along with map loacation
* Time of meet-up
* Walk leader
* Average group size

The big stuff card is for big organised walks.

![Big Stuff card](./assets/images/website-features/bigStuffCard.png)

### About Us page

The about us page is a mainly text bassed page for allowing the visitor to understand who we are and what we want to work towards, along with som stats. 

![About Us](./assets/images/website-features/aboutPage.png)

### Need help page

This page is designed for visitors seeking extra support. It features cards highlighting organisations for crisis helplines and general support. We’ve included diverse options to cater to various needs.

![Support guidance](./assets/images/website-features/supportGuidance.png)

Along with the cards, we have general guidance for connecting with local GP.

### Sign Up page

The Sign-Up page is a form where visitors can register to join one of the Men of Wales walks.

![Sign Up page](./assets/images/website-features/sign-upPage.png)

This form utilises the required function to ensure it is filled out correctly by the visitor, with minimal allowance for error.

When the visitor submits the form, they are taken to a success page, where they are informed that the form submission was successful.

![Successfully submitted](./assets/images/website-features/successPage.png)

### 404 error page

Custom page has been added for continuity of design.

![404 Error](./assets/images/website-features/404Page.png)
---

## Responsive Design


---

## Browser testing

I tested the website across three different browsers to check responsivness and if the page functions correctly. 


---

## User Story testing

| User Story | Testing |
| ---| ---|
| As a visitor who is interested in joining a group walk. I would like to see what walking groups are available to join and where. | Created card fors visitors to get information on each walk. Features include Image of walk, location with map pin and walk times. |
| As a visitor who isn't sure about walking in groups, i would like to see group sizes and to feel familiar with what to expect. | Added a feature in to display average group size for visitor familiarity. | 
|  As a previous attendee to a walk, I want to quickly access the sign up form for the other walks. | Added sign-up form to navigation bar for quick access. |
|  As a visitor who is also looking for support with my mental health, i would like to see recourses to mental health services. | Created a page containing general information on mental health along with links to other services for crisis and mental health support. |
| As a visitor I would like to see more about Men of Wales and the work they do. | Created an about page for further information on Men of Wales. This page includes goals and story, along with stats. 

---
### link to Wireframes Here !

PDF file containing all Wireframes designs
[Wireframes PDF](/Milestone_P1/MenOfWales_Wireframes.pdf)

---

### Technologies Used Here
----

* HTML
  * main strucure on of the website

* CSS
  * Styling the website with css external file

* JavaScript
  * Used for adding in bootStrap & Fontawesome funtionality

* Bootstrap
  * Used for framework of various sections (tagged with Bootstrap)

* Favicon.io
  * Used for favicons generated 

* Fontawesome
  * Used for Icons across site

* ChatGPT
  * Used for generation website logo and images used

* Balsamic
  * Creating and designing the Wireframes for Men of Wales 

* Git hub
  * used for hosting files and deployment

* Git
  * Used for commiting changes and pushing to Github.

* VS Code
  * Code editor used for writing all code in this project. 

* Lighthouse 
  * USed for website performance testing

* Wave 
  * Used for testing website  accessability

* W3cs
  * Used for code validation

---

## Testing

## Wave Tests

* I used Wave for accessibility testing across all pages, to ensure the site has good accessibility. During testing there was no errors found.

* All pages had an alert due to both the home button and the page icon linking to index.html. 

## Results
#### Index Wave Results
![index wave](./assets/images/wave-results/index-wave.png)

* The index page had contrast errors on the 'previous' & 'next' buttons on the carousel. I changed the icons and it's colour to be igh contrast numerous times, but contrast error still persisted. 

#### Walks Wave Result
![walks wave](./assets/images/wave-results/walks-wave.png)

#### About wave result
![about wave](./assets/images/wave-results/about-wave.png)

#### Need Help Wave Result
![needhelp wave](./assets/images/wave-results/help-wave.png)

#### Sign-Up Wave Result
![signup wave](./assets/images/wave-results/signup-wave.png)

#### Success Wave Result
![Success wave](./assets/images/wave-results/success-wave.png)

#### 404 wave result
![404 wave](./assets/images/wave-results/404-wave.png)

---

## W3C Code Validation

I used W3C code validator for checking all HTML code is valid. I pasted each pages code into the validatior individually for most accurate validation.

## Results
#### index.html
![index.html](./assets/images/w3c-Validation/indexHtml%20validation.png)

#### walks.html
![walks.html](./assets/images/w3c-Validation/walksHtmlValidation.png)

#### aboutUs.html
![aboutUs.html](./assets/images/w3c-Validation/aboutHtmlValidation.png)

#### needhelp.html
![needhelp.html](./assets/images/w3c-Validation/needhelpHtmlValidation.png)

#### signUp.html
![signup.html](./assets/images/w3c-Validation/signUpHtmlValidation.png)

#### success.html
![success.html](./assets/images/w3c-Validation/successHtmlValidation.png)

#### style.css
![style.css](./assets/images/w3c-Validation/cssValidation.png)

Satisfied with the result of no errors accross all pages individually, I then tested the HTMl and CSS with URL testing method.

#### URL test HTML
![URL HTML](./assets/images/w3c-Validation/urlHtmlValidation.png)

#### URL test CSS
![URL CSS](./assets/images/w3c-Validation/urlCssValidation.png)

Both tests yielded no errors.

## Light house testing for performance scores

I used Lighthouse testing for performance tests, checking that the site runs smoothly on both desktop and mobile. As expected, mobile results are slightly lower.

When putting each page through testing, tests showed that the images were originally oversized, causing unnecessary load times. As a result, I resized every image on the website for better optimisation, as well as changed their format to .webp.

## Results

### Index Desktop & Mobile
* Desktop
  * ![Index results](./assets/images/lighthouseScores/indexLighthouse.png)
* Mobile  
  * ![Mobile](./assets/images/lighthouseScores/indexPhoneLighthouse.png)

### Walks Desktop & Mobile
* Desktop
  * ![Desktop](./assets/images/lighthouseScores/walksLighthouse.png)
* Mobile  
  * ![Mobile](./assets/images/lighthouseScores/walkPhoneLighthouse.png)

### About Us Desktop & Mobile
* Desktop  
  * ![Desktop](./assets/images/lighthouseScores/aboutUsLighthouse.png)
* Mobile  
  * ![Mobile](./assets/images/lighthouseScores/aboutPhoneLighthouse.png)

### Need Support Desktop & Mobile
* Desktop  
  * ![Desktop](./assets/images/lighthouseScores/needHelpLighthouse.png)
* Mobile
  * ![Mobile](./assets/images/lighthouseScores/needhelpPhoneLighthouse.png)

### Sign Up Desktop & Mobile
* Desktop  
  * ![Desktop](./assets/images/lighthouseScores/SignUpLighthouse.png)
* Mobile
  * ![Mobile](./assets/images/lighthouseScores/signupPhoneLighthouse.png)

### Success Desktop & Mobile
* Desktop  
  * ![Desktop](./assets/images/lighthouseScores/successfulLighthouse.png)
* Mobile
  * ![Mobile](./assets/images/lighthouseScores/successPhoneLighthouse.png)
---

## Form Validation

Carried out form validation to ensure there are minimal errors when users fill out the form. All fields, except for additional information, are required inputs. I expect the webpage to alert users when a field is not sufficiently filled.

## Results

### Full Name Field - Alert expected
![Full Name](./assets/images/form-validation/nameFieldValidation.png)

### Email Field - Alert expected
![Email](./assets/images/form-validation/emailFieldValidation.png)

### Select Field - Alert expected
![Select Walk](./assets/images/form-validation/walkSelectValidation.png)

### Phone Number Field - Alert expected
![Phone Number](./assets/images/form-validation/phoneFieldValidation.png)

### Subission Success - Expecting to be taken to for success page upon submission
![Success Page](./assets/images/form-validation/sumbitFormValidation.png)

---

### Deployment

IDE used VS code

insert info about GIT commands

insert info on Git Hub

---

### Credits Here

