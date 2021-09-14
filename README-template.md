# Frontend Mentor - Clipboard landing page solution

This is a solution to the [Clipboard landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/clipboard-landing-page-5cc9bccd6c4c91111378ecb9). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process
I first edit the html file. Firstly, include all the images where they are required. Then Decide how to wrap the content into different divs. Which tag should be given to text.
Then in css, I declare all the colors as variables. Remove default margins and paddings and set them to zero.
Set each element's display to flex, flex-direction to column. I prefer Mobile-first development because it is usually all column layout.
Then, I work on fonts and colors.
Lastly on the alignment and spacing between elements.

Then I move to desktop development. Change the flex-direction to row wherever required. Then modify the alignment and spacing. For that I first review where to make changes and finalize the values in dev tools. Once, I finalized, I copy that to the editor file.

Finally, I move to hover and transition. 

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

Converting each and single html element to flexbox was a great achievement. I replaced margins with gaps. It also saved me from the hustle of deciding which sections should be flex. My css code became more DRY.

To see how you can add code snippets, see below:

```css
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Bai Jamjuree', sans-serif;
    font-size: 18px;
    font-weight: 400;
    display: flex;
    flex-flow: column nowrap;
    justify-content: center;
    align-items: center;
    gap:1rem;
}
```

If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more.



### Continued development

The nav section at the bottom is not exactly like shown in the design images. I would further like to perfect flexbox and grid concepts to arrange the things as desired.


### Useful resources

- [Landmarks in html](https://www.w3.org/TR/wai-aria-practices/examples/landmarks/HTML5.html) - This helped me to understand the landmarks in html5.
- [Complete guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/, https://flexboxfroggy.com/) - This is an amazing article which helped me finally understand flexbox. I'd recommend it to anyone still learning this concept.

-[Complete guide to css grid](https://css-tricks.com/snippets/css/complete-guide-grid/, https://cssgridgarden.com/) - This is an amazing article which helped me finally understand grids. I'd recommend it to anyone still learning this concept.



## Author

- Website - [Clipboard landing page](https://www.your-site.com)
- Frontend Mentor - [@Akku22jan](https://www.frontendmentor.io/profile/Akku22jan)

## Acknowledgments

I would like to acknowledge frontend mentor solutions where I saw declaring colors as variables, that eased the process
I would like to thank AngelaYu and udemy, I first did the full stack web development course with her She only introduced me to frontend mentor
I would like to thank barbara, she greately solved the margins issue by suggesting to convert each element to flex.
Lastly, I would like to thank "building amazing things" youtube channel. There video on "UI Design Crash course" helped me to understand typography and color hierarchy.
