# **Windows Simplified - Testing**

![Image from amiresponsive]()

[Windows Simplified live on GitHub Pages](https://welshy92.github.io/windows-simplified/)

## **Contents**

* [Automated Testing](#automated-testing)
* * W3C Validator (HTML)
* * W3C Validator (CSS)
* * Lighthouse Tool

* [Manual Testing](#manual-testing)
* * Testing User Story
* * Full Testing

* [Bugs](#bugs)
* * Solved Bugs
* * Known Bugs

Testing was a regular occurance during the development of this project.



## **Automated Testing**
The HTML of every page was validated by [W3C Validator](https://validator.w3.org)
* [index]()
* [keyboard shortcuts]()
* [maintaining your system]()
* [useful sites and software]()
* [404 error]()

The CSS of every page was validated by [W3C Validator](https://jigsaw.w3.org/css-validator/)
* [index]()
* [keyboard shortcuts]()
* [maintaining your system]()
* [useful sites and software]()
* [404 error]()

Lighthouse tool powered by [PageSpeed Insights](https://web.dev/measure/) was used to test the performance, acessibility, best practices and SEO of the website.
* [index]()
* [keyboard shortcuts]()
* [maintaining your system]()
* [useful sites and software]()
* [404 error]()

## **Manual Testing**

### **Testing User Story**

### **Full Testing**

## **Bugs**

### **Solved Bugs**

* 405 - POST error occured when submitting forum. Caused by having multiple actions in the Form tag. Removed redundant tag and it is now working correctly.

* Large amount of whitespace below the form on the mobile view. Caused by the hidden lightbulb image. Changed the image size to 0 and added an upscale to the media query for it.

* Trying to commit a large video to the repository failed, and crashed my workspace. Video has been uploaded to youtube and is now embedded on the site.

* Incorrect active page showing on the nav bar for all pages except index.htm. Moved the active class to correct nav list item for each page.

* Some external links on the links.html page not opening in a new tab. Added target="_blank" to the relevent ancor tags.

* No gap between the heading and paragraph text. Added line breaks

* Images clipping into the elements above them. Added a top margin to space it out a bit.

* All images with the picture class tag fail to load on github pages (404 error for each image). Works fine in preview. Fixed by changing all file paths to relative.

* Some links across the site incorrectly used an absolute filepath with isn't allowed with Github. Changed to relative filepath.

* Hero image on index.html not streching to edges of the viewport. Caused by some body padding and margins. Both now removed.

* Video embed on maintenance.html not resizing correctly. Placed it into it's own div and used padding-top of 56.25% to allow it to maintain it's 16:9 aspect ratio.

* Can't interact with YouTube player buttons at all on all screen sizes. Changed z-index from -1 to 1 and increased the z-index of header and footer to compensate for the overlap.

* Hamburger menu not working on maintenance.html. Class tag spelling corrected to fix it.

* h2 text too spread out on mobile views of maintenance.html and links.html. Caused by .content styling. move the text alignment to target specific elements of .content as opposed to whole class.

* Form on index.html doesn't get the same level of padding as the rest of the content. Added specific padding to their class + elements.

* captions not aligning correctly. Put captions in seperate divs to rest of the content and moved the class definer to the respective divs.

### **Known Bugs**

