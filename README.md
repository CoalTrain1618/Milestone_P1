![Men of Wales logo](/assets/images/MenofWalesLogo_small.webp) 
# Men of Wales

The Men of Wales website is the central function of the Men of Wales grassroots charity. This charity aims to improve the mental health and well-being of men across South Wales by facilitating group walks for new and current service users. The website features current group walks for visitors to view and book, and also offers direction to other services that can help with mental health.

![Multi device image](./assets/images/website-features/techsini-image.png)
---

## Content

* [Features](#featre)
* [User Story Tests](#usrStry)
* [WireFrames](#wireFrm)
* [Technologies](#techno)
* [Testing](#testing)
  * [Wave Tests](#waveTest)
  * [W3C Tests](#w3cTest)
  * [Lighthouse Tests](#LightHTest)
  * [Form Validation](#frmVal)
  * [Browser Tests](#brwsTest)
  * [Functional Testing](#FncTest)
* [Deployment Control](#depCtr)
* [Credits](#cred)


## Features

<a id="featre"></a>

### Home Page

#### Navbar 
![navbar-colapsed](/assets/images/website-features/nav-bar-feature-collapsed.png)
![navbar-expanded](/assets/images/website-features/nav-bar-feature.png)

- Contains navigation links to different pages on the site, allowing the visitor to navigate efficiently

- Enhances the user experience, ensuring quick navigation and improving engagement.

#### Footer

![footer](/assets/images/website-features/footer.png)

- Provides users with quick access to social media platforms and displays copyright information clearly.

- Enhances user engagement by encouraging social media interaction as well as displaying important copyright information.

#### Walking image carousel 

![walking-carousel](./assets/images/website-features/walk-picture-carousel.png)

- Displays past walks using an image carousel, along with the title "Why Walk?" with informative facts and a link to the walks page for further browsing.

- Captures user interest by displaying past walks, educates visitors on the benefits of walking, and encourages further interest in the walks page.

#### Need Help Support card

![support section](./assets/images/website-features/supportcard.png)

- Provides users with an accessible and clear option to seek additional support services, featuring supportive and comforting text.

- Allows users to quickly identify the further support page in case they need fast access to helplines.

#### Walkers words text carousel

![walk review carousel](./assets/images/website-features/walk-review-carousel.png)

- Showcases an auto-play text carousel featuring walkers' reviews with the title "Walkers' Words" and text in speech marks of walkers' stories.

- Provides reviews from past walkers, encouraging new visitors to join walks and building a sense of community and familiarity.

#### About us shortcut card

![About us section](./assets/images/website-features/aboutUsSection.png)

- Urges visitors to explore the website further by visiting the About Us page to read about the organisation.

- Promotes engagement by encouraging visitors to find out more about the charity, furthering visitor familiarity with the organisation and its mission.

### Walk Page

#### Walk Cards
 
![Walk Cards](./assets/images/website-features/walkCard.png)

- Enables visitors to browse available walks and view essential walk information and a visualisation of the walk.

- Gives visitors a convenient and informative overview of upcoming walks while promoting visitors' familiarity with each walk.


The 'Big Stuff' card is for big organised walks.

![Big Stuff card](./assets/images/website-features/bigStuffCard.png)

### About Us page

![About Us](./assets/images/website-features/aboutPage.png)

- Provides visitors with a comprehensive overview to help them understand who we are, our mission, and what we aim to achieve.

- Educates visitors about the organisation's background and goals, promoting visitor engagement with joining our walks.

### Need help page

![Support guidance](./assets/images/website-features/supportGuidance.png)

- Provides visitors seeking extra support with a page featuring cards that highlight organisations for crisis helplines and general support, offering diverse options to cater to various needs.

- Ensures visitors can quickly and easily find relevant support services and crisis helplines, giving visitors easy-to-access support.

### Sign Up page

![Sign Up page](./assets/images/website-features/sign-upPage.png)

- Provides a straightforward form where visitors can register to join one of the Men of Wales walks.

- Facilitates easy registration, encouraging participation by simplifying the sign-up process and ensuring a hassle-free sign up.

![Successfully submitted](./assets/images/website-features/successPage.png)

### 404 error page

![404 Error](./assets/images/website-features/404Page.png)

- Ensures design continuity across the website by incorporating a custom page.

- Maintains a cohesive and unified look throughout the site, enhancing user experience.

---

<a id="usrStry"></a>

## User Story testing

|     UserStory         |          Testing             |
| ----------------------|------------------------------|
| As a visitor who is interested in joining a group walk, I would like to see what walking groups are available to join and where.  | Created cards for visitors to get information on each walk. Features include image of walk, location with map pin and walk times.   |
| As a visitor who isn't sure about walking in groups, I would like to see group sizes and to feel familiar with what to expect.    | Added a feature to display average group size for visitor familiarity.| 
| As a previous attendee to a walk, I want to quickly access the sign-up form for the other walks.                                 | Added sign-up form to navigation bar for quick access. |
| As a visitor who is also looking for support with my mental health, I would like to see resources for mental health services. | Created a page containing general information on mental health along with links to other services for crisis and mental health support. |
| As a visitor, I would like to see more about Men of Wales and the work they do. | Created an about page for further information on Men of Wales. This page includes goals and story, along with stats. |

---

<a id="wireFrm"></a>

### link to Wireframes Here !

PDF file containing all Wireframes designs
[Wireframes PDF](/Milestone_P1/MenOfWales_Wireframes.pdf)

---

<a id="techno"></a>

### Technologies Used Here
----

* HTML
  * Main structure of the website

* CSS
  * Styling the website with an external CSS file"

* JavaScript
  * Used for adding in Bootstrap & Font Awesome functionality

* Bootstrap
  * Used for framework of various sections (tagged with Bootstrap)

* Favicon.io
  * Used for favicons generated 

* Font Awesome
  * Used for Icons across site

* ChatGPT
  * generating the website logo and images some images used

* Balsamiq
  * Creating and designing the Wireframes for Men of Wales 

* GitHub
  * used for hosting files and deployment

* Git
  * Used for committing changes and pushing to GitHub.

* VS Code
  * Code editor used for writing all code in this project. 

* Lighthouse 
  * USed for website performance testing

* Wave 
  * Used for testing website  accessibility

* W3C
  * Used for code validation

---

<a id="testing"></a>

# Testing

<a id="waveTest"></a>

## Wave Testing

Testing was focused to ensure the following criteria were met:

- All forms have associated labels or aria-labels so that this is read out on a screen reader to users who tab to form inputs.
- Colour contrasts meet a minimum ratio as specified in [WCAG 2.1 Contrast Guidelines](https://www.w3.org/WAI/WCAG21/Understanding/contrast-minimum.html).
- Heading levels are not missed or skipped to ensure the importance of content is relayed correctly to the end user.
- All content is contained within landmarks to ensure ease of use for assistive technology, allowing the user to navigate by page regions.
- All non-textual content had alternative text or titles so descriptions are read out to screen readers.
- HTML page lang attribute has been set.
- ARIA properties have been implemented correctly.
- WCAG 2.1 Coding best practices being followed.

## Wave Test Results
#### Index Wave Results
![index wave](./assets/images/wave-results/index-wave.png)

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

<a id="w3cTest"></a>

## W3C Code Validation

I used the W3C code validator to check that all HTML code is valid. I pasted each page's code into the validator individually for the most accurate validation.

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

Satisfied with the result of no errors across all pages individually, I then tested the HTML and CSS with the URL testing method.

#### URL test HTML
![URL HTML](./assets/images/w3c-Validation/urlHtmlValidation.png)

#### URL test CSS
![URL CSS](./assets/images/w3c-Validation/urlCssValidation.png)

Both tests yielded no errors.

---

<a id="LightHTest"></a>

## Lighthouse testing for performance scores

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

<a id="frmVal"></a>

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

### Submission Success - Expecting to be taken to for success page upon submission
![Success Page](./assets/images/form-validation/sumbitFormValidation.png)

---

<a id="brwsTest"></a>

## Browser Testing 

 - I conducted browser tests using four different browsers to check for visual discrepancies and responsive design. Safari tests were conducted on a MacBook.

 |    Browser     |        Version         |      Visual Discrepancies     |                   Responsive Design                     |
 |----------------|------------------------|-------------------------------|---------------------------------------------------------|
 |   Google       |        Latest          |    No visual discrepancies    | Site remains responsive on all pages and screen sizes   |
 |   Edge         |        Latest          |    No visual discrepancies    | Site remains responsive on all pages and screen sizes   |
 |   Brave        |        Latest          |    No visual discrepancies    | Site remains responsive on all pages and screen sizes   |
 |   Safari       |        Latest          |   No visual discrepancies     | Site remains responsive on all pages and screen sizes   |
---

<a id="FncTest"></a>

## Functional Testing

I tested each anchor tag across all pages to ensure they all direct me to the correct destination and function as intended. 

## Results

### - Navbar

- Navbar is copy and pasted to all other pages, so only recording test once.

| Line of Code | Desired Destination | Target _blank | Test Case                | Description                                        | Status |
|--------------|---------------------|---------------|--------------------------|----------------------------------------------------|--------|
| 40    | index.html     | No      | Anchor Tag Functionality | Verify anchor tag redirects to index.html properly | Pass    |
| 41    | walks.html     | No      | Anchor Tag Functionality | Verify anchor tag redirects to walks.html properly | Pass    |
| 42    | about.html     | No      | Anchor Tag Functionality | Verify anchor tag redirects to about.html properly | Pass    |
| 43    | needHelp.html  | No      | Anchor Tag Functionality | Verify anchor tag redirects to needHelp.html properly | Pass    |
| 44    | signUp.html    | No      | Anchor Tag Functionality | Verify anchor tag redirects to signUp.html properly | Pass    |

### - Index HTML

| Line of Code | Desired Destination | Target _blank | Test Case                | Description                                        | Status |
|--------------|---------------------|---------------|--------------------------|----------------------------------------------------|--------|
| 97    | walks.html     | No      | Anchor Tag Functionality | Verify anchor tag redirects to walks.html properly    | Pass    |
| 110   | needHelp.html  | No      | Anchor Tag Functionality | Verify anchor tag redirects to needHelp.html properly | Pass    |
| 137   | about.html     | No      | Anchor Tag Functionality | Verify anchor tag redirects to about.html properly | Pass    |

### - Index Footer

- Footer is copy and pasted to other pages, so only recording the test once.

| Line of Code | Desired Destination | Target _blank | Test Case                | Description                                        | Status |
|--------------|---------------------|---------------|--------------------------|----------------------------------------------------|--------|
| 147   | facebook.com    | yes      | Anchor Tag Functionality | Verify anchor tag redirects to facebook.com properly  | Pass    |
| 148   | instagram.com   | yes      | Anchor Tag Functionality | Verify anchor tag redirects to instagram.com properly | Pass    |
| 149   | X.com           | yes      | Anchor Tag Functionality | Verify anchor tag redirects to x.com properly         | Pass    |
| 150   | linkedin.com    | yes      | Anchor Tag Functionality | Verify anchor tag redirects to linkedin.com properly  | Pass    |

###  - Walks HTML - Map Locations

| Line of Code | Desired Destination | Target _blank | Test Case                | Description                                        | Status |
|--------------|---------------------|---------------|--------------------------|----------------------------------------------------|--------|
| 75    | google.co.uk/map/place  | Yes      | Anchor Tag Functionality | Verify anchor tag redirects to Map pinpoint properly | Pass    |
| 102   | google.co.uk/map/place  | Yes      | Anchor Tag Functionality | Verify anchor tag redirects to Map pinpoint properly | Pass    |
| 131   | google.co.uk/map/place  | Yes      | Anchor Tag Functionality | Verify anchor tag redirects to Map pinpoint properly | Pass    |
| 160   | google.co.uk/map/place  | Yes      | Anchor Tag Functionality | Verify anchor tag redirects to Map pinpoint properly | Pass    |
| 197   | google.co.uk/map/place  | Yes      | Anchor Tag Functionality | Verify anchor tag redirects to Map pinpoint properly | Pass    |

### - Walks HTML - Sign Ups

| Line of Code | Desired Destination | Target _blank | Test Case                | Description                                        | Status |
|--------------|---------------------|---------------|--------------------------|----------------------------------------------------|--------|
| 83    | signUp.html    | No      | Anchor Tag Functionality | Verify anchor tag redirects to signUp.html properly | Pass    |
| 111   | signUp.html    | No      | Anchor Tag Functionality | Verify anchor tag redirects to signUp.html properly | Pass    |
| 140   | signUp.html    | No      | Anchor Tag Functionality | Verify anchor tag redirects to signUp.html properly | Pass    |
| 169   | signUp.html    | No      | Anchor Tag Functionality | Verify anchor tag redirects to signUp.html properly | Pass    |
| 208   | signUp.html    | No      | Anchor Tag Functionality | Verify anchor tag redirects to signUp.html properly | Pass    |

### - needHelp HTML - Website links

| Line of Code | Desired Destination | Target _blank | Test Case                | Description                                        | Status |
|--------------|---------------------|---------------|--------------------------|----------------------------------------------------|--------|
| 79    | samaritans.org      | Yes      | Anchor Tag Functionality | Verify anchor tag redirects to Samritan's site properly | Pass    |
| 87    | callhelpline.org    | Yes      | Anchor Tag Functionality | Verify anchor tag redirects to C.A.L.L's site properly | Pass    |
| 95    | nhs.uk              | Yes      | Anchor Tag Functionality | Verify anchor tag redirects to NHS's site properly | Pass    |
| 111   | umbrellacymru.co.uk | Yes      | Anchor Tag Functionality | Verify anchor tag redirects to Umbrella Cymru's site properly | Pass  |
| 118   | diversecymru.org.uk | Yes      | Anchor Tag Functionality | Verify anchor tag redirects to Diverse Cymru's site properly | Pass    |
| 125   | meiccymru.org    | Yes      | Anchor Tag Functionality | Verify anchor tag redirects to Meic Cymru's site properly | Pass    |

### needHelp HTML - Tel: link

- The tel: anchor tags were tested by opening the link on a phone.

| Line of Code | Desired Destination | Target _blank | Test Case                | Description                                        | Status |
|--------------|---------------------|---------------|--------------------------|----------------------------------------------------|--------|
| 79    | Phone App   | No      | Anchor Tag Functionality | Verify anchor tag Opens Samaritans' number to phone pad properly | Pass    |
| 87    | Phone App   | No      | Anchor Tag Functionality | Verify anchor tag Opens C.A.L.L's number to phone pad properly | Pass    |
| 95    | Phone App   | No      | Anchor Tag Functionality | Verify anchor tag Opens NHS's number to phone pad properly | Pass    |

### 404 error page 

- I placed random text into the index.html to test the 404 page loads

  - ![404 Error](./assets/images/website-features/404-error-input.png)

- I then submitted the URL and the 404 page successfully loaded

  - ![404 success](./assets/images/website-features/404-error-success.png)


---

<a id="depCtr"></a>

## Deployment

### Version Control

The site was created using the Visual Studio code editor and pushed to github to the remote repository ‘tacos-travels’.

The following git commands were used throughout development to push code to the remote repo:

```git add <file>``` - This command was used to add the file(s) to the staging area before they are committed.

```git commit -m “commit message”``` - This command was used to commit changes to the local repository queue ready for the final step.

```git push``` - This command was used to push all committed code to the remote repository on github.

### Deployment to Github Pages

- The site was deployed to GitHub Pages. The steps to deploy are as follows:
  - In the GitHub repository, navigate to the Settings tab.
  - From the menu on the left, select Pages.
  - From the source section drop-down menu, select the Branch: main.
  - Click Save.
  - A live link will be displayed in a green banner when published successfully.

The live link can be found here - https://github.com/CoalTrain1618/Milestone_P1

### Clone the Repository Code Locally

Navigate to the GitHub repository you want to clone to use locally:

 - Click on the Code drop-down button.
 - Click on HTTPS.
 - Copy the repository link to the clipboard.
 - Open your IDE of choice (Git must be installed for the next steps).
 - Type git clone copied-git-url into the IDE terminal.

The project will now have been cloned to your local machine for use.

---

<a id="cred"></a>

## Credits

### Image Credits

- Header Image and walk images from - [unsplash.com](https://unsplash.com/)
- ChatGPT for generating carousel & about us Images

### Honourable mentions 

- Mentor: Gareth, who assisted with ideas and guidance throughout the project.
- Tutor: Marko, who offered guidance throughout the project.
- Fellow Students who offered feedback on the project.
  - Seren hughes
  - Teseo Nicholson
  - Ethan Skidmore

### Tech

- Bootstrap library and [website](https://getbootstrap.com/docs/5.3/getting-started/introduction/) for guidance.
- Microsoft Photos for image resizing.
- freeconvert.com [website]((https://www.freeconvert.com/webp-converter)) for converting images to webp format.
- ChatGPT for image generation
- Microsoft paint for logo colouring
- Styling Ideas for Markdown from [Here](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
