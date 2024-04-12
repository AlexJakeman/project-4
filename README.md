# Fit Freak's README

[View the live project here.](https://fit-freak-e89ae93eb2ed.herokuapp.com/)

## Desktop Homepage

![Image of the homepage from a Desktop user's perspective](/media/readme/homepage-desktop.png)

## Mobile Homepage

![Image of the homepage from a Mobile user's perspective](/media/readme/homepage-mobile.png)

## Description

Welcome to Fit Freaks, the best place for your e-commerce gym-based needs!

### Project Goal

#### CI Project Example Idea 2

- Fit Freak is aiming to provide top end merchandise and supplements to anyone and everyone that enjoys fitness.

#### Site owner's goal:

- Build an e-commerce store focused on the needs of regular gym-goers, and newbies alike.

#### External user’s goal:

- To join a ﬁtness community and purchase exercise merchandise and supplements.

## UX

### Exisiting Features

#### Navigation bar

Summary:
- The navigation bar allows us to select a part of the page that we'd like to navigate to, as well as having the logo as a top of the page button.

![Image of the branded5 navbar from a Desktop user's perspective](/media/readme/feature-navbar-desktop.png)

#### Accurate Basket Total

Summary:
- The basket total stays up to date with whatever you put in your basket.

![Image of the basket total after adding products to the bag](/media/readme/basket-total-mobile.png)

#### Toast Messages

Summary:
- The toast messages vary depending on the response from the user's action. 

![Successful toast message](/media/readme/toast-message-mobile.png)
![Warning toast message](/media/readme/toast-message-alert-mobile.png)
![Error toast message](/media/readme/toast-message-error-mobile.png)

#### Product Creation Form

Summary:
- The add product form allows store managers to add their own products. 

![Image of the product add page](/media/readme/product-add-page-mobile.png)

## Design

### Website Color Scheme

- Main Background: #FFF (Body / Light Text)
- Dark Accent: #343a40 (Navbar / Dark Contrast Elements)
- Light Accent: #fed136 (Certain Titles / Accenting / Light Elements)

### Font

We predominantly use the "Montserrat" font as it's big and bold, and helps to draw the end user in to the webapp.

## Testing

### Validation/Code Linter

1. W3C (https://jigsaw.w3.org/css-validator/#validate_by_input)
- Checked all CSS manually using the above site. 

2. Python (https://extendsclass.com/python-tester.html)
- Checked all Python code within the main.py file using the site above. 

3. HTML (https://marketplace.visualstudio.com/items?itemName=CelianRiboulet.webvalidator)
- There are no clear HTML errors within the project. Checked using W3C VS Code extension (https://marketplace.visualstudio.com/items?itemName=CelianRiboulet.webvalidator)
- To confirm, I am aware of some errors in HTML validation for Django based HTML.

4. CSS (https://marketplace.visualstudio.com/items?itemName=CelianRiboulet.webvalidator)
- There are no clear CSS errors within the project. Checked using W3C VS Code extension.

5. JavaScript (https://www.site24x7.com/tools/javascript-validator.html)
- There are no clear JS errors within the JavaScript files.

### Test Environments: The test will be conducted on multiple devices and browsers, including:

Desktop (Windows and macOS):
- Google Chrome
- Mozilla Firefox
- Microsoft Edge
- Safari

Mobile (iOS and Android):
- Safari (iOS)
- Google Chrome (Android)

### Automated Testing
Automated testing involves using tools and scripts to test the application automatically. This can include unit tests, integration tests, and end-to-end tests. Automated testing is beneficial for catching regressions and ensuring that the application functions as expected after code changes.

### Manual Testing
Manual testing is performed by human testers who interact with the application to identify bugs, usability issues, and other problems. Manual testing is valuable for evaluating the user experience, design, and overall functionality.

### User Stories

#### Story 1: Navigation and Menu

Objective: Test the navigation functionality and menu responsiveness.

Steps:

1. Expected Result: The HTML page opens in the web browser.
- Actual Result: Confirmed, the page opens as expected.
2. Expected Result: The navigation menu is visible.
- Actual Result: Confirmed, the navigation menu is visible.
3. Expected Result: Clicking the menu icon toggles the display of navigation links.
- Actual Result: Confirmed, the navigation links appear/disappear when the menu icon is clicked.
4. Expected Result: Clicking on each navigation link scrolls to the respective sections.
- Actual Result: Confirmed, each link scrolls to the correct section.
5. Expected Result: The menu adapts to different screen sizes upon resizing.
- Actual Result: Confirmed, the menu is responsive to different screen sizes.

![Image of the navbar with an active title to assist the user with knowing where they are in the page from a Desktop user's perspective](/media/readme/story-one-active-navbar-title.png)

#### Story 2: Term Submission Form

Objective: Validate the functionality of the term submission form.

Steps:

1. Expected Result: The "Submit a word / phrase" section is located on the page.
- Actual Result: Confirmed, the section is present.

2. Expected Result: Successfully submitting the form adds the term to the "Community Added Terms" section.
- Actual Result: Confirmed, the term appears in the list upon successful submission.

3. Expected Result: Appropriate success or error messages are displayed.
- Actual Result: Confirmed, success or error messages appear as expected.

![Image of the invalid input feedback from a Desktop user's perspective](/media/readme/invalid-input-feedback.png)

4. Expected Result: Submitting the form with invalid fields triggers appropriate error messages.
- Actual Result: Confirmed, error messages appear for invalid fields.

![Image of the disabled Add Term button from a Desktop user's perspective](/static/assets/img/readme/disabled-add-term-btn.png)

5. Expected Result: The Add Term button should remain disabled until all fields are valid.
- Actual Result: Confirmed, Add Term button is enabled only when all fields are filled with valid inputs.

![Image of the enabled Add Term button from a Desktop user's perspective](/static/assets/img/readme/enabled-add-term-btn.png)

6. Expected Result: The Live Term counter at the top of the page should increase by 1 upon successfully adding a term.
- Actual Result: Confirmed, the Live Term counter does increase by 1.

![Image of the successful save banner from a Desktop user's perspective](/static/assets/img/readme/successful-save-banner.png)

#### Story 3: Term Update and Delete

Objective: Confirm the update and delete functionality of the community-added terms.

Steps:

1. Expected Result: The "COMMUNITY ADDED TERMS" section is present.
- Actual Result: Confirmed, the section is present.
2. Expected Result: Updating a term modifies the information in the "Community Added Terms" section.
- Actual Result: Confirmed, the term details are updated.
3. Expected Result: Deleting a term removes it from the list.
- Actual Result: Confirmed, the term is removed upon deletion.
4. Expected Result: Appropriate error messages are displayed for non-existent terms.
- Actual Result: Confirmed, error messages appear for non-existent terms.
5. Expected Result: The Live Term counter at the top of the page should not increase by 1 when successfully updating a term.
- Actual Result: Confirmed, the Live Term counter does not increase by 1.
6. Expected Result: The Live Term counter at the top of the page should decrease by 1 upon successfully deleting a term.
- Actual Result: Confirmed, the Live Term counter does decrease by 1.

![Image of the successful update banner from a Desktop user's perspective](/static/assets/img/readme/successful-update-banner.png)

![Image of the successful delete banner from a Desktop user's perspective](/static/assets/img/readme/successful-delete-banner.png)

#### Story 4: Modal Windows

Objective: Test the content and functionality of modal windows (Privacy Policy and Terms of Use).

Steps:

1. Expected Result: Clicking on the "Privacy Policy" link opens the modal window.
- Actual Result: Confirmed, the "Privacy Policy" modal window opens.

2. Expected Result: Content within modal windows is clear and complete.
- Actual Result: Confirmed, content is clear and complete.

3. Expected Result: Closing modal windows using the keyboard or clicking outside works.
- Actual Result: Confirmed, modal windows close as expected.

4. Repeat steps for "Terms of Use" modal.

![Image of the privacy policy modal from a Mobile user's perspective](/static/assets/img/readme/modal-privacy-policy.png)

![Image of the terms of use modal from a Mobile user's perspective](/static/assets/img/readme/modal-terms-of-use.png)

#### Story 5: Term Table Search

Objective: Test the functionality of the term search feature.

Steps:

1. Expected Result: Searching for a term filters the table to display only relevant rows.
- Actual Result: Confirmed, the table updates as expected.

2. Expected Result: Clearing the search input restores the table to its original state.
- Actual Result: Confirmed, the table returns to the original state.

![Image of the terms of use modal from a Desktop user's perspective](/static/assets/img/readme/feature-terms-table-search.png)

#### Story 6: Footer Links

Objective: Verify the functionality of links in the footer.

Steps:
1. Expected Result: Clicking on each social media link opens in new tabs.
- Actual Result: Confirmed, links open in new tabs.

2. Expected Result: Clicking on "Privacy Policy" and "Terms of Use" opens the respective modal windows.
- Actual Result: Confirmed, modal windows open as expected.

#### Story 7: Data

Objective: When updating on the front-end, data on the back-end should be amended to match the changes.

Steps:
1. Expected Result: Updating fields using the front-end Update modal form should update the back-end Google Sheet data.
- Actual Result: Confirmed, the back-end data is correct.

2. Expected Result: Updating fields using the front-end Delete button should update the back-end Google Sheet data.
- Actual Result: Confirmed, the term is deleted in Google Sheets.

![Image of the update modal in use from a Desktop user's perspective](/static/assets/img/readme/feature-update-modal-form.png)

![Image of the Google Sheets matching data from a back-end perspective](/static/assets/img/readme/successful-update-google-sheet.png)

#### Examples of Exploratory Testing for "Gamer Jargon"

Open HTML Page:
- Expected Result: HTML page opens in the web browser.
- Actual Result: Confirmed, page opens as expected.

Test Navigation, Submit a Term, and Term Update/Delete:
- Follow the steps outlined in Stories 1, 2, and 3.

Test Modal Windows, Term Table Search, and Footer Links:
- Follow the steps outlined in Stories 4, 5, and 6.

Testing Responsiveness:
- Expected Result: Page layout remains responsive depending on what kind or size of device you're using.
- Actual Result: Confirmed, page layout is responsive.

Check External socials Links:
- Expected Result: External socials links open in new tabs.
- Actual Result: Confirmed, socials links open in new tabs.

Testing Scripts:
- Expected Result: JavaScript functions without errors.
- Actual Result: Confirmed, no errors in the console.

Testing Compatibility:
- Expected Result: Page functions correctly in different browsers.
- Actual Result: Confirmed, page works in various browsers.

Documentation:
- Expected Result: README.md is updated with instructions.
- Actual Result: Confirmed, documentation is updated.

Final Checks:
- Expected Result: No spelling or grammatical errors in the copy.
- Actual Result: Confirmed, no errors found.

### Automated Testing Examples (NOT IMPLEMENTED):

#### Regression Testing:

- Scenario: After implementing new features or making changes to the codebase, there is a need to ensure that existing functionalities still work as expected.

Automation Approach:
- Develop a suite of regression tests covering critical functionalities.
- Automate the execution of these tests to run after each code change.
- This ensures that existing features are not broken by new updates.

#### Cross-browser Testing:

- Scenario: Verifying that a web application works consistently across different web browsers (Chrome, Firefox, Safari, Edge) and versions can be time-consuming if done manually.

Automation Approach:

- Use a testing framework such as Selenium or Playwright to automate browser interactions.
- Develop scripts that simulate user interactions on different browsers.
- Automate the execution of these scripts to run on various browser configurations.
- This ensures the application's compatibility with multiple browsers.

#### Load Testing:

- Scenario: Assessing the performance and scalability of a web application under various load conditions (multiple users, high traffic) is crucial to identify potential bottlenecks.

Automation Approach:

- Use tools like Apache JMeter, Gatling, or locust.io to simulate a large number of virtual users.
- Develop test scenarios to mimic real-world user interactions.
- Automate the execution of these load tests to analyze the application's performance under different load levels.
- This helps identify performance issues and ensures the application can handle expected user traffic.

### Further Testing

- The Website was tested on Google Chrome, Internet Explorer, Opera and Safari browsers.
- The website was viewed on a variety of devices such as Desktop (OSX & Windows), Laptop (OSX & Windows), Tablet, iOS (iPhone) and Android (Google Pixel).
- A large amount of testing was done to ensure that all pages were linking correctly.
- Friends and family members were asked to review the site and documentation to point out any bugs and/or user experience issues.


## Technologies Used

Gamer Jargon uses the following technologies:

- JavaScript: [Learn more about JavaScript](https://en.wikipedia.org/wiki/JavaScript)
- Python: [Learn more about Python](https://en.wikipedia.org/wiki/Python_(programming_language))
- Django: [Learn more about Django](https://en.wikipedia.org/wiki/Django_(web_framework))
- HTML: [Learn more about HTML](https://en.wikipedia.org/wiki/HTML)
- CSS: [Learn more about CSS](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)
- Bootstrap: [Learn more about Bootstrap](https://startbootstrap.com/theme/agency)

## Data Model 

In this section, describe the data model designed for your project. You can include information about the entities, attributes, and relationships in your data model. Based on the example provided, your data model could look like this:

### Attributes:

- Word (String)
- Context (String)
- Meaning (String)
- Added_by (String)
- Date (DateTime)
- Id (Integer)

Here's an example entry in the dataset:

- Word: Mod (Modification)
- Context: Altered versions of a game created by players or developers to introduce new features or change existing ones.
- Meaning: Customized content that modifies the original game.
- Added_by: Luke Skywalker
- Date: 02/07/2022 02:45:34
- Id: 1111

![Image of the Google Sheets Data Model in use](/static/assets/img/readme/data-model-example.png)

### Google Sheets Implementation

Guide used: [Creating a Google Sheet](https://learn.codeinstitute.net/courses/course-v1:CodeInstitute+LSND101+2021_T1/courseware/c05d81d784ad412498d09e2f3c081a9f/53fe80e254f8462884e3d526b3a95c5e/)

In this guide, I was assisted by Anna Greaves (CI Content Dev) via a video that is designed to help students setup and implement a Google Sheets based database using Google's Drive API. 

#### Google Drive API Integration

Implementation Details:
The project utilizes the Google Drive API for storing and managing the dataset. Here's an overview of how it's integrated:

- Google Sheets as a Database:

The project uses Google Sheets as a database to store the dataset.
Each entry in the dataset corresponds to a row in a Google Sheets document.

- Google Drive API Integration:

The Google Drive API is used to interact with the Google Sheets document programmatically.
API requests are made to read, write, and update data within the Google Sheets document.

- Authentication and Authorization:

The project implements OAuth 2.0 for authentication and authorization to access the Google Drive API securely.
Users need to authenticate themselves with their Google accounts to access and modify the dataset.

- Data Model:

The data model remains consistent with the structure described earlier, but the storage medium is Google Sheets hosted on Google Drive.

#### Benefits

Utilizing Google Drive API for data storage offers several advantages:

- Scalability: Google Sheets provide scalable storage, accommodating datasets of varying sizes.
- Accessibility: Data stored in Google Sheets can be easily accessed and modified by authorized users from anywhere with an internet connection.
- Integration: Integration with Google Drive API allows seamless interaction with the dataset, enabling functionalities like adding, updating, and querying data programmatically.
- Usability: The database is designed for ease of use and accessibility. CRUD (Create, Read, Update, Delete) operations can be performed efficiently.

## Frameworks, Libraries & Programs Used

- Google Fonts https://fonts.google.com/specimen/Geo
Google fonts were used to import the different fonts into the project.

- Font Awesome (https://fontawesome.com/):
Font Awesome was used on all pages throughout the website to add icons for aesthetic and UX purposes.

- GitHub (https://github.com/):
GitHub is used to store the projects code after being pushed from Git.

- Google Sheets (https://docs.google.com/spreadsheets)
Google Sheets was integral to host the data for the webapp.

- Start Bootstrap (https://startbootstrap.com/theme/agency)
This theme assisted me with getting the UI for my page. 

## Deployment

### Heroku
The project was deployed to Heroku following a guide from CodeInstitute.
1. See CI link:
- https://learn.codeinstitute.net/courses/course-v1:CodeInstitute+FL101+2021_T1/courseware/4d995e6a4f384c3dafffdcbde3fd25ef/c39056b888d74e8ca8576c6890651626/

2. Live project link here:
- https://fit-freak-e89ae93eb2ed.herokuapp.com/

### Forking the GitHub Repository
By forking the GitHub Repository we make a copy of the original repository on our GitHub account to view and/or make changes without affecting the original repository by using the following steps...
1. Log in to GitHub and locate the GitHub Repository
2. At the top of the Repository (not top of page) just above the "Settings" Button on the menu, locate the "Fork" Button.
3. You should now have a copy of the original repository in your GitHub account.

## Credits

### Content

- All text-based content was written by the developer.
- Custom code written by developer
- Hero image - (https://www.freepik.com/free-photo/fitness-stuff-grey-background_5162337.htm#from_view=detail_serie)
- Bootstrap - Theme  / Components (https://getbootstrap.com/docs/4.6/getting-started/introduction/)
- Fontawesome - (https://fontawesome.com)

### Acknowledgements

- Stackoverflow for JS/Python error troubleshooting.
- YouTube for JS/Python error troubleshooting.
- ChatGPT - Data generation (e.g, list of descriptions for products, etc.)

### Code inspiraton from external sources

- Stack Overflow - Bug fixing
- Code Institute - https://learn.codeinstitute.net/courses/
