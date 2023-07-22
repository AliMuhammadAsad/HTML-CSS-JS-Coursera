# Coursera HTML, CSS and Javascript for Web Developers <img alt="HTML5" width="36px" src="https://cdn.jsdelivr.net/npm/programming-languages-logos@0.0.3/src/html/html.svg"/> <img alt="CSS3" width="40px" src="https://upload.wikimedia.org/wikipedia/commons/6/62/CSS3_logo.svg"/> <img alt="JS" width="40px" src="https://cdn.jsdelivr.net/npm/programming-languages-logos@0.0.3/src/javascript/javascript.svg" /> <img alt="Bootstrap" width="46px" src="https://upload.wikimedia.org/wikipedia/commons/b/b2/Bootstrap_logo.svg" />

## Module 5 Coding Assignment

**Summary:** In this assignment, we are going to have a bit of fun with our built restaurant web application. The front page of our web app contains 3 clickable tiles: Menu, Specials, and Map. If you click on the Specials tile, you will be taken to a single category page where all the menu items that belong to the Specials menu category will be shown. Your task in this assignment is to alter this behavior such that when the user clicks on the Specials tile, the web app takes the user to a random single category menu page, listing menu items in the category, be it "Lunch", "Dinner", "Sushi", etc. That way, any random category can become the Specials! What fun! (not! :-))

In order to accomplish this, we need to change the home HTML snippet and, besides pulling it dynamically from the server, also insert a random category `short_name` into the function call of the following code. Previously, the code to send the user to the "Specials" category was this:

```html
<a href="#" onclick="$dc.loadMenuItems('SP');">
```

For this assignment, we changed this line to prepare it for a random category `short_name` to be this:

```html
<a href="#" onclick="$dc.loadMenuItems({{randomCategoryShortName}});">
```

Here is what you will need to complete the assignment:

1. You will need to download the starter files for this project and copy them into your solution container folder (e.g., into 'module5-solution'). Since assignments and starter code get updated from time to time, don't assume that you have the latest version already on your system. The best way to ensure that you are working with the very latest starter code is either 'git clone' the `fullstack-course4` repository into a new directory OR, if you've already done 'git clone' previously, you can simply open up your command prompt (cmd on Windows or Terminal on Mac), navigate to the folder where the `fullstack-course4` repository was previously cloned into and do: `git pull`
<br><br>
This will update your local repository with whatever changes have been made since the last update.
<br><br>
**As a reminder, the full repository URL is:
https://github.com/jhu-ep-coursera/fullstack-course4**

2. Once you update your repository, copy all the contents of the `fullstack-course4/assignments/assignment5/assignment5-solution-starter` folder into your newly created solutions container folder for this assignment, e.g., `module5-solution`.
<br><br>
Once that's done, you are ready to start coding the solution.
<br><br>
**NOTE: the provided code will not run. It is up to you to follow the instructions to get it to run.**

3. You are NOT allowed to change the `home-snippet.html` file. Any adjustments to the value of `randomCategoryShortName` property needs to be done in Javascript code.

4. There are 4-5 fairly simple steps to implement the required functionality.
  * Open up `js/script.js` file.
  * Find TODO: STEP 0, and follow the instructions until you are done with TODO: STEP 4.
<br><br>
If you've watched the lectures, the code should be very familiar to you.<br><br>

5. Once you are done, verify that the desired functionality is working correctly. Use Browser Sync or deploy your solution to GitHub pages.
  * Load the home page in the browser.
  * Click on the Specials tile. A single page category with a list of menu items for **some** category should appear.
  * Click on the restaurant logo to go back to the home page.
  * Click on the Specials tile again. Most likely, a different single page category page will be shown.
<br><br>
Repeat this several times to make sure that most of the time you see a different single category page.
<br><br>

6. That's it!