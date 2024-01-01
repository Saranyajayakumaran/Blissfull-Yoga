# Happy yoga
This website aims to provide a platform for yoga enthusiasts to explore and practice yoga at their own pace. Whether you're a beginner or an experienced yogi, our website offers live events to experience the yoga .Dive into the transformative world of yoga, where mind, body, and soul harmonize. 


![Responsive image](https://raw.githubusercontent.com/Saranyajayakumaran/Happy-Yoga/main/assets/images/screenshot-responsive.webp)

## Features

- Navigation
    - The navigation at the top of the page shows he name of the club and other navigation links are at the right side corner of the page.
    - The heading contain a logo which denotes the yoga posture.
    - The navigation links Home, Event and Sign up which link to other pages of the website.
    
![Alt text](assets\images\screenshot-navigation.webp)
---
- Home page

    - About
        - The about section contains the information about the yoga which describes how useful doing yoga for our lifestyle.
    - Hero image
        - The image is intended to encourage prople to do the yoga . It shows how flexible we can when we do the yoga in day to day life.
    -   Benifits of yoga
        -  The section describes the benefits of yoga which creates a awareness to the people.
    - Contact
        - The contact section has the address ,telephone number an Eail id to contact the Happy yoga club.

- Event page
    - The event page is created with a background image and informations of the event organised to explore the yoga for free of cost. It also contains the types of yoga organised ,time of each event and place of the event.  

![Event page screen shot](<assets\images\screenshot event page.webp>)


- Sign Up page
    - The sign up page is created for the registration purpose. It hepls the user to register with their details for the event.

- Confirmation page
    - The confirmation page is created to tell the registered user that they successfully registered for the Event.


- Social Media links
    - The social media links of the Happy yoga club is given un the footer section of all the pages. 
    ![Social media link/footer](assets\images\screenshot-footer.webp)



## Testing
- I tested that this website is working in different browsers: Chrome, Firefox ,Safari.
- I confirmed that the project is responsive,looks good and functions on all standard screen size using the devtools device toolbar.
- I confirmed that the Navigation, Home page, Event page,Sign up and footer section are all readable and easy to understand.
- I have confirmed that the form works: require entries in the field, will only accept an email field,and the submit btoon works.



## Bugs
Solved bugs
- When  i run the index page, the horizontal line in the navigatio bar when selecting the page was not appear. I discover that is because of typo in class active. After changed, it works.
- When i run the project after deployment my background images were not displayed. I found that is because of the relative path of the image and i have changed it, then it works.
 background: url("../images/Event-PAGE-2.webp")
- Remove assets and replace with .. resolved the error.
## Validator Testing
Fixed bugs
- HTML
    - Missed some end tag when passing through the official W3C validator
    - Resolved it and again tested : No error found.
- CSS
    - Missed some semicolon and pixel.
    -Resolved it and gain tested : No error found.
- Accessibility
    -I confirmed that th ecolor and fonts chosen are easy to read and accessible by renning it through lighthouse in devtools.

    ![lighthouse report](https://raw.githubusercontent.com/Saranyajayakumaran/Happy-Yoga/main/assets/images/screenshot-report.webp)

Unfixed Bugs
    - No unfixed bugs.


## Deployment
    - The site was deployed to GitHub pages. The steps to deploy are as follows:
        - In the GitHub repository,navigate to the settings tab
        - Select the Pages from Code and automation
        - Then select the give the correct repository name ,default branch to main.
        - The page provide the link to complete website.

## Credits
    - Content
        - The code to make the navigation section and social media section was taken from the Love Running project.

    - Media
        - The images in the header was taken from pixabay.
    

