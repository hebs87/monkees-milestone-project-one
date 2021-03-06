# The Monkees Website - Milestone Project One

This is a website that I created for the band, **_The Monkees_**. My website will be used by existing, new and prospective fans and event planners to find out more about the band and its members. They can also listen to the band's music and sign up to the newsletter to keep up to date on the latest news and new music releases. Each page contains links to the band's social media pages.

Users can use my website to book tickets for the band's upcoming concerts, and they will have the ability to book the band to perform at their upcoming events through the contact form.

## UX

My website is for current and potential fans and event planners, who are looking to follow the band, listen to their music, book tickets and book the band to perform at their events. My website provides a *"one-stop-shop"* for users, to help them to achieve all of these things, along with several links to the band's external social media and Wikipedia pages.

I've chosen to style my website in the way that I have, as I felt that it best reflected the brand of the band. The band were at their peak during the late 60s, 70s and 80s, so the fonts and colour scheme that I've chosen best reflect this era and create a feeling of authenticity for users.

### User Stories

- As a potential fan I want to know more about the band and its members so that I can expand my knowledge of the band.
- As the band manager I want fans and event organisers to be able to book the band to perform at events such as weddings and Christmas parties so that the band can connect more with their fans.
- As the band members we want to know when and where event organisers and fans have booked the band to perform so that we can prepare for our performances and tailor them to the type of audience.
- As a lifelong fan I want to listen to the band's songs for entertainment and subscribe to their newsletter so that I'll be kept up to date when they release new material.
- As a wedding planner I want to contact the band so that I can book them to perform at my clients' wedding.
- As a current fan I want to visit the band's website so that I can buy tickets for their concerts.
- As an event organiser I want to know more about the band members and their music so that I can decide whether to book them for an upcoming Christmas party.
- As a current fan I want to sign up to the newsletter so that I can keep up to date with the latest news and tour dates.
- As a potential fan I want to listen to the band's music and visit their social media profiles all from one place so that I can learn more about them and don't have to spend time searching for each of their social media profiles.

### Wireframes

I drew my wireframes using Balsamiq. I have done two wireframes for each page to show my consideration of how to make my website responsive. The links to the files are below:

- [index.html (xl and sm)](https://github.com/hebs87/monkees-milestone-project-one/blob/master/wireframes/index-wireframe-1.png)
- [index.html (md, lg and xl)](https://github.com/hebs87/monkees-milestone-project-one/blob/master/wireframes/index-wireframe-2.png)
- [band.html (xl and sm)](https://github.com/hebs87/monkees-milestone-project-one/blob/master/wireframes/band-wireframe-1.png)
- [band.html (md, lg and xl)](https://github.com/hebs87/monkees-milestone-project-one/blob/master/wireframes/band-wireframe-2.png)
- [music.html (xl and sm)](https://github.com/hebs87/monkees-milestone-project-one/blob/master/wireframes/music-wireframe-1.png)
- [music.html (md, lg and xl)](https://github.com/hebs87/monkees-milestone-project-one/blob/master/wireframes/index-wireframe-2.png)
- [tickets.html (xl and sm)](https://github.com/hebs87/monkees-milestone-project-one/blob/master/wireframes/tickets-wireframe-1.png)
- [tickets.html (md, lg and xl)](https://github.com/hebs87/monkees-milestone-project-one/blob/master/wireframes/tickets-wireframe-2.png)
- [contact.html (xl and sm)](https://github.com/hebs87/monkees-milestone-project-one/blob/master/wireframes/contact-wireframe-1.png)
- [contact.html (md, lg and xl)](https://github.com/hebs87/monkees-milestone-project-one/blob/master/wireframes/contact-wireframe-2.png)

There are some differences between my wireframes and my final website. This was due to visual preferences and feedback received from other users who tested my website.

## Features

### Existing Features

#### All Pages

- **'Sign Up!' call to action button** - This is a button which users are able to click, and it allows them to then complete further steps to sign up for the band's newsletter.
- **Modal with built in form and submit button** - The modal is triggered by the 'Sign Up!' call to action button, and allows users to complete a form and submit their details to sign up to the band's newsletter. Each of the form's fields are required. Currently, no further action is taken when the 'Submit' button is clicked - this is a limitation due to the scope of the project.
- **Hamburger button** - Clicking the hamburger button triggers a full screen overlay menu containing the navigation links to all pages on my website. The user can click the links to navigate to the relevant webpage.
- **Social media links** - Each link opens a new page with the relevant social media page for the band (Facebook, Twitter and YouTube). These links make it easy for users to access the band's social media profiles from one place. The social media profiles load in a new tab, which allows users to then return to the site.
- **Full screen overlay menu** - The full screen overlay menu contains navigation links which redirect the user to the different pages of my website. The social media links are displayed in the top right hand corner of medium to extra large screens.
- **Navigation links** - Allows users to navigate around my website by clicking each navigation link, which redirects them to the relevant webpage.

#### All Pages (exluding index.html)

- **Return to top link** - This is located at the bottom the webpage, just above the footer. It allows users to return to the top of the page by clicking the link.
- **Footer 'Sign Up!' call to action button** - This is a button which users are able to click, and it allows them to then complete further steps to sign up for the band's newsletter. This is displayed in the centre of the footer, above the social media links on extra small and small screens. It is displayed to the left in the footer on medium to extra large screens.
- **Footer social links** - These have the same function as the social media links in the navigation bar/header. They are displayed in the centre of the footer, below the 'Sign Up!' call to action buttion on extra small and small screens. They are displayed to the right in the footer on medium to extra large screens.

#### band.html

- **Band member cards and links** - Each band member's picture and information is displayed in a card. Each card has a scroll bar, which allows users to scroll through and read all the information contained within the card. Users can then click the 'Find out more...' link, which opens the Wikipedia page for the relevant band member in a new browser tab.
- **Carousel with indicators and controls** - The carousel contains four pictures of the band, which slide automatically. Alternatively, users can use the controls to manually slide forwards or backwards through the images. The indicators allow users to see which image of the series they are viewing.
- **Band history link** - The 'Find out more...' link at the bottom of the *'Band History'* section allows users to find out more about the band. Clicking the link opens the band's Wikipedia page in a new browser tab. 

#### music.html

- **Discography timeline links** - Each album name is a link. These links allow users to find out more about the albums by opening the Wikipedia page for the relevant album in a new browser tab.
- **Spinning music discs** - This is purely visual and gives users a sense that music is playing. These discs constantly spin though, which is due to a limitation as I haven't yet learned JavaScript to make them start and stop spinning when certain actions are completed.
- **iframes** - The iframe embeds contains two of the band's albums on Spotify. Users can click each of the songs and listen to a 30 second preview of them. They are then redirected to the Spotify album page to either log in or sign up.
- **Spotify 'Follow' widget** - Allows users to click the 'Follow' button to follow the band on Spotify. If the user isn't signed in to Spotify, clicking the button opens a new window that allows users to login to their Spotify profile to then follow the band.
- **Audio tracks with controls** - Allows users to listen to the relevant track using the controls. Users can also download an mp3 copy of the track to their local drive on a desktop by using the controls.
- **Video with controls** - Allows users to watch the video using the controls. Users can watch the video on full-screen, and they can also download a copy of the video to their local drive on a desktop by using the controls.

#### tickets.html

- **'Book Now' call to action button** - This is a button which users are able to click, and it allows them to then complete further steps to receive instructions on how to finalise their ticket booking.
- **Modal with built in form and submit button** - The modal is triggered by the 'Book Now' call to action button, and allows users to complete a form and submit their details to receive instructions on how to finalise their ticket booking. Each of the form's fields are required. Currently, no further action is taken when the 'Submit' button is clicked - this is a limitation due to the scope of the project.
- **'Limited availability' alert** - This is a banner above the 'Book Now' button that alerts the user to the fact that there is limited ticket availability for that particular concert.
- **'Sold Out' disabled button** - This button allows the user to see that the particular concert is sold out. The button is disabled and is for information purposes only.

#### contact.html

- **Form with submit button** - Allows users to book the band to perform at their events by completing the form and submitting their details. Currently, no further action is taken when the 'Submit' button is clicked - this is a limitation due to the scope of the project.
- **Form dropdowns** - Some of the form's input fields have dropdowns, which allows users to select the relevant option from a list of options.
- **Form date selector** - Allows users to choose the desired date that they want to book the band by clicking the date selector icon, which displays a calendar. 
- **Form number input field with min and max range** - Allows users to input the number of attendants to the event by either typing the number directly into the input field, or by using the higher or lower selectors. This field has a minimum value of 20 and a maximum value of 999999999.

### Features Left to Implement

Once I've learnt JavaScript and back-end web development, I will add further functionality to the existing features on my website.

- **'Sign Up!' modal action** - I will add further functionality to the 'Submit' button so that it displays an on-screen 'Thank you' message. I will also add functionality for an email to be sent to users to confirm that they have successfully signed up for the band's newsletter.
- **Hamburger button** - I will add functionality for the burger button to change to a 'X' icon once the full screen overlay menu is triggered and displayed.
- **Full screen overlay menu** - I will improve the display and functionality of the full screen overlay menu, which will in turn reduce the amount of CSS code that I've had to use instead.
- **Spinning music discs** - I will add functionality to these discs so that they are triggered to spin when the user plays the music within the relevant iframe, and they will stop spinning when the music is stopped.
- **Audio and video controls** - I will add custom styles to the existing audio and video controls so that they also reflect the brand of the band and the theme of the website, and so that they appear the same in all browsers.
- **'Book Now' modal action** - I will add further functionality to the 'Submit' button so that it displays an on-screen 'Thank you' message. I will also add functionality for an email to be sent to users with further instructions to complete the ticket booking process.
- **'Limited availability' alert** - I will add functionality to the 'Limited availability' alert so that it is only displayed when there is a limited availability of tickets for that particular concert.
- **'Sold Out' disabled button** - I will add functionality to the 'Sold Out' button so that it is only displayed when the particular concert is sold out. This will require the 'Book Now' button to change to a 'Sold Out' button in this event.
- **Form with submit button on contact.html page** - I will add functionality to the 'Submit' button so that it displays an on-screen 'Thanks for booking us!' message. I will also add functionality for an email to be sent to users to confirm that they have booked the band for their event.
- **Form date selector** - I will add functionality to the date selector icon to change it to a calendar icon. I will also add my custom styles to the calendar and improve the fuctionality so that it greys out any dates that have already been booked, or when the band is unavailable.

## Technologies Used

- [**Balsamiq**](https://balsamiq.com/)
    - I've used **Balsamiq** to create wireframes of my website before building the actual site.
- [**HTML5**](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5)
    - The project uses **HTML5** to create the basic elements and content of my website.
- [**CSS3**](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS3)
    - The project uses **CSS3** to add custom styles to the elements and content of my website.
- [**Bootstrap v4.3**](https://getbootstrap.com/)
    - The project uses **Bootstrap v4.3** to add a responsive grid system, prebuilt components, plugins built on jQuery, and Bootstrap styles to my website, before adding my custom styles.
- [**jQuery**](https://jquery.com)
    - The project uses **jQuery** to simplify DOM manipulation. This is the standard jQuery that is built with Bootstrap components.
- [**JavaScript**](https://www.javascript.com/)
    - The project uses **JavaScript** from Bootstrap which is required to add functionality to some of Bootstrap's components.
- [**Google Fonts**](https://fonts.google.com/)
    - The project uses **Google Fonts** to style the text and suit the style of the band.
- [**Font Awesome**](https://fontawesome.com/)
    - The project uses **Font Awesome** for the social media links and the hamburger button on my website.
- [**Cloud9**](https://c9.io/login)
    - I've used **Cloud9** as the development environment to write the code for my website.
- [**Git**](https://git-scm.com/)
    - I've used **Git** as a version control system to regularly add and commit changes made to project in Cloud9, before pushing them to GitHub.
- [**GitHub**](https://github.com/)
    - I've used **GitHub** as a remote repository to push and store the committed changes to my project from Git. I've also used GitHub pages to deploy my website in a live environment.

## Testing

### Testing User Stories

I used my user stories and documented each of the steps that each user would need to accomplish what they have stated. Below is the link to the document that contains this information:

- [Testing User Stories](https://github.com/hebs87/monkees-milestone-project-one/blob/master/testing-documents/testing-user-stories.pdf)

### Responsive Testing

I used Google Chrome's Development tools to constantly test each change that I made to my website and to ensure that it appeared in the desired way on different screen sizes. I also tested my website on different screen sizes (mobile, tablet and desktop) to ensure it appeared in the desired way on different devices.

To test my whole website, I went through each page, feature by feature, and documented the results on a spreadsheet. The spreadsheet also documents any responsive features and confirms that they work and appear as intended on different screen sizes. The link to the spreadsheet it below:

- [Testing Checklist](https://github.com/hebs87/monkees-milestone-project-one/blob/master/testing-documents/testing-checklist.pdf)

### HTML and CSS Validation

I used the [W3C HTML Validator tool](https://validator.w3.org/#validate_by_input) to validate my HTML code.

I used the [W3C CSS Validator tool](https://jigsaw.w3.org/css-validator/#validate_by_input) to validate my CSS code.

### Interesting Bugs or Problems

- **Burger icon** - The burger icon wasn't appearing once the fullscreen overlay menu was triggered. The reason for this is that the header in which the burger icon was in had a lower z-index than the overlay menu. To fix the issue, I gave the header a higher z-index value than the overlay menu.
- **Burger icon when overlay menu is triggered** - As the header (including the burger icon) is part of the page, it disappears when the user scrolls down while the overlay menu is triggered. The user then has to scroll back to the top of the page for the burger icon to reappear while the overlay menu is triggered. This is another constraint, and I will fix this bug when I learn JavaScript, so that the header remains fixed, only when the overlay menu is triggered.
- **Band card images** - The images automatically take up 100% of the card width, so they appear stretched. I have tried to make the images take up less of the card width, but this throws the alignment out, and it doesn't look as tidy with the scroll bars. This is a constraint and I've decided to leave the images as they are.
- **'dates' attribute** - For the discography timeline, I used the sample code from the code used within the Resume mini project. The sample code used the `dates` attribute. However, the [W3C HTML Validator tool](https://validator.w3.org/#validate_by_input) stated that this was invalid. When I looked on Slack, I saw that another student had the same issue, and the advice they received was to use the `data-year` attribute instead. I tried this and it resolved the issue.
- **'Submit' button on *Book Us* form** - Once I entered the information and submitted the form, the form kept routing me through to the index.html page. After speaking with my mentor, he asked me to check the value of the `action` attribute of the `<form>` element. The issue was that the value I was using was `action="/"`. Once I changed this to `action="contact.html"` the issue was resolved.
- **'Submit' button on *Book Us* form** - Once I entered the information and submitted the form, I kept getting a '405 Not Allowed' error message, but this was only happening in the live environment and not the testing environment. I posted this in the Slack community and was given the advice to change the `method` value to `get` instead of `post`. This resolved the error.

## Deployment

The hosting platform that I've used for my project is GitHub Pages. To deploy my website to GitHub pages, I used the following steps:

1. Loaded the terminal window in my Cloud9 workspace.
2. Initialised Git using the `git init` command.
3. Added all files to the Staging area (Git) using the `git add .` command.
4. Committed the files to Git using the `git commit -m "Initial commit"` command.
5. Created a new repository in GitHub called 'monkees-milestone-project-one'.
6. Copied the below code from GitHub into the terminal window in my Cloud9 workspace:

    ```git remote add origin https://github.com/hebs87/monkees-milestone-project-one.git```

    ```git push -u origin master```

7. Entered my GitHub username and password to push the files from Git to GitHub.
8. Went into 'Settings' on my repository page in GitHub.
9. Selected the 'master branch' option under the 'GitHub Pages' section.
10. Ran several regular commits throughout my project.

### Repository Link

https://hebs87.github.io/monkees-milestone-project-one/

### Running Code Locally

To run my code locally, users can download a local copy of my code to their desktop by completing the following steps:

1. Go to [my GitHub repository](https://github.com/hebs87/monkees-milestone-project-one.git).
2. Click on 'Clone or download'.
3. Click on 'Download ZIP'.
4. Once dowloaded, extract the zip file's contents and run my website locally.

## Credits

### Content

- The text for Davy Jones' band card was copied from [Davy Jones' Wikipedia page](https://en.wikipedia.org/wiki/Davy_Jones_(musician)).
- The text for Micky Dolenz's band card was copied from [Micky Dolenz's Wikipedia page](https://en.wikipedia.org/wiki/Micky_Dolenz).
- The text for Michael Nesmith's band card was copied from [Michael Nesmith's Wikipedia page](https://en.wikipedia.org/wiki/Michael_Nesmith).
- The text for Peter Tork's band card was copied from [Peter Tork's Wikipedia page](https://en.wikipedia.org/wiki/Peter_Tork).
- The text for the 'Band History' section and the discography information was copied from [The Monkees' Wikipedia page](https://en.wikipedia.org/wiki/The_Monkees).

### Media
- The photos used in this site were obtained either from the assets provided with the course content, or from Google images. I made sure any Google images were "free to use or share, even commercially".
- The audio tracks used in this site were obtained from the assets provided with the course content.
- The video track used in this site was obtained from the assets provided with the course content.
- The link for the iframe content for the *'Monkeemania: The Very Best Of The Monkees'* album was obtained from [the album's Spotify page](https://open.spotify.com/album/1mOeF3Ew1vdmJLbGOG2CuP).
- The link for the iframe content for the *'Monkees Greatest Hits'* album was obtained from [the album's Spotify page](https://open.spotify.com/playlist/7mbzl6fkxbayOw7OwjDMHG).
- The follow button embed code was obtained from [the band's Spotify page](https://open.spotify.com/artist/320EPCSEezHt1rtbfwH6Ck).

### Acknowledgements

- I received inspiration for the full screen overlay menu when I was looking at websites for other bands. I came across the website for the band called [The Specials](https://www.thespecials.com/) and wanted to incorporate a similar menu in my project.
- I received inspiration for the spinning music discs from my fiancee. When she looked at my website, she suggested this as some sylistic feedback.
- Thanks to the Slack community to help me to fix an error with the `dates` attribute in the discography timeline, and to help me to fix the error with the Book Us form on the contacct.html page.
- A special mention to my mentor, Dick Vlaanderen, for his feedback on my project's scope and design, and for hints on what information to include in my README.md file to justify my stylistic choices.