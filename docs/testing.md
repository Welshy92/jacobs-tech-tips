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

405 - POST error occured when submitting forum.
Caused by having multiple actions in the Form tag. Removed redundant tag and it is now working correctly.

Large amount of whitespace below the form on the mobile view.
Caused by the hidden lightbulb image. Changed the image size to 0 and added an upscale to the media query for it.

### **Known Bugs**

Nav bar becomes off-centered between mobile and desktop widths. Maybe and another breakpoint in the middle (tablet size?)

Form on index incorrectly centered in desktop view

No gap between the heading and paragraph text