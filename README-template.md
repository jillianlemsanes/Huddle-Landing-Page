# Frontend Mentor - Huddle landing page with curved sections solution

This is a solution to the [Huddle landing page with curved sections challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/huddle-landing-page-with-curved-sections-5ca5ecd01e82137ec91a50f2). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

This project was completed to test my CSS skills. All of the coding is my work but the designs and project idea came from Frontend Mentor. This project uses HTML and CSS only. 

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

-Mobile View Screenshot

/images/mobile-screenshot.png

-Desktop View Screenshot 

/images/desktop-screenshot.png
### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)
## My process

- I viewed the desktop and mobile designs to get an idea of what HTML markup I need to layout. 

- I did some research on a few things I knew I would need to use in this project but was not comfortable with (row-reverse, these type of background images)


 - I started with a desktop first HTML markup. I completed the project this way so that the complicated desktop designs would be laid out in HTML first. You want to account for the more complex layouts of the desktop view with HTMl.
 
 - Since mobile first is the easier layout and design, I styled my CSS with mobile first. I chose to do mobile first CSS because once I get to desktop, there was much less I had to style with CSS. Styling simple designs to the more complex works best with CSS.
### Built with

- Semantic HTML5 markup
- Flexbox
- Mobile-first workflow
- Font Awesome Icons
- Google Fonts


### What I learned

1. SVG images can be styled. This was a completely new thing to me. I ran into this when I was needing to insert an all-white version of the "Huddle logo" into the footer section. I styled the SVG inside the actual svg file, however I believe you can also style in in the CSS style page. I simply created a copy of the Huddle logo, re-named it to "logo-footer" and styled away. 

2. I was under the impression that the wavy background images were one giant background image. I was thinking the whole thing was just one background image that you insert behind the section you need it and you are good to go. Definitely did not work like that, as I quickly realized that the background images were literally just the edges of the curvy background. 

    -I ended up putting the top and bottom edge of the curvy backgrounds onto the various "backgrnd-img 1, 2, or 3" classes. These typically fell into the container ABOVE  or BELOW where the background was supposed to be, and then I would use a "bckgrnd-color" class to change the desired container background. In sum, I had to use to seperate sections to achieve the look needed for one section. Had no idea this project was going to use so much styling to get those background images to look correct. 

3. You can set multiple background images to one container, and how to move their positions. I learned a lot of CSS styling with background images froom this project. 

### Continued development

1. I would like to learn more about styling SVG images, and how to style the SVGs in the CSS style sheets instead of in the SVG file.
2. I want to practice using custom CSS, as I have seen it several times but have never used it myself. 
3. I want to keep working on my semantic HTML. I felt more comfortable with it in this project but I still have a lot to learn about it.
4. Next, I will try a project with CSS grid. I learned about grid but I've never used it in a project and I think it will be extremely helpful to know and level up my CSS skills even more. 


### Useful resources

- [Font Awesome](https://fontawesome.com/)- I used this to obtain the social media logos, there are a lot of sites you can use but I used this one for my project. 
- [CSS Tricks Flex Direction](https://css-tricks.com/almanac/properties/f/flex-direction/) - Some of the sections in the design between mobile and desktop were switching the order of the image and text. I used this resource to figure out how to get the look I needed using flex-direction: row-reverse. 

## Author

- Frontend Mentor - [@jillianlemsanes](https://www.frontendmentor.io/profile/jillianlemsanes)
- GitHub - [@jillianlemsanes](https://github.com/jillianlemsanes)


