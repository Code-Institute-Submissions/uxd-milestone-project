
# Five Chambers Full Band Site

This project was created as part of my first Milestone project with the Code Institute. It is a static front-end site designed to raise awareness of a local covers band, promote upcoming gigs and boost their fan base.
I chose to base my project on Five Chambers Full as I wanted to gain experience interacting with clients as a Developer. The client is a local covers band that play Rock'n'Roll covers for people of all ages.

## UX

Prior to beginning the design process I met with Kiran and Mike from the band and we discussed what it was they wanted from the site. 
At the end of the meeting we confirmed that the purpose of the site was _**to raise awareness of the band by creating a space for fans 
to find out more about the band, when the next gigs are and increase the number of bookings the band recieves.**_
From information gatered at the meeting I put together a list of the following potential features:
* About us
* Gig guide
* Gallery
* Social Links
* Contact form
* Mailing list
* Booking availability calendar

To decide which features would be used in the site I used the Viability vs Feasability method, this testing can be found 
[here](https://docs.google.com/spreadsheets/d/15Kd2izYh5g3eZcMRsQOElHK1Wpi76QsAB0gfZKWu40E/edit?usp=sharing). As a result of this testing I decided the features
that would be included in the MVP would be: About Us, Gig guide, Gallery, Social links and a contact form / page. 

Once the features were decided on I started drawing out some potential designs and created a couple of wireframes to show how the landing page would be designed on both mobile and desktop views, these can be viewed 
[here](https://drive.google.com/file/d/16mY4uHhNf7jNLX5V9ao5824xkeh7Hcx8/view?usp=sharing). The color scheme of the site was originaly to be grayscale with accents of blue, this was to match the bands black and white logo.
During my project planning session with my mentor they advised against the grayscale scheme and so I used the 
[Adobe Color Wheel](https://color.adobe.com/create/color-wheel/)
to create the [colour palette](https://drive.google.com/file/d/1hGC-_FSpgQxzIq6pKxmNUD9cpNVQfvIP/view?usp=sharing) used throughout the project, the central blue `#7de3ff` is the colour I had originally chosen to use as an accent colour.



### User Stories:

Below are a list of the users stories throughout the project.

* As a user, I want a gigs list, so I can find out when and where the band are playing next.
* As a user I want to find the bands social media pages so that I can keep up to date with the latest news about the band.
* As a user, I would like to contact the band so that I can book them for an event.
* As a user, I want to find out more about the band members so I can decide if their music tastes are for me.


## Features

Here are a list of features that have been implimented as well as additional features that could be added in the future to improve the users experience.

### Existing Features:

* **Collapsable Nav** - The collapsable `nav` allows users to easily navigate the site on mobile devices easily, it is a common feature used in most responsive sites 
and so I included it in my project to ensure user expectations were met.

* **Hero-Image** - This feature was designed to call attention to the gigs list user story. 
It allows users to get to the Gigs page in one click even on mobile devices when the `nav` is collapsed. 

* **Gigs** - The gigs page itself is an interactive table that allows you to show/hide additional info about the selected event. During testing in earlier versions of the site
some users did not realise that they were able to click on the table to show the `.more-info` rows. To resolve this issue I used the Font Awesome down arrow icon to tell users 
that more information can be seen by clicking the Venue name.

* **Social Links** - The social links in the footer of each page allow users to easily find links to the bands social pages from any page of the site.

* **About** - The About the band feature allows users to get an understanding of who's who within the band and get a glimpse of the big personalities behing the music.

* **Gallery** - The gallery page allows users to get an idea of what to expect if they were to attend one of the bands gigs. The gallery itself is responsive to different 
screesn sizes and was originally intended to include 10 images taken at one of the bands recent Gigs, unfortunatley the images provided by the band were all different sizes. 
Due to time constraints I decided to choose 8 simarly sized images and use these for the purpose of the project. 

* **Contact** - The contact page allows users to easily contact the band for any reason without having to share the bands personal details online. 
I originally planned for the background of the contact page to be white as it is in the preceeding three pages. During my mid-project planning session my mentor
said the page felt a little empty on larger screen sizes. To rectify this I decided to re-use some of the code from the `.hero-image` in the `header` of index.html. 
This allowed me to quickly and easily add a background image of the band to the contact page with minimal changes to the code.

### Features to impliment / Improvements to make:

* **Collapsable Nav** - The drop down on the collapsable `nav` does not cover the entire screen width. This is something I would like to have resolved prior to submission but
I was unable to. In addition to this I had planned to use the Band's Logo in the `navbar` in the `navbar-brand` section. The background for the image the band provided was 
unfortunatley coloured white rather than having a colourless background. This caused the logo to have a white box around it on the blue background of the navbar.
I could have edited the photo and used the logo but I decided to instead remove the logo for the MVP, replacing it with the band name as seen in the finished project.

* **Social Links** - In the future I would like to add more CSS styling to the Social links to include a hover animation.

* **Contact** - Upon testing the site across different screen sizes I discovered the `contact-form` container overflows onto the footer of the page on xs screens. In future versions of the site I would like resolve this issue.

* **Availability Calendar** - This feature was cut from the original MVP during the Viability vs Feasability testing carried out earleir in the design process. 
I would quite like to add this feature into later versions of the site as I feel it will really help to increase the number of bookings the band will recieve. 
However at this point in the course and with the focus of the project being a static site i felt it was best to spend more time on other features.

## Technologies Used

* **HTML5**

* **CSS3**

* **Bootstrap** - I chose to use the [Bootstrap CDN](https://getbootstrap.com/docs/4.4/getting-started/introduction/) to create the general layout 
and styling of the pages. This allowed me to quickly put together the overall design quickly which in turn allowed me more time to 
enhance the site using CSS. Both the CSS and JS links were included in the site as the collapsable `nav` component uses JavaScript to function.

* **Font Awesome** - I chose to use [Font Awesome](https://fontawesome.com/) for the icons across the site as they provide a large range of free to 
use icons that I have used prevously and so know they will work correctly.

* **Chrome DevTools** - I used Chrome's built in Dev Tools throught the project to inspect individual components and make CSS changes live on the screen prior to copying them into `style.css`.


## Testing

To Check my code I used the W3 Schools' [HTML Validator](https://validator.w3.org/) and [CSS validator](https://jigsaw.w3.org/css-validator/). 
The results from these checks can be seen here: [HTML](https://drive.google.com/open?id=1_SW4XNozTrInPzfWJ6HCXvin4LjjUG93), [CSS](https://drive.google.com/open?id=1_SW4XNozTrInPzfWJ6HCXvin4LjjUG93)

In addition to the above automated tests I carried out manual testing of the site using Chrome's dev tools. This testing was to ensure not only that the views correctly across different viewports. During this stage of testing I opened each page of the site and checked how it would view on each devise type and then used the responsive mode 
to adjust the site to non-standard screen sizes to ensure it still displayed correctly.

After deploying my project I sent the url to the site to varoius test users who checked how the page displayed in browser on different devices.
It was during this testing phase that I discovered I hadn't put `required` at the end of my `<input>` tags in my `.contact-form`. 
I corrected this error in the code and also added the names to each input. I then tested the page again myself by trying to click the send button 
without the required fields being filled out and the error messages all displayed correctly.

Some erros discovered by testing have been mentioned in the Features section above, this is because I was testing the site multiple times after adding 
each feature and so made changes as I went along rather than having one test phase at the end.

## Deployment

I chose to deploy my project using [GitHub Pages](https://pages.github.com/). I deployed the site quite early on in the project to allow for the testing mentioned above.
When I first deployed the site there was an issue with importing the `style.css` document and so only the bootstrap styling was viewable. Upon investigation
it was the way I had written the `href` link for the style sheet. Originally I had used `href="../assets/css/style.css"` to link to the sytle sheet and this worked
when viewing the site locally so I missed my error. I resolved the issue by removing the `../` at the start of the `href`. 

I had no other issues with the deployment of my site.

## Credits


### Content:
*The content for the project was provided by Five Chambers Full.*

### Media:
*All images used across the project were obtained from Five Chambers Full.*

### Acknowledgments:
*The inspiration for this project came from Five Chambers Full.*