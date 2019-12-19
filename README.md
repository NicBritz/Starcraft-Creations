# Starcraft Creations - Milestone Project 1

<!-- contents -->

## Contents

- [Overview](#Overview)
- [UX](#UX)
  - [Standard Customer](#Standard-Customer)
  - [Professional Customer](#Professional-Customer)
  - [Starcraft Creations](#Starcraft-Creations)
- [Wireframes](#Wireframes)
- [Features](#Features)
- [Technologies Used](#Technologies-Used)
  - [Tools for the job](#Tools-for-the-job)
- [Testing](#Testing)
- [Deployment](#Deployment)
- [Credits](#Credits)
  - [Content](#Content)
  - [Acknowledgements](#Acknowledgements)

<!-- overview -->

## Overview

### Milestone One Project 

I created a website for an imaginary 3D printing company that I called Starcraft Creations, the back story for the company is as follows:

Starcraft Creations is a prestigious company with an impeccable track record. A company that holds its standards very high and takes care of their customers.

They produce both original and custom-designed 3D printed items and they wanted a website that reflects the quality of their work, something they could be proud of.

That is why I have created this site as clean and responsive as possible, the overall goal is for the company to sell its services to customers.

<!-- Top -->

<div align="center">

[Top](#Contents)

</div>

<!-- ux -->

## UX

### User stories

##### Standard Customer

- For a standard customer, I wanted to give the impression of a professional website that was easy to navigate. I also needed it to have as much of the important information but without making the website look too busy or too cluttered.

##### Professional Customer

- As a professional engineering company would typically know exactly what they need I wanted it to be fast to get to the quoting stage. I also needed to make the quoting form ask for as little information as possible but still get everything needed to get a quote out. Keeping the landing page clean portrays a neat company and the catchphrase 'Parts printed in as little as 1 working day!' helps to show that the company is fast and efficient.

##### Starcraft Creations

- For Starcraft Creations I wanted to create a website that portrays a professional-grade 3d printing service. It needed to be clean and neat and have only the content that was relevant to the company. It also needed to be fully responsive as most users would be using the site on mobile devices. This is why I took the mobile-first approach during development. As the ultimate goal is to get business into the company the landing page had to access the quoting form. 

<!-- Top -->
<!-- wireframes -->

### Wireframes

These are my wireframes I created during the design process, they were great as a guide to get started. Here you can also find the original [Balsamiq Mockup](/wireframes/) file. I did deviate from this slightly as once it was all working it was looking a bit bland but it was very helpful to have a structure and an idea in place form the beginning. Overall, the concept stayed the same.

<div align="center">

**Home - PC**

<img src="/wireframes/PC/Home%20-%20PC.png" alt="home screen wireframe for pc" width="512" height="357">

**About - PC**

<img src="/wireframes/PC/About%20-%20PC.png" alt="about screen wireframe for pc" width="512" height="357">

**Products - PC**

<img src="/wireframes/PC/Products%20-%20PC.png" alt="products screen wireframe for pc" width="512" height="357">

**Contact - PC**

<!-- Top -->

<div align="center">

[Top](#Contents)

</div>

<img src="/wireframes/PC/Contact%20-%20PC.png" alt="contact screen wireframe for pc" width="512" height="357">

**Home - iPad**

<img src="/wireframes/iPad/Home%20-%20iPad.png" alt="home screen wireframe for ipad" width="308" height="458">

**About - iPad**

<img src="/wireframes/iPad/About%20-%20iPad.png" alt="about screen wireframe for ipad" width="308" height="458">

**Products - iPad**

<img src="/wireframes/iPad/Products%20-%20iPad.png" alt="products screen wireframe for ipad" width="308" height="458">

**Contact - iPad**

<!-- Top -->

<div align="center">

[Top](#Contents)

</div>

<img src="/wireframes/iPad/Contact%20-%20iPad.png" alt="contact screen wireframe for ipad" width="308" height="458">

**Home - iPhone**

<img src="/wireframes/iPhone/Home%20-%20iPhone.png" alt="home screen wireframe for iphone" width="217" height="433">

**About - iPhone**

<img src="/wireframes/iPhone/About%20-%20iPhone.png" alt="about screen wireframe for iphone" width="217" height="433">

**Products - iPhone**

<img src="/wireframes/iPhone/Products%20-%20iPhone.png" alt="products screen wireframe for iphone" width="217" height="433">

**Contact - iPhone**

<img src="/wireframes/iPhone/Contact%20-%20iPhone.png" alt="products screen wireframe for iphone" width="217" height="433">

</div>

<div align="center">

[Top](#Contents)

</div>

<!-- features -->

## Features

<!-- Top -->
**General**

I used a color pallet generated form the large image on the landing page using https://color.adobe.com/create and this font https://fonts.google.com/specimen/Source+Sans+Pro from google fonts.
This gave my website a clear text and a color scheme that looked good with the content.

**Logo**

I have taken care to ensure that the logo is as responsive as possible, keeping the spacing and size looking neat in as many screen sizes as possible. 
I also made sure to use the orange in the logo throughout the website as this is the company's brand colour.

**Navigation Bar**

The navigation bar on the website incorporates some icons to give the menus some visual cues. 
I have also made it so that the active menu item is underlined to help indicate where you are currently at on the page. I used some JavaScript here too to help make it have smooth scrolling, you can find a reference to that in the credits section.

**Landing Page**

I have a clean image that immediately conveys what that the company does on the landing page. 
I also included some text to reiterate the service the company offers. From the landing page, I also made it so that you can request a quote without having to navigate anywhere else.
  
**About section**

When I created the 'About Us' section, I made use of Bootstrap's card component. This helped to structure the content neatly and in an organized way. I tried to keep this as simple and informative as possible with some visual styling to that is aesthetically pleasing.

**Services Section**

I tried to make this part of the site as informative as possible to the services the company would offer also allowing for the user to be able to request a quote at any point on the page. This also has some big pictures to give potential customers a visual representation of the type of product you could expect.

**Testimonials**

I wanted to incorporate a testimonials section on the site so that first-time customers could have an idea of the kind of service they could expect from a company like Starcraft Creations. 

**Team**

The team section was a late addition to give the website a more personal feel. I created the elements in this section to be round as I did not want to site to be too 'square'. I added some names and titles so that customers could feel like they know the team.

**Contact**

The contact page offers a map to the company and a simple form to get In touch in case you have any queries, you will also find the company address here. I have also created a popup modal for this that indicates that submission was successful although this is just a visual thing at the moment. 

**Footer**

The footer gives you a link to instantly create an email to the company and it will fill in the subject with some default text. there are also links to the various social media platforms in the footer all of which have some visual changes when hovered over. I have also made it so that external links open in a separate tab to keep users on the website using target="_blank".

**modals**

There is a quote modal that is built for you to create a request for a quote, this has another modal linked that will display that your request is successful, that way you can see that something has happened once you hit the submit button. There are dropdown lists and required fields here to make sure the user inputs valid information. 

### Features left to implement

It would be good to get some JavaScript running on the website, that way I can add some more things like doing something with the data that the user enters into the forms. Another feature I would like to implement is possibly some animation to the site, for instance to the testimonials scrolling through them or something like that.
<!-- Top -->

<div align="center">

[Top](#Contents)

</div>

<!-- technologies used -->

## Technologies Used

I used the following technologies to create this website:

1. HTML
2. CSS
3. [Bootstrap (4.4.0)](https://getbootstrap.com/)
4. [Google fonts](https://fonts.google.com/)
5. [Font Awesome (5.11.2)](https://fontawesome.com/)
6. [Git](https://git-scm.com/)
7. [Hover.css](https://ianlunn.github.io/Hover/)

### Tools for the job

Below is a list of tools I used to create this website.

- [Pycharm](https://www.jetbrains.com/pycharm/) - This is the IDE I used to start building the website.
- [Gimp](https://www.gimp.org/) - A free image editor I used to create and edit come of the site content.
- [Balsamq](https://balsamiq.com/) - All my wireframes were created in the desktop version of Balsamiq.
- [VS Code](https://code.visualstudio.com/) - Used this editor for building parts of the website.
- [Git Hub](https://github.com/) - Used this site to manage my projects storage as well as host the website.
- [Grammarly](https://www.grammarly.com/) Used to double-check all my spelling and grammar.
- [W3C Markup](https://validator.w3.org/) - used this to check my HTML for errors and typos.
- [W3C CSS](https://jigsaw.w3.org/css-validator/) - used this to check my CSS for errors.
- [Autoprefixer](https://autoprefixer.github.io/) - I used this tool to make sure I did not miss any prefixing in my code.

  <!-- Top -->

<div align="center">

[Top](#Contents)

</div>

<!-- testing -->

## Testing

I tested my code using [W3C Markup](https://validator.w3.org/) and [W3C CSS](https://jigsaw.w3.org/css-validator/) as a start to pick up any small errors in the code here I discovered that I had left out the alt test for some of my images as well as some stray div tags. 
Throughout the process, I would regularly test with these two tools to try to catch things early.

I tested the following features on multiple PC browsers (Chrome, Firefox, Edge) and Mobile devices (IOS, Android) and this is what I found:

### Navigation Bar
1. Test that this is responsive and collapses in the smaller screen sizes.
2. Test that the spacing between the menu items resizes on different screen sizes and that the logo does not overlap the menu items.
3. Test that the scroll to function is working on multiple devices and in multiple browsers.

It quickly became apparent that on the smaller devices I needed to collapse the menu and shit the logo up to abominate the smaller sizes. so I found I needed to implement media queries at this stage to have more control of this.
When the menu was expanded I also saw it looked odd on the smaller devices so I decided to centre the menu in the end. I was using a CSS scroll function and I realised it was not compatible in most browsers so I opted for a JavaScript solution in the end.

### Landing Image
1. Test that the image looks good on a wide range of screen sizes.
2. Test that the heading text and quote button will resize and is responsive.
3. Test that the modal opens and looks good on the smaller sizes. 

This gave me loads of trouble on the ios devices as it simply would not render the image on the physical device, 
after many hours of trial and error and finally found a stack overflow thread I realised that this was because of the image 
being fixed so I fixed this with a media query (Thanks stack overflow!) 
[Thread](https://stackoverflow.com/questions/36686654/fixed-background-images-disappear-on-iphone-ipad)

### About us 
1. Test that the link to the page is working as expected.
2. Test that the cards do not get too small switching between the different screen sizes.
3. Test that there is a clear definition between the heading text and the content of the cards.

After seeing this on a small device I realised there was not enough definition to the headings in the cards so I added underline and made the text uppercase.

### Services
1. Test that the link to the page is working as expected.
2. Test that the cards do not get too small switching between the different screen sizes.
3. Test that the buttons on each card works correctly and opens the modal as expected. 

This section was re-done multiple times as I had run into many little bugs when testing the buttons kept covering the text on the smaller screens. When the modal would pop up after clicking the button it would add strange padding to the background.
I spent a lot of time bug fixing and testing this on multiple screen sizes as its the main reason for this type of site.

### Testimonials
1. Test that the text is legible.
2. Test that the rating stars are responsive and remain a good distance from the testimonial text.

I originally had the testimonials in a horizontal line, after I changed the screen sizes and they looked off due to the different length of the text each one had. the solution, in the end, was to put them in a single verticle line. This made it look much better.

##Forms
1. Test the link to the contact form 
2. Test the quote button correctly opens the quote modal.
3. Test all the fields and dropdown menus
4. Test the submit button is working correctly.

### User testing
I believe this was the most important tests of all, I had some friends and family test the site and the feedback was invaluable. I think when you have been staring at the same site for weeks it is hard to see the little errors. 
They discovered Typos and grammar mistakes. 
One also suggested that I add the success modal to the submit button on the quote form as it felt like you were left hanging. hey spotted small spacing issues also. At that stage, a few commented on the Logo being too pixelated on their devices so I remade the logo at a higher resolution.

 <!-- Top -->

<div align="center">

[Top](#Contents)

</div>

<!-- Deployment -->

## Deployment

This site makes use of GitHub's technology for deployment. I have used GitHub pages to serve the site. The deployed version can be found here: https://frozenaught.github.io/Starcraft-Creations/, this relies on the [`index.html`](\index.html) file to make it work.
There is also a folder called `assets` that has sub-folders for the `CSS` and `images` that the website needs to work correctly.

For development, I created a repository https://github.com/Frozenaught/Starcraft-Creations.

If you want to run it locally you can follow the following steps:

- Use `git clone https://github.com/Frozenaught/Starcraft-Creations` to pull a copy of the repo to your computer.
- I would always recommend doing a git pull before starting any work on the project, this just ensures you are working on the latest version.
- Make any changes you need and commit using the command `git commit -m "your message` after staging the content with the command `git add "name of file"` of `git add .` for staging all files.
- You can push this to the remote using `git push`

- If there is anything you would not like to include in your commit I have made a [`.gitignore`](.gitignore) file, simply add the path to the file or folder and it will no longer show up if you run `git status`.
- I suggest regular commits as this will avoid big issues that are hard to reverse.
- You could also make use of a separate branch if you decide you want to experiment with things or don't want to work directly on the master branch. to do this use the `git checkout -b "branch name"` command.
- You could then switch back to the master branch using `git checkout master`

 <!-- Top -->

<div align="center">

[Top](#Contents)

</div>

<!-- Credits -->

## Credits


### Content

All content for this project is from the following sources.

- Images
  - [Cloudinary](https://cloudinary.com/) - I used this service to host some of my larger images as a CDN to make the site run faster.
  - [Pixabay](https://pixabay.com/) - This site is packed full of royalty-free images both free and paid.
- Text
  - [Simplfy3D](https://www.simplify3d.com/support/materials-guide/) - some of the more descriptive text was borrowed from this website.
  - Most of the test I made up.
- Code helpers
  - [Smooth Scroll](https://www.abeautifulsite.net/smoothly-scroll-to-an-element-without-a-jquery-plugin-2) - I used this code snippet to help with my smooth scrolling.
- Colours
    - [Adobe Color](https://color.adobe.com/create) - I used this tool to help with creating a colour scheme for the site.
- Logo
    - [Free Logo Design](https://www.freelogodesign.org/) - I used this to create the first version of the logo but I have since had to make a higher resolution version.
    
### Acknowledgements
**Notable sites**
I used these sites for reference along the development process.

- [Bootstrap Documentation](https://getbootstrap.com/docs/4.4/getting-started/introduction/) - For Bootstrap documentation.
- [CSS Tricks](https://css-tricks.com/) - For CSS documentation.
- [Can I Use](https://caniuse.com/) - For CSS decision making.
- [Google Maps](https://developers.google.com/maps/documentation/javascript/adding-a-google-map) - For google map integration.
- [Stack Overflow](https://stackoverflow.com/) - For those times when I cold not figure out why i was not getting the result i expected.


#### Gary Simons

To help guide me in the correct direction, I drew some inspiration from this project of his. As he was able to get a perfect score on his project, I figured I could learn from his work.
here you can find links to his [website](https://garysimons.github.io/One-Milestone-Project/) and [Github](https://github.com/GarySimons/One-Milestone-Project)

#### Haley Schafer

As Haley so kindly provided an example of a grade five project, I used her Portfolio project to help guide me.
Here you can find links to her [website](https://code-institute-solutions.github.io/StudentExampleProjectGradeFive/) and [Github](https://github.com/Code-Institute-Solutions/StudentExampleProjectGradeFive)

#### Lix Pen

I like the look and feel of the [Lix Pen website](https://lixpen.com/) and it helped to give me some inspiration during the design and implementation process.

#### Protolabs

I also liked the [Protolabs website](https://www.protolabs.co.uk/) and drew some inspiration from this site also.

#### Deed 3D
I used this site for some of my wording ideas and inspiration [Deed 3D](https://deed3d.com/) 
 <!-- Top -->

<div align="center">

[Top](#Contents)

</div>
