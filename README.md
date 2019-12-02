# Z Services 
Milestone Project #1: User-Centric Frontend Development - Code Institute

Z Services is a small businnes who cleaning windows with purified water in Wigan and surrounding areas. 
You can find the live demo of the site [here:](https://milka77.github.io/z-services/ "Z Services Homepage")


## UX

I want to create a clean design for the site focused on the basic information about the company and their service.
For the collapsable mobile navigation menu I've used only CSS to create a mobile version of the navigation. I got the hint “checkbox” from my mentor Ali, I get the inspiration from these sites:: [inspiration 1](http://jsfiddle.net/5FzRL/4/) and [inspiration 2](https://codepen.io/42EG4M1/pen/ByvGPa).  I reviewed those two code snippets and created my own code and menu. 

### User Stories
* At the **opening page** on **_Destop computers_** users should be able to see the navigation bar at the top of the page in fixed position. When users hovering over the navigation the links should change the background color and text color to clearly see which menu they want to activate. 
At the **_Mobile version_** they should see the menu button fixed on the top left corner. While they press this button the navigation menu will expand to the top of the page. By pressing it again the navigation will be closing. 
* **Navigation bar** on large screens, when users hovering over the navigation the links should change the background color and text color to clearly see which menu they want to activate. By pressing any of the navigation features the site jumps to the selected section with a smooth scrolling effect by using the code `scroll-behavior: smooth;`.
* At **About me** section users should see a brief introduction and info from the company. 
* **F.A.Q.s** section should answer most of the questions of the users. If there are still any questions unanswered they should use the contact section to get the answer. 
* **Contact** section users should see a form which they can fill out and receive their free quotation shortly. 


## Features

### Existing Features

* Home - Allows users to reach the starting page from anywhere on the site. 
* About Me - A brief description of the company and from the owner.
* F.A.Q.s - Frequently asked questions about window cleaning and the company.
* Contact form - Allows users to fill and submit the form to request a free quotation for their windows will be cleaned.  
* Collapsable menu at mobile version of the site. 


### Features left to Implement

* Picture gallery - Shows pictures before and after the work been done. 

## Technologies Used

* HTML
* CSS
* [Font Awesome](https://fontawesome.com/ "Font Awesome Homepage") 
* [Google Fonts](https://fonts.google.com/ "Google Fonts Homepage")
* Favicon generator [favico.io](https://favicon.io/favicon-generator/)

This project was written in HTML & CSS using Cloud9 and is currently hosted on GitHub pages. 
I used Font Awesome icons to create a nice and simple social media link section in the footer. 
As my mentor, Ali mentioned I can use [Bootstrap](https://getbootstrap.com/) if I want it's allowed to use it, but he recommended that I should do every coding by myself that's the way how you can learn and fully understanding coding. I accepted his recommendation and not used Bootstrap. 
Every coding, styling is made by myself.

## Deployment 
The site is hosted and published using GitHub pages and deployed from the master branch only. The publishing steps you can find [here](https://help.github.com/en/github/working-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site). To deploy correctly the site the landing page must be named index.html. Future updated will shown automatically on the page you don't need to do anything. 

## Testing

Validated my [HTML](https://validator.w3.org/) and [CSS](https://jigsaw.w3.org/css-validator/) code was no error found.
I was testing the site with Chrome developer tools on my desktop PC, and with my iPad mini2
and on my iPhone SE and with multiple browsers (Safari, Chrome, Firefox, Internet Explorer) to make sure compatibility and responsiveness working.
#### Navigation
Navigation links were tested and pointing at the selected section. 
Mobile navigation button working. Opening and closing the navigation menu as it should be.
Desktop navigation inverting hovering effect working.
#### All links are working 
Tested all the links on every device which I used for testing was every link working. The social media links are using the `target="_blank"`attribute so they opening in a new tab of the browser. 
#### Testing contact form: 
* When trying to submit an empty form without the required fields an error message appears. 
* An error message appears when you try to submit the form with an invalid email address.
* After all required fields are filled out and the form was submitted a success message appears.


The site have the mobile first approach design. The navigation menu changes from a box on the top left corner on mobile version to a full width top fixed navigation bar on the desktop version.  


## Media

Pictures are from [Clipart Library](http://clipart-library.com/) and [Shutterstock](https://www.shutterstock.com/home). 
The photos used in this site were obtained from Zoltan the owner of Z Services. 