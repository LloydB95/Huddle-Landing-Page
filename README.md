# Frontend Mentor - Huddle landing page with single introductory section solution

This is a solution to the [Huddle landing page with single introductory section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/huddle-landing-page-with-a-single-introductory-section-B_2Wvxgi0). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the page depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

![](./screenshot.jpg)

### Links

- Solution URL: [https://www.frontendmentor.io/solutions/huddle-landing-page-with-a-single-introductory-section-eU1nZ3kEOQ](https://www.frontendmentor.io/solutions/huddle-landing-page-with-a-single-introductory-section-eU1nZ3kEOQ)
- Live Site URL: [https://lloydb95.github.io/Huddle-Landing-Page/](https://lloydb95.github.io/Huddle-Landing-Page/)

## My process

### Built with

- Semantic HTML5 markup
- Tailwind CSS
- Flexbox
- Mobile-first workflow
- [Font Awesome](https://fontawesome.com/) - For Icons

### What I learned

I had learned how to create a landing page for a website. This allowed me to learn how to effectively space several items on a page and created a more challenging situation in which I had to significantly change the desktop and mobile versions of the site. 

The short code snippet below shows how I was able to differentiate the orientation of the website based on how it is viewed. **bg-mobile** allowed for it to pull the file for the mobile background while **md:bg-desktop**  meant that on a medium sized screen (In this case it was 1440px) it would display a seperate image.

```HTML
<body
    class="bg-mobile md:bg-desktop bg-violet flex md:justify-center md:items-center bg-no-repeat bg-cover h-screen w-screen">
    <div class="md:w-[1440px] px-8 md:mx-auto md:px-16 py-8">
```
All throughout this challenge I have learnt that using an **md** tag before a component is what helps the code to read and change the image based on the device that is viewing it.

### Continued development

I would like to continue to develop my skills regarding spacing and orientation and how to effectively use Tailwind CSS classes to cut down on excess code and how better to implement certain classes in certain situations e.g. Padding.

### Useful resources

- [Tailwind CSS - Padding](https://tailwindcss.com/docs/padding) - This gave me the classes I have used to pad out elements on the page, integral part of development.
- [Tailwind CSS - Max-Width](https://tailwindcss.com/docs/max-width) - Using this alongside the **md** tag helps to differentiate desktop and mobile. Also very helpful in sizing elements on the page effectively.

## Author

- Frontend Mentor - [@LloydB95](https://www.frontendmentor.io/profile/LloydB95)

## Acknowledgments

I have had a lot help with this challenge from a colleague with extensive knowledge on the subject.
