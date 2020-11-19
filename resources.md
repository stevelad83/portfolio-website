# Topics & Resources

## HTML & CSS basics

If you've no experience with these technologies, please follow the [Codeacademy learn HTML](https://www.codecademy.com/learn/learn-html) and [Codecademy learn CSS](https://www.codecademy.com/learn/learn-css) courses on HTML and CSS. These units give a good overview of HTML and CSS, but if you want some extra practice or prefer the format of FreeCodeCamp, try the [FreeCodeCamp HTML/CSS material](https://learn.freecodecamp.org/) out too.

One of the most important things to understand about HTML and CSS is the Box Model. [This video](https://www.youtube.com/watch?v=9z0LjM4cM0o) explains it pretty well.

[LearnCSSLayout](http://learnlayout.com/toc.html) is also a brilliant guide on all aspects of using CSS to control layout. Combine it with playing around in [Codepen](https://codepen.io/) to practice what you've learnt so far in this section.

There are loads of great HTML and CSS resources online, but the sheer volume of elements, attributes and styles to learn means that it can take a while until it sinks in. To get you started, Here are a couple of reference guides and cheatsheets:

- We like [this book](http://wtf.tw/ref/duckett.pdf) which is great value for the investment.

- Some good HTML5 cheatsheets are available [here](https://websitesetup.org/html5-cheat-sheet/)

- A great place to try out anything like this is [Codepen](https://codepen.io/). You can make your own stuff ('pens'), but have a look at what other people are up to too - great for inspiration.

## Responsive Design

Nowadays most visits to websites are made on mobile and tablet devices. This means people are viewing sites on a range of different screen sizes, and we need to make sure our site looks attractive and provides a good user experience across all devices. Responsive design is the process of designing and building our sites with this in mind. There are a few concepts and features in CSS that you should get to know to help with this:

- The use of **relative units** when we specify sizes and positions with CSS. There is a short section on the [% unit](http://learnlayout.com/percent.html) on LearnLayout. Read this article on [Relative Units](https://thecssworkshop.com/lessons/relative-units) and maybe try some out on Codepen.

- The use of **media queries**. Media Queries allow us to specify particular styling to be applied at specific ranges of screen sizes, giving us extra control over where we position things and how we size elements and typefaces on different sized devices. There is a short section on the [Media Queries](http://learnlayout.com/media-queries.html) on LearnLayout. Also read this [CSS Tricks Guide to Media Queries](https://css-tricks.com/css-media-queries/) and experiment on Codepen.

- The **flexbox** layout model has been around since the early 2010s, and was created with responsiveness in mind. It is very commonly used now to handle alignment across one direction, and is worth getting on top of. The [MDN basic concepts walkthrough](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout/Basic_Concepts_of_Flexbox) is an excellent introduction, then the [CSS Tricks guide](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) is a great reference. Kill some time and learn some flexbox with [Flexbox Froggy](https://flexboxfroggy.com/) and [Flexbox Zombies](https://flexboxzombies.com/p/flexbox-zombies).

- Finally, the new kid on the block is **CSS grid**. It has been supported on all major browsers since the end of 2017, and is becoming more and more widely implemented. Whereas flexbox is focused on handling elements across one dimension, you can think of CSS Grid as a mapping tool across two dimensions. Again, your major references should be [MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout/Basic_Concepts_of_Grid_Layout) and [CSS Tricks](https://css-tricks.com/snippets/css/complete-guide-grid/). But [Grid Garden](http://cssgridgarden.com/) is a fun introductory game too.

## Accessibility

Accessibility, commonly referred to a 'a11y' in the tech world, refers to making tech available to as many people as possible, regardless of any disability or impairment. You can read a summary of the aims and legal imperatives we must subscribe to as developers on [W3C](https://www.w3.org/standards/webdesign/accessibility).

One thing you can do from the start is ensure you are using 'semantic HTML' - or the right element for the right occasion - here's an [overview](https://internetingishard.com/html-and-css/semantic-html/). For example, a `<p>` tag represents a **p**aragraph, so that's what it should be used for, because this has implications not only for those read your code, but for [screen readers](https://24ways.org/2017/accessibility-through-semantic-html/) and [SEO optimisation](https://www.inboundnow.com/html5-semantic-elements-mean-seo/) amongst other things.

[Axe](https://www.deque.com/axe/) is an accessibility auditing tool available as an extension on [Chrome](https://chrome.google.com/webstore/detail/axe/lhdoppojpmngadmnindnejefpokejbdd) and [Firefox](https://addons.mozilla.org/en-US/firefox/addon/axe-devtools/). It will give you some detailed feedback on accessibility issues your website might have - try using it on some popular websites and see where they fall short!

## CSS Pre-processors & Syntax

Start building your site using vanilla CSS - you should get used to its syntax and its limitations. In the 'real world', however, many developers use a CSS pre-processor. This is essentially an extra step in interpreting the CSS - it can be written in a different format, which is then processed into regular CSS that browsers can understand. This [article](https://htmlmag.com/article/an-introduction-to-css-preprocessors-sass-less-stylus) is a great demonstration of how three of the most common CSS pre-processors (SASS, LESS and Stylus) give you more freedom with CSS.

Another consideration on larger projects is adopting a naming convention for your CSS classes that is readable and flexible. You might not be doing something on a scale where you reap the benefits, but this would be a good opportunity to explore good practices: consider implementing the [BEM syntax](http://getbem.com/introduction/) in your page.

## Resources to spruce up your pages

- [fontawesome.io](http://fontawesome.io/) for icons
- [devicon](http://konpa.github.io/devicon/) for some lovely tech icons in particular
- [google fonts](https://fonts.google.com/) for easily implementable fonts
