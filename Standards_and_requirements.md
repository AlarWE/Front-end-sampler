# Standards and requirements

* HTTP output - HTML5
* Styles - CSS3
* Language abbr. - ISO 639-2 Alpha-2
* Browsers - IE8, Chrome (latest), Firefox (latest), Safari (latest), Mobile browsers
* Scripts - JavaScript 1.8.5, jQuery 1.11.3

## General requirements

1. A HTML5 based layout. 
2. A dynamic layout (taking account the variable volume of content).
3. Responsiveness (website should work on every device and every screen size, no matter how large or small, mobile or desktop.)
4. The generated HTML should include all the elements needed in the final version, not just the elements required for presenting the prototype.
5. The finished prototype must be completely semantic and be divided to data, presentation and behavior/movement layers.
6. Labels, links and all other elements with variable content (translations), elements need to be in text format.
7. It is important to display information about the general building blocks of the prototype (for ex. body contains three containers: “header”, “content” and “footer”. “content” in turn, is divided to “sideContent” and “mainContent”, etc). In addition, any special remarks as needed.
8. CSS must be valid (except IE hacks). [CSS Validation] (https://jigsaw.w3.org/css-validator/)
9. HTML must be valid. [Markup Validation] (http://validator.w3.org/)

## Specified instructions

* Empty br, div, p etc. are not for positioning layout elements, use CSS.
* List items should be formally identical.
* Do not use one ID tag multiple times on a page for styling.
* Styling classes should target complex objects (table, form), not single objects (table cell, input field).
* input type=file should be solved with jQuery or JS.
* Checkbox and Radio button styling must be solved with CSS.
* Styling select elements should be solved with CSS and jQuery or JS.
* Datepicker and Autocomplete must be solved with jQuery UI.
* Buttons related to a form such as submit and reset should be button type=submit or other button types. Navigating to a different page should always be solved with an element, even when visually identical.  
* Differently sized thumbnails from an image should be kept to the minimum.
* Not all elements must have a class attached to it. It’s easier to define by type or parent elements.
* If a block or element is unique to the page, define it with an id attribute not with a class. If it is an element used frequently on the site, use a class. (For ex. header is a unique block so use an id attribute. Coloring an odd row in a table is a frequent occurrence so use a corresponding CSS selector not a class).
* A selectors name should be in English, short, precise, understandable in context. Created names should have a uniform logic.
* Used image files (design elements and content) should be grouped logically in to subdirectories.
* The same system should be used with css files. I.e. main styles, third party software (datepicker, autocomplete), etc.
* Necessary browser override styles should be in a separate file. I.e. IE8.css.
* It’s necessary to use hover effects on buttons, anchors etc.
* Using JavaScript or jQuery should be kept to a minimum.
* IE8 does not support some CSS3 rules, so there is no need to use some third-party scripts for them. Just make sure the layout is not broken.
* Custom fonts should be added with Google Fonts.
* Mobile (responsive) layout should start from 1024px (iPad width) and end at 320px (minimum mobile width).