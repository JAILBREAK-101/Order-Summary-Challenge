# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents
- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [Continued development](#continued-development)
- [Acknowledgments](#acknowledgments)

## overview

### The challenge

Users should be able to:

- See hover states for interactive elements

### Screenshot

![](./Solution%20screen-shot.png.jpg)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Responsive CSS (Media Queries for Background for Mobile view)


### What I learned

I learnt how to really limit the lines of code i write in CSS, by using CSS advanced properties and selectors, such as : nth-of-type(), :is, and combination of other selectors for selecting elements by classes, Ids or tagnames.
I also learnt how to combine styles together not only using the advanced CSS selectors, but also getting used to limiting the amount of lines of CSS code i use when styling different components (tags and elements on the HTML file and on the Web-Page).

Some snippets on the advanced CSS selectors, and Pseudo Properties I used during the challenge: 
```css
:is(.proceed, .component a):hover {
    opacity: .5;
    text-decoration: none;
}

.text p:nth-of-type(1) {
    font-weight: 600;
    margin-bottom: .5em;
    color: var(--supplementary1);
}

main,
.card,
.body-content {
    display: flex;
    align-items: center;
    flex-direction: column;
}
```

All these limited the amount of code (lines of CSS) I had to write for each component
### Continued development

I want to continue to focus on building solid layouts and components even more advanced than this, by practicing on using advanced CSS selectors to reduce the number of lines of CSS that I write for a  single component, and for all the components of my project. And also writing Semantic HTML, not only to make my HTML well structured and more readable, but also to give meaning to Screen Readers made Visually Impaired people, and to those that are disabled in one way or the other  that want to have access to my Website accessible, and to make my Website and projects easily understandable for them. 

### Useful resources

- [Learn Every CSS Selector In 20 Minutes](https://www.youtube.com/watch?v=l1mER1bV0N0&t=786s) - This helped me for CSS advanced Selectors. I really liked this concept, and in the way it was though, and will use it going forward in the development of other projects.

## Author
- Frontend Mentor - [@JAILBREAK](https://www.frontendmentor.io/profile/JAILBREAK-101)
- Twitter - [@Oluwagbemiga](https://www.twitter.com/GenixTech1)
- Github - [@JAILBREAK-101](https://github.com/JAILBREAK-101)

## Acknowledgments

I appreciate Kyle from Web Dev Simplified for the amazing concepts he has been teaching on his YouTube Channel, thus giving me a chance to learn them. I also acknowledge and thank FrontEnd Mentor for their amazing challenges, thus giving I and other developers a chance to participate and build Real-World Projects, that can be added to our portfolio for potential Job-Hirings, and also greater opportunities in the future.