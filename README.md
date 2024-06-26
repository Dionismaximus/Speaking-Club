# English Speaking Club in Cork
The English Speaking Club website is a landing page for people who would like to find some place to communicate with another people in English.
The English Speaking Club, which located in Cork in The Linen Weaver - JD Wetherspoon Pub in Cork offers a fun and rewarding experience in a great location.

Users of the site can get all the necessary information about the club, venue, contacts, read the feedback from current members of the club and make an application to join the club.

![Screenshot of the website. How it looks like on a different screens](assets/images/How%20am%20I%20look%20like.png)

## Features
- __Navigation__
  - Featured at the top of the page, at the very left located the bridge symbol and it also a link to the main home page.
  - The main navigation block is at the fixed top page with navigation links: Home, Our place, Contacts, Join us.
  - The fixed top of the page accomplished with a gradient colour and nav buttons are highlighted with a different colour depending on which page the user is currently on.
  - The mobile version of the website has the nav toggle bar instead usual navigation block.
![Screenshot of the fixed top of the website](assets/images/navigation_block.png)
- __The Header__
  - The header shows the name of the club using a little shadow for added dimension.
  - The header has the main photo with four members of club.
  - The header has a short welcome, brief and clear description of the main purpose of the club.
![Header](assets/images/Header_section.png)

- __Motivation section__
  - The motivation section on the main page contains four blocks of information with the main benefits of club membership.
  - The blocks have the headings with a stand-out color and with added blocks shadowing for better user experience.
![Motivation section](assets/images/Join_us_section.png)

- __Reviews section__
  - Review section has the five reviews from the regulars of the club.
  - Every review block has piece of text, picture and name of the member.
![Reviews section](assets/images/Reviews.png)

- __Join us button__
  - Join us button takes users to a Join Us page where a potential user can apply to join the club.
![Join us button](assets/images/join_us_button.png)

- __Schedule and contacts section__
  - It has a schedule sheet completed in a table that is easily perceived by the user.
  - Contacts block has phone number and e-mail, where user can get furhter information about the club.
![Schedule and contacts section](assets/images/schedule_and_contacts.png)
- __Footer__
  - The footer contains four icons which is links to social media.
  - The fullscreen laptop version of the website has extra navigation list of Home page, Our place page, contacts and Join us page links.
![Footer](assets/images/Footer.png)

- __Our place page__
  - The our place page gives the users an idea of where the weekly club meetings are held.
  - It has a few pictures of the interior and exterior of the pub.
  - At the bottom of the page is the link to the official The Linen Weaver - JD Wetherspoon website and an embedded google map showing the location of the pub.
![Our place page](assets/images/Pub.png)

- __Join us page__
  - Join us page has a form where the user can send his data to join the club.
  - Form collect Name, Last Name, E-mail, Phone number and preferred messenger.
![Join us page](assets/images/join_us_page.png)

## Testing 
- I tested this page in different browsers. The site works fine.
- I confirmed that this website is responsive for all type of screen.
- I confirmed that the all pages, blocks and section are readable and easy to understand.
- I have confirmed that the form works: requires entries in every field, will only accept e-mail in the e-mail field, and the submit button works.

## Bugs
### Solved bugs
- After checked the code on HTML validation service that showed a few errors.
- One image has two target attribute and all images on our_place page have inappropriate name that has a space.
- There was a few errors with label element in join_us form.
- All types of errors displayed in the W3 html validator have been fixed.

## Validator testing
- __HTML__
  - No errors were return after solved two previous errros when passing through the official W3C validator
  ![index.html page result](assets/images/html_page_validator.png "index.html page result")
  ![our_place.html page result](assets/images/our_place_page_validator.png "our_place.html page")
  ![join_us.html page result](assets/images/join_us_page_validator.png "join_us.html page")

- __CSS__
  - No errors were return when passing through the official (Jigsaw) validator
- __Accessibility__
  - I confirmed that the colors and font chosen are easily to read and understand with a high contrast ratio.
  - The website has been checked by running it through lighthouse in devtools
![Lighthouse test results](assets/images/lighthouse_results.png "The result of the main page test by the lighthouse program")
![Lighthouse test results](assets/images/our_place_lighthouse_test.png "The result of the our_place page test by the lighthouse program")
![Lighthouse test results](assets/images/join_us_lighthouse_test.png "The result of the join_us page test by the lighthouse program")

## Deployment
- __The site was deployed to GitHub pages. The steps to deploy are as follows:__
  - In the GitHub repository, navigate to the Settings tab
  - From the source section drop-down menu, select the Master Branch
  - Once the master branch has been selected< the page provided the link to the completed website

  Link to the live site here: [English Speaking Club in Cork](https://dionismaximus.github.io/Speaking-Club/)

## Credits
### Content
- The code to make the navigation toggle bar for mobile version of the website partially was taken from the Love Running Project
### Media
- All icons was taken from [Font Awesome](https://fontawesome.com/)
- The images except our place page was taken from [Pexels](https://pexels.com/)
- The photos for our place page was taken from the official [The Linen Weaver - JD Wetherspoon Pub website](https://www.jdwetherspoon.com/pubs/all-pubs/republic-of-ireland/county-cork/the-linen-weaver-cork/)