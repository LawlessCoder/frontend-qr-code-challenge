# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Frontend Mentor - QR code component solution](#frontend-mentor---qr-code-component-solution)
  - [Table of contents](#table-of-contents)
  - [Overview](#overview)
    - [Screenshot](#screenshot)
    - [Links](#links)
  - [My process](#my-process)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)
    - [Continued development](#continued-development)
    - [Useful resources](#useful-resources)

## Overview

This is my submission for the first project in my Frontend Mentor journey. A major factor for choosing this project (and Frontend Mentor as a whole) was my desire to manipulate the style of my notes and UI in the Obsidian app using HTML and CSS (maybe one day making my own theme for the app). Thus, I am excited to begin learning HTML and CSS, and I hope to learn more in the projects to come!  

### Screenshot

![QR Code Site - Desktop Version](./screenshot.png)

### Links

- Solution URL: [Frontend Mentor Solution](https://www.frontendmentor.io/solutions/qr-code-challenge-using-flexbox-and-mobile-first-design-3Q68jK3St3)
- Live Site URL: [Add live site URL here](https://lawlesscoder.github.io/frontend-qr-code-challenge/)

## My process

I began this challenge installing Figma and interacting with the provided `.fig` file. This was a fun experience for me because I got to utilize a common tool in designing user interfaces and user experiences. Next, I began researching HTML and CSS, taking notes on syntax, common practices, and how both languages relate to web development. Since I was already familiar with Markdown, HTML was a nice demonstration of other uses of markup languages.

After learning just enough about HTML and CSS to dip my toe into the challenge, I moved onto working on the project. I started with laying out the content in my `index.html` file. I decided to group the main content (the QR code image and the text beneath the QR code) into its own container to (hopefully) make life easier in the land of CSS. Then, I transitioned to writing CSS code for each element. Once a ruleset was defined for each element, I worked towards ensuring the design stayed consistent as the viewport changed.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow 

**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

I learned many, many lessons from this initial project. First and foremost, I learned about the flexbox layout method. I utilized the flexbox in my design to display my elements in a vertical arrangement/in one column since this is ideal for the mobile experience. Immediately I was happy with the results.

```CSS
.content {
    background-color: hsl(0, 0%, 100%);
    box-shadow: 0 1.5625rem 1.5625rem hsl(0, 0%, 0%, 4.77%);
    display: flex;
    flex-direction: column;
    ...
}
```

Second, I learned how useful a Figma file is during the design process. I utilized this project's `.fig` file to observe how the dimensions of elements changed between the mobile and desktop experiences, the color and blur of the box-shadow, and the font weights of the font elements.

Third, I learned the difference between `px`, `em`, and `rem` and when to use each unit. I originally started with `px` and found that using the absolute unit reduced the flexibility of the website's elements. I switched to `rem` because it improves accessibility and makes the site dynamic. 


### Continued development

For starters, I would like to become familiar with best HTML and CSS practices when creating a frontend product. One aspect I struggled with during this exercise was naming and assigning classes in HTML and utilizing said classes in CSS. I decided to group my elements in containers based on their relationship to one another, and then assigned a class to the container. Each element within the container was manipulated in CSS using the class name followed by the element type, like so:

```CSS
.content img {
  margin: 25px;
  border-radius: 25px;
  width: 500px;
}
```

An alternative approach could have been assigning a specific class to the image element and selecting that class in CSS. I am unsure which is a better practice. I imagine there are use cases and pros and cons for both methods.

Another area I would like to delve into is dynamically positioning elements. I stumbled upon the flexbox layout while learning CSS for this activity, and I found it useful for placing my main group of elements on the webpage. I read about grid versus flexbox and think I have a better understanding of when to use both. I would like more experience using both types of layouts.

### Useful resources

- [Khan Academy: Introduction to HTML/CSS](https://www.khanacademy.org/computing/computer-programming/html-css) - This helped me with learning the basics of HTML and CSS. I liked the live editing and display as well as the content. Note, however, that the tutorial is a bit dated.
- [YouTube CSS/3 Full Tutorial - Playlist](https://www.youtube.com/watch?v=FFOQRK1K7N0&list=PL7TLF4T4Tq2RCWa-ZRkEWXVtXteyZ2CjK) - I stumbled upon this series of videos while looking for some CSS tutorials. I liked the examples in each video.
- [YouTube Learn Flexbox CSS in 8 minutes](https://www.youtube.com/watch?v=phWxA89Dy94) - Another YouTube video I landed on while falling down the CSS rabbithole. This one is a quick video (< 10min) about flexbox.
- [px vs rem](https://www.joshwcomeau.com/css/surprising-truth-about-pixels-and-accessibility/) - A very useful page for understanding common CSS units (px, em, rem) and when to apply them.

