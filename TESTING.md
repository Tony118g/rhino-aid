# Testing

## Code Validation

The Rhino Aid site has been tested extensively through development. All html code has been run through the [W3C html Validator](https://validator.w3.org/) and the css code has been run through the [W3C css Validator](https://jigsaw.w3.org/css-validator/).

* A few errors were found in both the html and css code but after fixing these and rerunning the code no errors were found throughout.
    * To find out more about the errors that arose please see the [known Bugs](#known-bugs) section.

### W3C html validator results

* Home page (index.html)

    ![Screenshot of index.html validation result ](assets/readme-images/html-validation.png)

* Gallery page (gallery.html)

    ![Screenshot of gallery.html validation result ](assets/readme-images/html-validation.png)

* Help out page (help-out.html)

    ![Screenshot of help-out.html validation result ](assets/readme-images/html-validation.png)

* Contact page (contact.html)

    ![Screenshot of contact.html validation result ](assets/readme-images/html-validation.png)

* Form sent page (form-sent.html)

    ![Screenshot of form-sent.html validation result ](assets/readme-images/html-validation.png)

### W3C css validator results

![Screenshot of style.css validation result ](assets/readme-images/css-validation.png)

## Responsiveness Test

Responsiveness testing was carried out throughout the development of the site using [Google Chrome Devtools](https://developer.chrome.com/docs/devtools/) and the [Responsive Design Checker](https://responsivedesignchecker.com/).

* I built the site using a mobile first approach and then added media queries for medium and large screens.
* During development I then ended up adding another media query for very small screens to cater for smaller mobiles. The original coding for the header caused the logo to drop down in order to fit the font and so reducing the font size and adding a few other style rules for screens < 375px fixed the problem.
* During a certain phase of development I replaced two pages in the navbar (volunteer and donate) with a single "help out" page.
    * Following this I tried changing the breakpoints for media queries to cater for a smaller navbar however I discovered that the affects were too detrimental to the rest of the site and had too little effect on the navbar to warrant the change so I reverted back to the original breakpoints.

Once I had made necessary changes, I carried out tests on the site on various devices, these are the results I obtained:

|       | Galaxy s9+|Galaxy s5|Nexus 4|iphone XR|ipad mini|ipad pro|10" notebook|19" desktop|24" desktop 
:-----  | :----:    | :-----: |:-----:| :-----:  | :-----:  | :-----: | :-----:     | :-----:    | :-----:
render  | pass      | pass    | pass  | pass     | pass     | pass    | pass        | pass       | pass
images  | pass      | pass    | pass  | pass     | pass     | pass    | pass        | pass       | pass
links   | pass      | pass    | pass  | pass     | pass     | pas     | pass        | pass       | pass

## Browser Compatibility

The Rhino Aid site was tested on the following browsers:
* Google Chrome
* Microsoft Edge
* Safari

No issues were found across these browsers and the appearance, functionality and responsiveness were consistent throughout.

## Known Bugs

### Resolved

* Across all html pages the following bug was found:

    ![Screenshot of html validation error result ](assets/readme-images/html-bug.png)

    * This was a result of duplicating the nav for a navbar and hamburger menu without changing the id for one of them.
    * It was easily fixed by removing the id="navbar" and replacing it with id="burger-menu"
    
