# Code Refactor Starter Code

## Description

Having been provided with some starter code for "Horeison", my task was to adjust some of the existing code to make it more efficient, readable and geared towards Search Engine Optimisation and accessibility.

Certain aspects of the .html file were changed to remove vague <div> elements and were replaced with appropriate, specific ones i.e. <header>, <footer>, <section> etc. depeding on their positioning and funtion on the page. Their respective attributes were changed in CSS accordingly so that they still effected styling.

Any <h> tags were renamed to follow the flow of the page, going from lowest and progressing higher further down the page; this ensures any screen-readers would read headings sequentially rather than eratically across the page. Similarly, I also ensured the order of the html and CSS were structured in a similar way to the layout of the page i.e. top to bottom, left to right, for ease of code readability.

Where multiple selectors possessed the same properties and values, they were combined under one selector, or by having multiple classes seperated by commas. Similarly, some details, such as font, text colour and size, were shared by the majority of the document and were placed into the <body> selector to apply to all, but could still be altered by including differences dictated the parent element.

In terms of SEO and accessibility, a title for the page was inserted into the <head>. Elsewhere, all pictures were provided with an "alt" tag, giving them a description of the image enabling them to be read by screen readers. However, as a result of rewriting the code for the "hero image" in order to have an "alt" tag in HTML, the display does not function as it did when in CSS - when the screen width is changed, the image does not altersize or remain centered. After attempting and failing to rectify the styling in CSS, I have had to compromise for the sake of accessibility.

## Usage

Below is a link to the live site and screenshots across the page showing it deployed:
https://blealan.github.io/week-1-code-refractor-assignment-b-lealan/

```md
    ![Screenshot 1](assets/images/screenshot-1.png)
    ![Screenshot 2](assets/images/screenshot-2.png)
    ![Screenshot 2](assets/images/screenshot-3.png)
    ```


## Credits

Here are some links for sites used to check on best practises and formating:
https://www.w3schools.com/
https://www.freecodecamp.org/news/html-best-practices/
https://www.w3schools.com/html/html5_semantic_elements.asp
https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/Organizing
https://www.codecademy.com/learn/learn-html/modules/learn-semantic-html/cheatsheet
https://coding-boot-camp.github.io/full-stack/github/professional-readme-guide

Some code elements (hero image and links within the top navigation bar) were discussed with Graham McCullough, and I viewed his code found at:
https://github.com/Grahamy27/week-1-code-refactor-graham

