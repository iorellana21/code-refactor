# Code-Refactor

## Description
Refactoring Horiseon website to make it more accessible.
## What Was Done
Performed code-refactor on original-html and original-css files for [Horiseon](https://github.com/iorellana21/code-refactor/blob/main/assets/images/01-html-css-git-homework-demo.png) (link to image) - from restructuring order, updating tags, consolidating classes, correcting broken link.
#### 1. HTML
* Apply correct indentation and spacing
* Replace &lt;div&gt; tags with appropriate HTML semantic tags
    * header
    * figure
    * main
    * section
    * aside
    * footer
* Add 'id' to line 36 to make internal link work
* Add 'alt' to all images
* Add comments for each HTML semantic tag
* Remove classes and have CSS file call on the HTML tag

#### 2. CSS
* Ensure correct indentation has been applied
* Reorder file to have a top-down format based off HTML
* Consolidate properties that are applying the same format
    * Example: .benefit-lead, .benefit-brand, .benefit-cost
* Update CSS selectors to call HTML tag instead of a class 
    * Example: .header{} -> header{}
* Rename .hero class to call &lt;figure&gt; tag
* Add comments for each configuration

## Before and After
Original HTML              |      HTML Refactored
:-------------------------:|:-------------------------:
![alt text](https://raw.githubusercontent.com/iorellana21/code-refactor/main/assets/images/original-html.png "OG HTML")  |  ![alt text](https://raw.githubusercontent.com/iorellana21/code-refactor/main/assets/images/html-refactored.png "Refactored HTML")


Original CSS               |      CSS Refactored
:-------------------------:|:-------------------------:
![alt text](https://raw.githubusercontent.com/iorellana21/code-refactor/main/assets/images/original-css.png "OG CSS")  |  ![alt text](https://raw.githubusercontent.com/iorellana21/code-refactor/main/assets/images/css-refactored.png "CSS Refactored")

## Credits
* [Stack Overflow](https://stackoverflow.com/) - building the table for Before and After
* [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) - how to build README
* [W3 HTML Validator](https://validator.w3.org/#validate_by_upload) - validating HTML
## Links
#### Live URL
* https://iorellana21.github.io/code-refactor/
#### GitHub URL
* https://github.com/iorellana21/code-refactor

#### HTML URL
* https://github.com/iorellana21/code-refactor/blob/main/index.html
#### CSS URL
* https://github.com/iorellana21/code-refactor/blob/main/assets/css/style.css