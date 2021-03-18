# LittleFlowers SPA

LittleFlowers is a SPA that offers a multitude of services, treatements and facilities.


#Table Of Contents

-   [User Experience](#user-experience)
-   [Features](#features)
-   [Technologies Used](#technologies-used)
-   [Testing](#testing)
-   [Deployment](#deployment)
-   [Credits](#credits)

## User Experience

Use this section to provide insight into your UX process, focusing on who this website is for, what it is that they want to achieve and how your project is the best way to help them achieve these things.

-   [The Strategy Plane](#the-strategy-plane)
-   [The Scope Plane](#the-Scope-plane)
-   [The Structure Plane](#the-structure-plane)
-   [The Skeleton Plane](#the-skeleton-plane)
-   [The Surface Plane](#the-surface-plane)


### The Strategy Plane

The goal of this website is to showcase the spa, allowing customers to see what facilities are available, what treatments are offered and who is performing them.

- As a SPA customer, I want to see the different treatments offered, their prices, and send enquiries to the SPA
- As a SPA customer, I want to know who is going to do the treatment, what's their professional background and what they are specialised in.

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

### The Skeleton Plane

### The Surface Plane

The color palette of the website will be dark red - dark pink - pink - white.
Fonts will be:
- Philosopher for headings and logo
- Nunito for "normal" text

This section is also where you would share links to any wireframes, mockups, diagrams etc. that you created as part of the design process. These files should themselves either be included as a pdf file in the project itself (in an separate directory), or just hosted elsewhere online and can be in any format that is viewable inside the browser.

## Features

-   [Existing Features](#existing-features)
-   [Features Left to Implement](#features-left-to-implement)
 
### Existing Features

- Feature 1 - allows potential customers to see the treatments offered and their prices
- Feature 2 - allows potential customers to know the staff and their professial background
- Feature 3 - allows returning customers to check if the staff member who gave them the treatment previously is still working there, get their name and request the treatment with them again in case they enjoyed it the first time
- Feature 4 - allows potential and returning customers to get in touch to check availablity, book or ask questions by calling or sending an email
- Feature 5 - allows potential customers to see all the social pages of the SPA
- Feature 6 - allows potential customers to have a preview of the facilities available (sauna, steam room, pool, hot tub)


### Features Left to Implement
- Add booking system in the future

## Technologies Used

In this section, you should mention all of the languages, frameworks, libraries, and any other tools that you have used to construct this project. For each, provide its name, a link to its official site and a short sentence of why it was used.

- [Balsamiq](https://balsamiq.com/) for the wireframes of this readme.md file
- [Bootstrap](https://getbootstrap.com/) to use the grid system, pre-formatted buttons in home-page, collapsible navabr
- [Animate.css](https://animate.style/) for transitions of banner heading of each page
- [FontAwesome](https://fontawesome.com/) for icons
- [Google Fonts](https://fonts.google.com/) for fonts
- [Hover.css](http://ianlunn.github.io/Hover/) for transitions effect in navbar and facilities page
- [JavaScript](https://code.jquery.com/) for collapsible navbar

## Testing

In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your user stories from the UX section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as:

1. Contact form:
    1. Go to the "Contact Us" page
    2. Try to submit the empty form and verify that an error message about the required fields appears
    3. Try to submit the form with an invalid email address and verify that a relevant error message appears
    4. Try to submit the form with all inputs valid and verify that a success message appears.

In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

### Bugs

- I initially didn't use the container class when using bootstrap grid (which should have the structure container > row > column) which caused horizontal overflow.
After adding the container (or container-fluid) class, the issue was fixed.

- I wasn't able to configure a collapsible navbar from [Bootstrap instructions](https://getbootstrap.com/docs/4.0/components/navbar/).
I used the scripts at the end of [this repository](https://github.com/Code-Institute-Solutions/BootstrappingYourNextBigIdea-BS4/blob/master/03-Components/03-progressive_enhancements_with_javascript_components-part-1/index.html) instead.


If this section grows too long, you may want to split it off into a separate file and link to it from here.

## Deployment

This project was developed using GitPod, pushed to GitHub and deployed using GitHub Pages.

To deploy to GitHub Pages from its GitHub repository, the following steps were taken:

1. Log into GitHub
2. From the list of repositories on the screen, select **matteofiorini92/LittleFlowers-SPA**
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

1. Follow this link to the [GitHub repository](https://github.com/matteofiorini92/Flowers-SPA)
2. Click on the Code button
3. In the drop-down, copy the URL that you see in the HTTPs tab
4. In your local IDE, open the terminal
5. Change the current working directory to the location where you want the cloned directory to be made
6. Type git clone and the paste the URL you copied in Step 3
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