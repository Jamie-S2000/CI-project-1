# Jamie's guitar Shop

Jamie's Guitar Shop is a small independent guitar shop in the heart of Newcastle.

The webiste is designed to show customers the services the shop provides.

<img src="assets/readme-imgs/am-i-responsive.webp">

<!--add contents section-->

## Planning and Development

- __Target Audience__

The target audience for the website is Guitar Players.

The website aims to infrom guitarists of the services and products provided by the shop.

These are people who:

* Are looking to purchace new guitar gear (e.g. guitars, amps, straps etc.).

* Are looking to join a community of poeple to play guitar with.

* Are looking for a guitar tech for any alterations to their guitars.

<br>

- __User Stories__

    * As a user, I want to find out more about Jamie's Guitar Shop.

    * As a user, I want to find a local guitar shop.

    * As a user, I wnat to find a community of guitar players.

    * As a user, I want to find a reliable guitar tech.

<br>

- __Site Objectives__

    * To inform customers of a local shop.

    * To show the user where to find the shop.

    * To give the user a way to contact the shop.

    * To inform users when they can visit.

    * To inform users when events are happening.

    * To help customers get in touch with a guitar tech.

<br>

- __Approach__

    * The site will be created witht he principles of user design.

    * The site will provide users with information about the shop.

    * The site will provide users with a way to contact the shop.

    * The site will provide users with a way to find it on social media.

    * The site will be accessible.

    * The site will be easiliy navigated and consistant throughout.

<br>

- __Colour Scheme__

The colours of the site were chosen to match the colours of the guitars and to contrast eachother.

* The yellow colour was picked as a common colour for acoustic guitars while matching the Les Paul image.

* The dark purple was piced for titles and social links as it contrasts the yellow and gives some varience from the text.

* The text is a very dark grey chosen to make the text slightly less harsh wile aslo maintaining contrast

* Finally the background of the whole site is an off-white making it easier to look at whilst also matching the white on the Stratocatser.

<img src="assets/readme-imgs/colours.webp">

<br>

- __Typography__

The fonts were chosen to allow for easy reading in the document whilst the titles give a more welcoming vibe.

* Montserrat Alternatives: Gives the titles a more laid back and welcoming vibe to the site whist staying easily readable.

* Monserrat: This is a clear and concise font that is easiliy legible whilst being a slightlyu toned down version of the title font.

<br>

## Features

### Existing Features

- __Favicon__

* The favicon was chosen to be relevent to the website and to suit the colours.

<img src="assets/readme-imgs/favicon.webp">

- __Navigation Dropdown__

* The navigation dowpdown menu is there to help users navigate the site.

* It has links to the home page, guitar jamns page and guitar techs page.

<img src="assets/readme-imgs/nav-bar.webp">

<br>

- __Sticky Navigation bar__

* The sticky navigation bar allows users to navigate the site no matter where on the page they are.

* It sticks in a fixed posiytion on the top of each page.

* It uses a burger icon to helkp the user reconise it's use.

<img src="assets/readme-imgs/sticky-bar.webp">

<br>

- __Images__

* The images chosen were two of the most popular guitars on the home page and a selection on the jams page.

* The home page guitars were chosen as they will be easily reconisable.

* The selection was chosen to show more variation in guitars.

The links to eacfh image is:

* Stratocaster (1st home page image): https://www.pexels.com/photo/electric-guitar-amplifier-cord-port-808354/

* Les Paul (2nd home page image): https://www.pexels.com/photo/close-up-shot-of-a-guitar-8134200/

* Asorted guitars (guitar jams image): https://www.pexels.com/photo/electric-guitars-on-display-5396357/

<img src="assets/readme-imgs/guitar-imgs.webp">

<br>

- __About Us Section__

The about us section gives some basic information about the shop and can direct users to other pages.

* It lays out what the store is, what they sell and what services they can provide.

* there are also links within the text so users can get to other pages of the website.

<img src="assets/readme-imgs/about-us.webp">

<br>

- __Opening Times__

The opening times section allows useres to know when they can visit and call the shop.

<img src="assets/readme-imgs/opening-times.webp">

<br>

- __Where To Find Us__

This section has 2 key features:

*Address*

This allows users to find the shop via map apps.

*Map*

This is taken from google maps.

* The map is embeded from google maps and so is fully interactable.

* The map allows users of the website to get a general location of the shop making it easier to find.

<img src="assets/readme-imgs/map.webp">

<br>

- __Get In Contact__

This section allows users to contact the shop.

They can contact the shop by:P

* Email

* Phone

Both of these are linked alowing users click the method of contact and they will be directed to their Email or Skype/phone dial.

<img src="assets/readme-imgs/contact-us.webp">

<br>

- __Social Links__

The footer contains all the social media links for users to follow and find out more about the shop.

It contains links to:

* Facebook

* X/Twitter

* Instagram

They are represeneted by icons taken from https://fontawesome.com.

Each link opens in a new tab as they are going to external websites.

<img src="assets/readme-imgs/social-links.webp">

<br>

- __Guitar Technicians__

This page gives users some information about the guitar store technicions and allows them to submit a form to contact one.

Some features of the form are:

* Each field being required before submition.

* A section for the user to tell the shop what they need help with.

* Submit and Reset buttons that change colour when hovered over.

* Users are sent to another page once the form is submited.

<img src="assets/readme-imgs/tech-form.webp">

<br>

- __Thank You Page__

The Thank You Page displays when a user has submitted a form.

It displays a small message thanking the user for sending a message and confirming their request has been sent.

<img src="assets/readme-imgs/thank-you.webp">

<br>

- __Jam Nights__

The Jam Night Page gives the user information on social nights at the shop.

The page was desinged to be:

* Welcoming to all players.

* Informative to when they are.

* Show inclucivity to anyone without an instrument.

<br>

## Testing

The site was tested thoughout development on these devises:

* HP Omen with a 17" display - Chrome, Edge

* 27" monitor - Chrome, Edge (The website was ran on the HP Omen and this was to check sizing on larger displays)

* Samsung Galaxy S21 Ultra - Chrome, Samsung Internet

* IPad Air - Safari

* IPhone 13 - Safari

Google Dev-tools was also used thoughout to test responciveness.

- __Testing the home page__

I tested the links in the dropdown menu and that they all went to the correct page.

I tested the links in the about us section to make sure they also went to the correct page.

I tested the map to make sure it could be moved, zoomed in on and opened in a new tab.

I tested the phone numbger link which at first was not working.

This was due to having spaces in:

```
<a href="tel: +44 1234 567890">
```

This was fixed by removing the spaces and the link now works:

```
<a href="tel:+441234567890">
```

I tested the email link to mkae sure it allowed users to send an email to the address.

I tested all the social media links to make sure they all open in new tabs and go to the correct links.

- __Testing The Guitar Technicians Page__

I tested the links in the dropdown menu and that they all went to the correct page.

I tested each text box to make sure they were all required.

I tested the email text box to make sure it had to have an email submited.

I tested the submit and reset buttons to make sure they changed colours when hovered over.

I tested the submit button to make sure it directed the user to the correct page. This was also tested to make sure it wont allow a form to be submitted without all the information.

The reste button wast tested to mkae sure it rest all the data in the form.

I tested all the social media links to make sure they all open in new tabs and go to the correct links.

- __Testing The Thank You Page__

I tested the links in the dropdown menu and that they all went to the correct page.

I tested all the social media links to make sure they all open in new tabs and go to the correct links.