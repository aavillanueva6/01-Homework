# semantic-markup

## this is the first homework assignment for my coding bootcamp

The task of this assignment was to refactor a website to improve its accessibility.  The initial version of the html for the site did not use any semantic html tags to structure the site.  Most of the elements in the site were classified as \<div>'s.  A screenshot of the original code is below:


A summary of changes to the code are as follows:

* A title was added to the \<head> element
* \<div> with class "header" was changed to a \<header>
* \<div> with the links to the other sections on the page was changed to a \<nav>
    * This resulted in an update being required in the style.css file.  This \<div> was referenced in three locations to format the navigation bar.  Each instance of "div" in the css was changed to "nav" (i.e. ".header div ul" was changed to ".header nav ul")
* \<div> with class "hero" was changed to a \<figure> with class "backgroundImage"
    * This resulted in an update being required in the style.css file.  The class "hero" is used to set the background image size and provide a source for the image.  The class needed to be updated to match the change in the html.
* \<div> with class "content" was changed to a \<section>
* each of the three \<div>'s under the "content" section were changed to \<article>'s
* The Search Engine Optimization article was missing an id that was required for the nav menu link to function.  id "search-engine-optimization" was added to the element
* \<div> with class "benefits" was changed to an \<aside>
* ach of the three \<div>'s under the "benefits" aside were changed to \<article>'s
* \<div> with class "footer" was changed to a \<footer>
* the \<h2> element in the footer was changed to an \<h4>
    * This resulted in a required change to the css file.  A style was defined for the \<h2> element inside of the footer class.  This was updated to reference the updated \<h4> element.
* an alt property was added to all \<img> elements
* comments were added to both the html and the css files to provide brief descriptions of what each section of code is doing.
* 
* 
* 

The deployed version of the website with my refactored code is live on github pages at the following link:  
https://aavillanueva6.github.io/01-Homework/

