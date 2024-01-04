# Happy yoga
This website aims to provide a platform for yoga enthusiasts to explore and practice yoga at their own pace. Whether you're a beginner or an experienced yogi, our website offers live events to experience the yoga. Dive into the transformative world of yoga, where mind, body, and soul harmonize.

Webpage link:https://saranyajayakumaran.github.io/Happy-Yoga/


![Responsive images of the website](https://raw.githubusercontent.com/Saranyajayakumaran/Happy-Yoga/main/assets/images/screenshot-responsive-n%20.webp)

## Features

- Navigation
    - The navigation at the top of the page shows name of the club and other navigation links are at the right side corner of the page.
    - The heading contain a logo which denotes the yoga posture.
    - The navigation links Home, Event and Sign up which navigate to other pages of the website.
    
![Navigation bar of the website](https://raw.githubusercontent.com/Saranyajayakumaran/Happy-Yoga/main/assets/images/screenshot-navigation.webp)
---
- Home page

    - About
        - The about section contains the information about the yoga which describes how useful doing yoga for our lifestyle.
    - Hero image
        - The image is intended to encourage people to do the yoga . It shows how flexible and enthusiastic we can when we do the yoga in day to day life.
    -   Benifits of yoga
        -  The section describes the benefits of yoga which creates a awareness to the people.
    - Contact
        - The contact section has the address,telephone number and Email id to contact the Happy yoga club.

- Event page
    - The event page is created with a background image and informations of the event which is organised to explore the yoga for free of cost. It also contains the types of yoga organised ,time of each event and place of the event.  

![Event page of the website](<https://raw.githubusercontent.com/Saranyajayakumaran/Happy-Yoga/main/assets/images/screenshot event page.webp>)


- Sign Up page
    - The sign up page is created for the registration purpose. It hepls the user to register with their details for the event.
    - The details are First name, Last name, Age, Email, Gender, Category and Submit button . When the user filled all the field in required format and click submit button then the confirmation message will be appeared in confirmation page.

   ![Signup page of the website]( https://raw.githubusercontent.com/Saranyajayakumaran/Happy-Yoga/main/assets/images/screenshot-signup.webp)

- Confirmation page
    - The confirmation page is created to confirm the registration of the user that they successfully registered for the Event.


- Social Media links
    - The social media links Facebook, Instagram ,Youtube and Twitter of the Happy yoga club is given in the footer section of all the pages. 
    - When the user clicks the icon, the social media page will be appeared in separate page.
   
    ![Social media link/footer](https://raw.githubusercontent.com/Saranyajayakumaran/Happy-Yoga/main/assets/images/screenshot-footer.webp)



## Testing
- I tested that this website is working in different browsers: Chrome, Firefox ,Safari.
- I confirmed that the project is responsive,looks good and functions on all standard screen size using the devtools device toolbar.
- I confirmed that the Navigation, Home page, Event page,Sign up and Footer section are all readable and easy to understand.
- I have confirmed that the form works: required entries in the field, will only accept an email field,and the submit button works.

## Functional Testing


| Action      | Expected result  | Pass/Fail     |
|------------|------|----------------|
| Enter Home page URL  | Open the home page   | Pass|
| Click the Event page menu | Display Event page   | Pass|
| Click the Sign up page menu  | Display Sign up page  | Pass |
| Leave the form empty in Signup form and click let's Explore|Pop up message "Please fill out this field"|Pass|
| Type the email in wrong format in signup form and click "Let's Explore"|Pop up message"Please include an '@' in the email address" |Pass
|Fill all the details in the correct format in signup form and click "Lets Explore"|Display confirmation page|Pass|
|Click Home link in confirmation page|Display Home page|Pass|
|Click the Facebook logo in footer |Navigate to Facebook page in new tab|Pass|
|Click the Instagram logo in footer |Navigate to Instagram page in new tab|Pass|
|Click the Twitter logo in footer |Naviagte to Twitter page in new tab| Pass|
|Click the Youtube logo in footer|Navigate to Youtube page in new tab|Pass|



## Bugs
Solved bugs
- When  i run the index page, the horizontal line in the navigation bar for home page when selecting the page was not appear. I discover that is because of typo in class active. After i changed the spelling in HTML page , it works.
- When i run the project after deployment my background images were not displayed. I found that is because of the relative path of the image and i have changed it, then it works.
        background:url("/assets/images/Event-PAGE-2.webp")
        
    - Remove assets and replace with .. resolved the error.
        background: url("../images/Event-PAGE-2.webp")

## Validator Testing
Fixed bugs
- HTML
    - Missed some end tag when passing through the official W3C validator
    - Resolved it and again tested : No error found.
- CSS
    - Missed some semicolon when passing through CSS validator.
    - Resolved it and again tested : No error found.
- Accessibility
    - I confirmed that the color and fonts choosen are easy to read and accessible by running it through lighthouse in devtools.

    ![lighthouse report](https://raw.githubusercontent.com/Saranyajayakumaran/Happy-Yoga/main/assets/images/screenshot-report.webp)

Unfixed Bugs
- No unfixed bugs.


## Deployment
 - Remote 

    The site was deployed to GitHub pages. The steps to deploy are as follows:
    - In the GitHub repository,navigate to the settings tab.
    - Select the Pages from Code and automation menu.
    - Then give the correct repository name and default branch to main.
    - The page provides the link to complete website.
- Local

    The steps to deploy are as follows:
    - In the GitHub repository click code tab and copy the URL of repository.
    - Open command prompt in the local computer and type git clone and paste the URL of GitHub repository.
         "git clone https://github.com/Saranyajayakumaran/Happy-Yoga.git"
    - The repository will be deployed in loco machine.
    - We can check the directory using "dir" command in command prompt. 

## Credits
- Content
    - The code to make the navigation section and social media section was taken from the Love Running  project [Love Running](https://code-institute-org.github.io/love-running-2.0.).

- Media
    - The images in the Website was taken from [Pixabay](https://pixabay.com.).
    - The icons and logo in the website was taken from [Fontawesome](//fontawesome.com/s).

    

