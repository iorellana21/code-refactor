# Code-Refactor

## What Was Done
Perfomed code-refactor on original html and css files for Horiseon website - from restructuring order, updating tags, consolidating classes, correcting broken link.

#### 1. HTML
* Apply correct indentation and spacing
* Replace &lt;div&gt; tags with appropriate HTML semantic tags
    * header
    * figure
    * main
    * section
    * aside
    * footer
* Add 'id' to line 36
* Add 'alt' to all images
* Add comments for each HTML semantic tag
* Remove classes and have CSS file call on the HTML tag

#### 2. CSS
* Ensure correct indentation has been applied
* Reorder file to have a top-down format based off HTML
* Consolidate classes that are applying the same format
    * Example: .benefit-lead, .benefit-brand, .benefit-cost
* Update classes that are referenced in HTML semantic tags to call the tag instead of a class 
    * Example: .header{} -> header{}
* Rename .hero class to call &lt;figure&gt; tag
* Add comments for each configuration

## Before and After Pics

Original HTML              |      HTML Refactored
:-------------------------:|:-------------------------:
![]()  |  ![]()


Original CSS               |      CSS Refactored
:-------------------------:|:-------------------------:
![]()  |  ![]()

## Links
#### GitHub URL
* 

#### Live URL
* 