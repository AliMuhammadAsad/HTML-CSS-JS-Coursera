# Coursera HTML, CSS and Javascript for Web Developers <img alt="HTML5" width="36px" src="https://cdn.jsdelivr.net/npm/programming-languages-logos@0.0.3/src/html/html.svg"/> <img alt="CSS3" width="40px" src="https://upload.wikimedia.org/wikipedia/commons/6/62/CSS3_logo.svg"/> <img alt="JS" width="40px" src="https://cdn.jsdelivr.net/npm/programming-languages-logos@0.0.3/src/javascript/javascript.svg" /> <img alt="Bootstrap" width="46px" src="https://upload.wikimedia.org/wikipedia/commons/b/b2/Bootstrap_logo.svg" />

## Module 3 Coding Assignment

For this course, upon completion of Module 3 which was about designing a website for a real life client, we were further introduced to the Bootstrap framework, and how to use Bootstrap to create responsive webpages.

The assignment is to develop a simple but responsive food website that adheres to some criteria as follows:

1. The implementation of the page you will be creating should follow the mockup illustrations shown below. You are provided 3 mockups: desktop and tablet (same), mobile, and mobile with mobile menu dropdown shown. Your implementation has to be JUST 1 page. In other words, you will be creating a single, responsive page.
2. Your page must include a CSS file. No inline styles allowed. Your CSS file should be placed into a `css` folder under the solution container folder, e.g., `module3-solution/css`.
3. For this assignment, you are to use Twitter Bootstrap CSS Framework as much as possible. I suggest you start with copying the starter bootstrap files and folders.
4. Since we are using Bootstrap for this assignment, instead of specifying pixel ranges, I will define our desktop, tablet, and mobile views in terms of Bootstrap CSS class prefixes, i.e., `md`, `sm`, and `xs`.
     * Desktop mockup illustration should correspond to Bootstrap `md`-based classes
     * Tablet mockup illustration should correspond to Bootstrap `sm`-based classes
     * Mobile mockup illustration should correspond to Bootstrap `xs`-based classes
5. Navbar: Create a navbar that scrolls away together with the page (the navbar should become invisible and is not fixed to the top when you scroll the page down). The navbar should have a company name (i.e., `navbar-brand` class) called "Food, LLC" that is aligned to the left side of the navbar. (*See* [https://getbootstrap.com/docs/3.3/components/#navbar](https://getbootstrap.com/docs/3.3/components/#navbar). *Make the browser window narrower to see the mobile menu button appear in the first example shown at the provided link.*)
<br><br>
For desktop and tablet view, the navbar should not contain anything else. No other buttons should be visible. (_Hint: use 'visible-xs' class._)

1. Navbar - Mobile View: Create a simple menu button (3 horizontal bars). When the user clicks that button, a dropdown menu should appear (as illustrated in Mobile Open Menu illustration below.) The dropdown menu should contain 3 items: Chicken, Beef, and Sushi.
<br><br>
The dropdown menu should take up the entire width of the browser window. Make sure the dropdown menu has a background color set that distinguishes it from the rest of the content.
<br><br>
(_Hint: See_ [_https://getbootstrap.com/docs/3.3/components/#navbar_](https://getbootstrap.com/docs/3.3/components/#navbar) _and Lecture 31 for examples on how to accomplish this._)

1. Page Heading. The page heading that says Our Menu should be centered within the browser window. You must use a Bootstrap class to accomplish this.
<br><br>
(_Hint: look for a Bootstrap class that centers text, see_ [_https://getbootstrap.com/docs/3.3/css/#type-alignment_](https://getbootstrap.com/docs/3.3/css/#type-alignment)_._)

1.  Create a single really tall section that will use the Bootstrap Grid and take up the entire width of the browser window (minus some margins, of course) for all views: desktop, tablet, and mobile. To make the section really tall, you can either fill it out with a LOT of text or simply set its height to something like 1000px. It needs to be tall enough to cause scrolling down to be required to view the bottom of the section. Make sure its background color is set to distinguish it from the rest of the content. (_Hint: don't forget to have an element with a class='container' or class='container-fluid' wrapping your grid. Remember that to have the grid do something "always", i.e., no matter what browser window size, use the `col-xs-`... classes. In this case, since we want the section to take up the entire row, use `col-xs-12`._)

### Mockup Illustrations

**Desktop**

<img src="images/desktop.png" width="50%"/>

**Mobile View**
<div>
<img src="images/menu-collapsed.png" width="25%" align="left" /> <img src="images/mobile-expanded.png" width="25%" align="left" margin-left="20px" />
</div>
<br><br><br><br><br><br><br><br><br><br><br><br>

**&#42;&#42;&#42; REQUIRED GRADED ASSIGNMENT ENDS HERE &#42;&#42;&#42;** 

**OPTIONAL, UNGRADED PORTION IS BELOW:**

1. (OPTIONAL, NOT GRADED) Since in this optional part you will be implementing something more complex than a single section in the Bootstrap grid, remove that section before continuing.

2. (OPTIONAL, NOT GRADED) As in previous assignment, the rest of your site is very simple. It consists of a page heading and 3 sections (all in one row in the desktop view). Each section contains some text. You can make it dummy text/"lorem ipsum", it doesn't matter. How the sections are laid out on the screen depends on the width of the browser window. (_Hint: use the Bootstrap Grid we discussed in Lecture 26 of Module 2 as well as numerous lectures of Module 3, including Lecture 35._)

3. (OPTIONAL, NOT GRADED) Each section should be fairly large in height. You can achieve this by either filling it up with a lot of content text or simply setting its height property to something large like 700px. At the end of each section, provide a link that says "Back to Top". This link should jump the page back to "Our Menu" heading. (_Hint: use a link that points to a section of the page discussed in Lecture 9 of Module 1._)

4. (OPTIONAL, NOT GRADED) Each section should have an h3-based section heading which should be centered within the section. Use the same Bootstrap class you used for centering the page heading to center the section heading. Use the heading names shown in the mockup illustrations, i.e., "Chicken", "Beef", "Sushi".

5. (OPTIONAL, NOT GRADED)Layout: In the desktop view, each of the 3 sections should take up equal amount of space on the screen. As you make the browser window wider or narrower, each section should become wider or narrower.
<br><br>
(_Hint: use `md`-based grid column classes as discussed in Lecture 26 and Lecture 35 among others. It's a 12 grid-based system, so 3 in a row means each grid will take up 4 grid cells, i.e., `col-md-4`._)
For a visual reference of this view, see the desktop mockup illustration below.

6.  (OPTIONAL, NOT GRADED)Layout: In the tablet view, the first 2 sections should be in the first row and be of equal size. The 3rd section should be in the second row and take up the entire row by itself.
<br><br>
(_Hint: use 'sm'-based grid column classes and remember that you don't really need to define a separate 'row' class as you can achieve this layout within a single Bootstrap 'row' as discussed in Lecture 26 and Lecture 35, among others. To have 2 sections take up an entire row, i.e., all 12 columns, each one should take up 6 columns. To make the 3rd section take up the entire width of the browser window, i.e., 12 columns, use `col-sm-12`._)
<br><br>
For a visual reference of this view, see the tablet mockup illustration below.

7.  (OPTIONAL, NOT GRADED)Layout: In the mobile view, each section should take up the entire row.
<br><br>
(_Hint: use `xs`-based grid column class. Since you need to take up the entire row, use `col-xs-12`._)
<br><br>
For a visual reference of this view, see the mobile mockup illustration below.

8.  (OPTIONAL, NOT GRADED) Link the menu items "Chicken", "Beef", "Sushi" from the mobile-only menu drop down to jump to the part of the page those sections correspond to.


### Mockup Illustrations

**Desktop**

<img src="images/desktop-optional.png" width="50%" />

**Tablet**

<img src="images/tablet-optional.png" width="50%" />

**Mobile**

<img src="images/mobile-optional-collapsed.png" width="25%" align="left" /><img src="images/mobile-optional-expanded.png" width="25%" align="left" margin-left="20px" />