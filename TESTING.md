# Testing

## Code Validation

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