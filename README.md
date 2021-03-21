# LittleFlowers Spa

LittleFlowers is a spa located in Galway (Ireland) that offers a multitude of services, treatments and facilities.


# Table Of Contents

-   [User Experience](#user-experience)
-   [Features](#features)
-   [Technologies Used](#technologies-used)
-   [Testing](#testing)
-   [Deployment](#deployment)
-   [Credits](#credits)

## User Experience

-   [The Strategy Plane](#the-strategy-plane)
-   [The Scope Plane](#the-Scope-plane)
-   [The Structure Plane](#the-structure-plane)
-   [The Skeleton Plane](#the-skeleton-plane)
-   [The Surface Plane](#the-surface-plane)


### User Stories

The goal of this website is to showcase the spa, allowing customers to see what facilities are available, what treatments are offered and who is performing them.
The owner of the spa wants to increase the visibility and online presence of his business in order to increment its revenue. 

- Case 1: As a spa customer, I want to see the different treatments offered, their prices, and send enquiries to the spa
- Case 2: As a spa customer, I want to know who is going to do the treatment, what's their professional background and what they are specialised in.

### The Scope Plane

Users need to know what treatments are available, how much do they cost and what is their duration, in order to be able to decide how many treatments to book based on their budget and time.
Users also need to know that who is going to perform those treatments is a team of qualified professionals, with experience and tenure.

### The Structure Plane

The website will have a simple structure to meet the users needs:
- Home page with introduction to what can be found on the website (facilities, treatments, team pages), with a small section for reviews from frequent customers
- Treatments page: list of all available treatments with price and duration
- Facilities page: simple preview of the facilities available with a short description
- Team page: this page has two goals:
    1. show to the customers that the staff members are qualified professionals
    2. if a returning customer had a treatment in the past and want to book another treatment with the same person, they can easily do so even if they didn't remember the team member's name.
- All pages will have contact details in the footer, so that at any point the customer can contact the spa to check the availability and book an appointment.

### Wireframes

- [Home Page Wireframe](https://drive.google.com/file/d/16jf2mTJFocQcSzgAo074IYApLB4rgJuD/view?usp=sharing)
- [Treatments Page Wireframe](https://drive.google.com/file/d/1DI111dHViTy4XiTRItU8Bvbig9kdWBnV/view?usp=sharing)
- [Facilities Page Wireframe](https://drive.google.com/file/d/1pFnuEb9Rg5QKEU8gdVohRA5FFmPtqEWZ/view?usp=sharing)
- [Team Page Wireframe](https://drive.google.com/file/d/1mtRimAEPNAdOj-dA3KNnCuePRDBZf9XW/view?usp=sharing)

### The Surface Plane

The color palette of the website will be dark red - dark pink - pink - white.
Fonts will be:
- Philosopher for headings and logo
- Nunito for standard text

## Features

-   [Existing Features](#existing-features)
-   [Features Left to Implement](#features-left-to-implement)
 
### Existing Features

- Feature 1 - allows potential customers to see the treatments offered and their prices
- Feature 2 - allows potential customers to know the staff and their professional background
- Feature 3 - allows returning customers to check if the staff member who gave them the treatment previously is still working there, get their name and request the treatment with them again in case they enjoyed it the first time
- Feature 4 - allows potential and returning customers to get in touch to check availability, book or ask questions by calling or sending an email
- Feature 5 - allows potential customers to see all the social pages of the spa
- Feature 6 - allows potential customers to have a preview of the facilities available (sauna, steam room, pool, hot tub)


### Features Left to Implement
- Add booking system in the future

## Technologies Used

- [Balsamiq](https://balsamiq.com/) for the wireframes of this readme.md file
- [Bootstrap](https://getbootstrap.com/) to use the grid system, pre-formatted buttons in home-page, collapsible navbar
- [Animate.css](https://animate.style/) for transitions of banner heading of each page
- [FontAwesome](https://fontawesome.com/) for icons
- [Google Fonts](https://fonts.google.com/) for fonts
- [Hover.css](http://ianlunn.github.io/Hover/) for transitions effect in navbar and facilities page
- [JavaScript](https://code.jquery.com/) for collapsible navbar

## Testing

Usability and responsiveness were tested on the followin browsers:
- Google Chrome (Version 89.0.4389.72 (Official Build) (x86_64))
- Firefox (86.0 (64-bit))
- Safari (Version 13.0.5 (15608.5.11))
- Microsoft Edge (Version 89.0.774.57 (Official Build) (64bit))

All sections and divs adapted to the screen size as expected, all links worked fine and the navigation was flawless.

Case 1: As a spa customer, I want to see the different treatments offered, their prices, and send enquiries to the spa
- Treatments are described in a dedicated page, with a clear indication of price and duration.
- It's possible to enquire with the spa from any page using the clickable links in the footer to send an email or make a phone call.

Case 2: As a spa customer, I want to know who is going to do the treatment, what's their professional background and what they are specialised in.
- This is possible from the Team page, which highlights in a clear and structured way each staff member's experience/background, tenure at the spa and speciality or certification.

The Google Chrome Lighthouse feature was used on all 4 pages to measure Performance, Accessibility, Best Practices and SEO.
Results can be seen here:
- [Home Page](https://drive.google.com/file/d/1LqFAXg9LEcX8hSRixCrZssSuM4UsEWF1/view?usp=sharing)
- [Treatments](https://drive.google.com/file/d/1NTX8pMfEWF437KC5XKSmP4jCZ2FiddfG/view?usp=sharing)
- [Facilities](https://drive.google.com/file/d/1JW-1BBOKBV93toSlPP3RQDHN3JowPKqU/view?usp=sharing)
- [Team](https://drive.google.com/file/d/1gAoTLHpPtLj3pTHVrZT7TjbQlR31H1bi/view?usp=sharing)

I used the following validators to check my HTML and CSS code:

[HTML Validator](https://validator.w3.org/)
Outcome: Document checking completed. No errors or warnings to show. (all 4 pages)

[CSS Validator](https://jigsaw.w3.org/css-validator/validator)
Outcome: Congratulations! No Error Found.

### Bugs

- I initially didn't use the container class when using bootstrap grid (which should have the structure container > row > column). This caused horizontal overflow.
After adding the container (or container-fluid) class, the issue was fixed.

- I wasn't able to configure a collapsible navbar from [Bootstrap instructions](https://getbootstrap.com/docs/4.0/components/navbar/).
I used the scripts at the end of [this repository](https://github.com/Code-Institute-Solutions/BootstrappingYourNextBigIdea-BS4/blob/master/03-Components/03-progressive_enhancements_with_javascript_components-part-1/index.html) instead.

- I wanted the navbar to be always at the top of the page, even when scrolling down. This caused the navbar to cover the banner too.
To avoid this, I just added a div with class fix-navbar-issue, with the only purpose of "pushing down" the banner so that the navbar didn't cover it.

- I tried to set a transition in the Facilities page using the visibility value, which didn't work. I found [here](https://stackoverflow.com/questions/27900053/css-transition-with-visibility-not-working) the reason why and changed the transition to affect the opacity value.

## Deployment

This project was developed using GitPod, pushed to GitHub and deployed using GitHub Pages.

To deploy to GitHub Pages from its GitHub repository, the following steps were taken:

1. Log into GitHub
2. From the list of repositories on the screen, select **matteofiorini92/LittleFlowers-Spa**
3. From the menu items near the top of the page, select **Settings**
4. Scroll down to the **GitHub Pages** section
5. Under **Source** click the drop-down menu labelled **None** and select **main**
6. In the **folder** drop-down, the **/root** folder is automatically selected
7. Click on **Save**
8. The project is now deployed and the URL of the website is available in the GitHub Pages section

### Hot to run this project locally

To clone this project into Gitpod you will need:

1. A Github account
2. Use the Chrome browser

Then follow these steps:

1. Install the Gitpod Browser Extension for Chrome
2. After installation, restart the browser
3. Log into Gitpod with your gitpod account
4. Navigate to the Project GitHub repository
5. Click the green GitPod button in the top right corner of the repository
6. This will trigger a new gitpod workspace to be created

To work on the project code within a local IDE such as VSCode, Pycharm etc:

1. Follow this link to the [GitHub repository](https://github.com/matteofiorini92/Flowers-Spa)
2. Click on the Code button
3. In the drop-down, copy the URL that you see in the HTTPs tab
4. In your local IDE, open the terminal
5. Change the current working directory to the location where you want the cloned directory to be made
6. Type git clone and paste the URL you copied in Step 3
7. Press Enter. Your local clone will be created.

## Credits

### Content

The text for the facilities and treatments descriptions were inspired by the following websites:
- [steam room benefits](https://www.pinterest.ie/pin/382243087099210412/)
- [sauna benefits](https://cryopurespa.com/infrared-sauna-benefits/)
- [hot stone massage](https://www.healthline.com/health/hot-stone-massage#benefits)
- [facial](https://www.tripsavvy.com/what-is-a-facial-3090025)


### Media
The photos used in this site were obtained from

- [Unsplash](https://unsplash.com/)
    - [home banner](https://unsplash.com/photos/SMwCQZWayj0)
    - [staff 1](https://unsplash.com/photos/ROJFuWCsfmA)
    - [staff 2](https://unsplash.com/photos/nwdPxI1h4NQ)
    - [pool](https://unsplash.com/photos/hCTLx7QrE-w)

- [Pixabay](https://pixabay.com/)
    - [staff 3](https://pixabay.com/photos/face-cute-happy-man-male-person-2171923/)
    - [sauna](https://pixabay.com/photos/woman-sauna-spa-wellness-beauty-936549/)
    - [jacuzzi](https://pixabay.com/photos/pool-water-swimming-sport-holiday-3810389/)
    - [steam room](https://pixabay.com/photos/spa-day-steam-relaxation-relax-4671389/)
    - [facilities](https://pixabay.com/photos/bathing-person-water-foam-soap-918720/)
    - [treatments](https://pixabay.com/photos/spa-woman-facial-beauty-salon-4481538/)
    - [team](https://pixabay.com/photos/relaxation-spa-massage-686392/)
    - [hot stones](https://pixabay.com/photos/massage-relaxation-massage-389719/)
    - [bath](https://pixabay.com/photos/people-man-water-bathtub-side-2603530/)
    - [facial](https://pixabay.com/photos/spa-massage-beauty-lifestyle-woman-5388990/)
    - [deep tissue](https://pixabay.com/photos/massage-shoulder-relaxation-massage-389716/)
    - [head and shoulders](https://pixabay.com/photos/woman-young-massage-head-massage-3688233/)
    - [manicure](https://pixabay.com/photos/people-hands-manicure-cuticle-2587157/)

### Acknowledgements

The content of the deployment section of this readme.md was mostly taken from [this webinar](https://www.youtube.com/watch?v=7BteidgLAyM).