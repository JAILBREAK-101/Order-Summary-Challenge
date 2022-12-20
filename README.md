Frontend Mentor - Order summary card solution
This is a solution to the Order summary card challenge on Frontend Mentor. Frontend Mentor challenges help you improve your coding skills by building realistic projects.

Table of contents
Overview
The challenge
Screenshot
Links
My process
Built with
Continued development
Acknowledgments
overview
The challenge
Users should be able to:

See hover states for interactive elements
Screenshot


Links
Live Site URL: (https://genixjailbreak.netlify.app/)
My process
Built with
Semantic HTML5 markup
CSS custom properties
Flexbox
Responsive CSS (Media Queries for Background for Mobile view)
What I learned
I learnt how to really limit the lines of code i write in CSS, by using CSS advanced properties and selectors, such as : nth-of-type(), :is, and combination of other selectors for selecting elements by classes, Ids or tagnames. I also learnt how to combine styles together not only using the advanced CSS selectors, but also getting used to limiting the amount of lines of CSS code i use when styling different components (tags and elements on the HTML file and on the Web-Page).

Some snippets on the advanced CSS selectors, and Pseudo Properties I used during the challenge:

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
All these limited the amount of code (lines of CSS) I had to write for each component

Continued development
I want to continue to focus on building solid layouts and components even more advanced than this, by practicing on using advanced CSS selectors to reduce the number of lines of CSS that I write for a single component, and for all the components of my project. And also writing Semantic HTML, not only to make my HTML well structured and more readable, but also to give meaning to Screen Readers made Visually Impaired people, and to those that are disabled in one way or the other that want to have access to my Website accessible, and to make my Website and projects easily understandable for them.

Useful resources
Learn Every CSS Selector In 20 Minutes - This helped me for CSS advanced Selectors. I really liked this concept, and in the way it was though, and will use it going forward in the development of other projects.
Author
Frontend Mentor - @JAILBREAK
Twitter - @Oluwagbemiga
Github - @JAILBREAK-101
Acknowledgments
I appreciate Kyle from Web Dev Simplified for the amazing concepts he has been teaching on his YouTube Channel, thus giving me a chance to learn them. I also acknowledge and thank FrontEnd Mentor for their amazing challenges, thus giving I and other developers a chance to participate and build Real-World Projects, that can be added to our portfolio for potential Job-Hirings, and also greater opportunities in the future.
