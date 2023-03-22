# Rose's Flower Shop

The Rose's Flower Shop website is designed to be a responsive website that allows visitors to view it on a range of devices

https://beffyd.github.io/Milestone-Project/

[add images from https://ui.dev/amiresponsive once pathing is fixed for GitHub pages]

## Initial discussion:

Rose's Flower Shop is a business that provides customers with high-quality flower arrangements for various events. They need a website to allow customers to reserve their flower arrangements and pay upon collection at the shop. 

Essential information for the site: 
- Company History
- Packages available 
- Location of store 

## User stories: 

Client goals:
- To be able to view the site on a range of devices
- To make it easy for people to find the store on google maps
- To make it easy for users to select and reserve their desired flower arrangement 
- To allow users to find Rose's Flower Shop on social media platforms

First-time visitor goals:
- I want to find out the different price ranges available to me 
- I want to be able to navigate the site easily on mobile or desktop 
- I want to be able to find the shop on social media

Returning visitor goals:
- I want to see what flower arrangments are available to me depending on the season
- I want to be able to contact the shop via email or telephone to answer any questions I may have.

Frequent Visitor goals:
- I want to be able to reserve my packages with ease in time for my event.

# Design 

[add colour palette image]

I have used the colours shown in the colour palette here as I think they have a nice fresh energy to them and in a sense represent springtime, which is obviously when most flowers come into bloom. 

## Typography

The font "Merriweather" is used on the index page for the company history paragraph. It is a sans-serif font.
The font "Playfair Display" is used throughout the site for the prices and also the company logo. It is a sans-serif font. 

## Imagery

I will use images of different kinds of flower arrangements across the site to show the variety of packages that are available to customers.

## Wireframes

Wireframes made on Balsamiq can be viewed at: https://imgur.com/a/XHOppk2 
The site was designed with desktop and mobile in mind and was later optimized to fit tablets also. 

## Screenshot of desktop and mobile view:

Screenshots of the project can be viewed at: https://imgur.com/a/r9IIBvf

# Features

The website is comprised of a home page, 2 pages of flower arrangements for different occasions, and a contact page. 

On these pages the features are: 
- a navigation bar
- social media links that are accessible by clicking the relevant icons 
- a form that allows the user to choose a package with a radio button
- a map to find the store in person/ to collect the reserved package 

**The home page (Index page)**

The home page for Rose's Flower shop on the desktop shows a slide show of the shop's best work, on mobile, it has one still image of a flower arrangement. Underneath the picture/slideshow, it has a paragraph on the company's history since it was established.

**Birthdays Page**

The Birthdays page allows users to browse a selection (3) of flower arrangements and select one to reserve with a form. 

**Weddings Page**

The Weddigss page allows users to browse a selection (6) of flower arrangements and select one to reserve with a form. 

**Contact**

The contact page shows a map of the shop and also has a telephone number and email address for the customer. 

## Accessibility

I have been mindful whilst coding to ensure the website is accessible. This has been achieved by:
- Using semantic HTML
- Using sans-serif fonts for the site (These are easy-to-read fonts for people with dyslexia and learning difficulties)
- Adding alt text to images for users that are using a screen reader

## Technologies used:

HTML AND CSS3

GITPOD

GITHUB

BOOTSTRAP 

FONT AWESOME 

GOOGLE FONTS 

## Deployment

The site is deployed using GitHub Pages 

**To Deploy the site using GitHub Pages:**

Login (or signup) to Github.
Go to the repository for this project, https://beffyd.github.io/Milestone-Project/.
Click the settings button.
Select pages in the left-hand navigation menu.
From the source dropdown select the main branch and press save.
The site has now been deployed, please note that this process may take a few minutes before the site goes live.
Local Development

**How to Fork**
To fork the repository:

Log in (or sign up) to Github.
Go to the repository for this project, beffyd.github.io/Milestone-Project/
Click the Fork button in the top right corner.
How to Clone

**To clone the repository:**
Log in (or sign up) to GitHub.
Go to the repository for this project, beffyd.github.io/Milestone-Project/
Click on the code button, select whether you would like to clone with HTTPS, SSH or GitHub CLI and copy the link shown.
Open the terminal in your code editor and change the current working directory to the location you want to use for the cloned directory.
Type 'git clone' into the terminal and then paste the link you copied in step 3. Press enter.


## Acknowledgments:

bootstrap navbar

font awesome icons (socials in the footer and contact)

unsplash for free images used in packages

htmlcolorcodes.com for hex and RGB colour values

@gradar on codepen.io for their HTML and CSS slide show code I used on the index.html page (https://codepen.io/gradar/pen/BaavLLo)

getbootstrap.com documentation on display: flex 

Google embedded iframe HTML used for the map on the contact page

## Thanks to:
The Code Institute and London South Bank University for providing a fully funded course available to me. 

Thanks to my brother Joe who knows how to code.

Thanks to Tom from MySpace for encouraging me to write my first code.

Thanks to my mentor Jubril Akolade.


# Testing

## Automated testing 

https://imgur.com/a/ZW2LPfn

please note, all checks passed aside from 2 errors on the birthday-packages page and wedding-packages page "end div tag seen but there were open elements" and "unclosed form element" however could not remove without breaking the page.

## Manual Testing

### Testing User Stories

`First Time Visitors`

| Goals | How are they achieved? |
| :--- | :--- |
| I want to find out the different price ranges available to me. | The user can click on the 'birthdays' or 'weddings' page in the top right on the navbar |
| I want to be able to navigate the site easily on mobile or desktop | The user can view the site on either mobile, desktop or tablet and the site will adjust to fit screen size|
| I want to be able to find the shop on social media| The user can see there are social media links on all pages in the footer, also the user is asked to follow on instagram on the home page |

`Returning Visitors`

|  Goals | How are they achieved? |
| :--- | :--- |
| I want to see what flower arrangments are available to me depending on the season | The user will be shown the available flowers by images on 'Wedding' & 'Birthdays' page|
| I want to be able to contact the shop via email or telephone to answer any questions I may have.| The user can find contact details on the 'contact' page |

`Frequent Visitors`

| Goals | How are they achieved? |
| :--- | :--- |
| I want to be able to reserve my packages with ease in time for my event. | The user can reserve their desired flower arrangement by selecting the relevant radio button and submitting the form|

## Full testing

**PC:**
Windows 10 PC with an Acer KG271 monitor (24inches) 

**Mobile devices:**
- iPhone SE
- iPhone XR
- iPhone 12 Pro 
- Pixel 5
- Samsung galaxy s8
- Samsung galaxy s20 Ultra

**Tablet:**
- iPad air
- iPad mini 

Each device tested the site using:
 - Google Chrome 
 - Mozilla Firefox
 - Internet Explorer 

 | Feature | Expected Outcome | Testing Performed | Result | Pass/Fail |
| --- | --- | --- | --- | --- |
| The sites title | Link directs user back to homepage | Clicked title | Homepage reloads | Pass |
| Social media icons/links | Icons open in new tab when taking user to site | Clicked icon(s)| New tab opens relevant social media page | Pass |
| Radio buttons on form| Radio buttons should only allow one choice | Clicked on the different options available | Radio button switches to last package selected | Pass |
| Reservation form button | Form submitted  | Information filled out and "Reserve my package" buttonn pressed | opens a new tab which loads https://formdump.codeinstitute.net/| pass

## Solved Bugs

Navbar kept aligning left next to the logo. Fixed by adding the "justify-content-end" attribute to the navbar.

Navbar was not optimised on mobile or tablet. Fixed by targeting the navbar toggler and changing the width in chrome developer tools, then applying the rule to CSS.  

The Navbar position was moving down on tablets (devices over 509px). Fixed by adding a media query for screens with a minimum width of 509px. 

Slideshow syntax error, removed "-web kit-" prefix from animation and keyframes CSS.

## Version Control: 
Git & GitHub 

## Deployment:

Project was deployed on Gitpages and is viewable at: 

https://beffyd.github.io/Milestone-Project/




