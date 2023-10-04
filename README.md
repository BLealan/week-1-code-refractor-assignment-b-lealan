# Code Refactor Starter Code

## Description

Having been provided with some starter code, my task was to adjust some of the existing code to make it more efficient, readable and geared towards Search Engine Optimisation and accessibility.

Certain aspects of the .html file were changed to remove vague <div> elements and were replaced with their appropriate ones i.e. <header>, <footer> etc. Their respective atributes were changed in CSS accordingly so that they were still effected.

Any <h> tags were renamed to follow the flow of the page, going from lowest and progressing higher further down the page; this ensure any screen-readers would read headings sequentially rather than eratically across the page. Similarly, I also ensured the html and CSS were structured in a similar way to the layout of the page i.e. top to bottom, left to right, for ease of code readability.

Where multiple selectors possessed the same properties and values, they were combined into one selector, using multiple classes seperated by commas. Similarly, some details, font, text colour and size were shared by the majority of the document - these were placed into the <body> selector to apply to all, but could still be altered by including differences via the parent element.

In terms of SEO and accessibility, a title for the page was inserted into the <head>. Elsewhere, all pictures were provided with an "alt" tag, giving them a description of the image.

## Usage



## Credits

Here are some links for sites used to check on best practises and formating:
https://www.w3schools.com/
https://www.freecodecamp.org/news/html-best-practices/
https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/Organizing
https://www.codecademy.com/learn/learn-html/modules/learn-semantic-html/cheatsheet
https://coding-boot-camp.github.io/full-stack/github/professional-readme-guide

## License

