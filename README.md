# Quizzero :see_no_evil: :hear_no_evil: :speak_no_evil:
![Multi Device View](https://github.com/bartosz-makowski/Quizzero/blob/master/wireframes/quizzero-multiscreens.png)
Project of a Quiz web application using API from [Open Trivia Database](https://opentdb.com/)

## Contents:book:
### UX:superhero_man:	
  * **Project Goals** :jigsaw:	
  * **Target Audience Goals** 	:dart:
  * **Site Owner Goals**  	:dart:
  * **User Requirements and Expectations** 	:dart:
  * **Design Choices** :framed_picture:
    * Fonts
    * Icons
    * Colours
    * Sounds
  * **Wireframes** :straight_ruler:		
  * **Features** :abacus:	
    * Features that have been developed
    * Features that will be implemented in the future
  * **Technologies Used** :computer:	
    * Languages
    * Tools & Libraries
  * **Testing** :magnet:
  * **Bugs** :mosquito:
  * **Deployment** :surfer:
  * **Acknowledgements** :clap:
  
## UX ( User Experience)
### Project Goals :jigsaw:	
The goal of this project is to provide the users with a fun and interactive quiz game. The website needs to be visually appealing whilst providing a great User Experience to encourage users to visit it and play the game

### User Goals :jigsaw: 
* Ability to input your name
* Ability to see the best score
* Ability to see the final score
* ability to choose amount of questions
* Visual feedback when correct answer is chosen
* Visual feedback when incorrect answer is chosen
* Visual interaction and feedback
* Interact with the website on both Desktop tablet and mobile

## User stories 	:dart:
* As a user I expect to **type my name before starting the game**
* As a user I want to be able to **select amount of my questions**
* As a user I want to be able to **change from light to dark mode**
* As a user I want to be able to **see when I choose the correct answer**
* As a user I expect to **check my final score and my best score in the game session**

## Site Owner Goals	:dart:

* Create a fun experience for the users


## User Requirements and Expectations 	:dart:

* **Requirements**
  * Navigate the website using the menu buttons and drop down selector
  * Ability to play the game on desktop and mobile devices
  * Contnent displayed in a visually appealing manor
  
* **Expectations**
  * Content is visually satisfying and informative on all screen sizes
  * No information overload
  * Navigation takes user to specific parts of the website
  
## Design choices :framed_picture:	
The theme of this project is *game*, therefore my design choices are heavily influenced by positive colours and motifs. Using the resources in [this blog](https://www.crazyegg.com/blog/colors-proven-to-boost-sales/) I was able to pick out a colour scheme that has been proven to boost sales/interaction with a web page. By using [this webpage](https://coolors.co/) I was able to macth colors for this projcet.
  
**Fonts**

I chose to use the font **Open Sans** as it was designed with a neutral, yet friendly appearance which compliments the general attitude of this project's design and it's desired function. it can be found [here](https://fonts.google.com/specimen/Open+Sans?sidebar.open=true&selection.family=Open+Sans:ital@1)

**Colours**

Using learned knowledge from prior research, bright and vibrant colours have a higher influence in terms of positivity and therefore more potential interactions. [Link to the colour palette](https://coolors.co/fafafa-000000-ff7f11-ef2d56-2fbf71). Screenshot of the colour palette has been added to the wireframes [folder](https://github.com/bartosz-makowski/Quizzero/blob/master/wireframes/colorpalette.png).
Dark theme palette can be found [here](https://github.com/bartosz-makowski/Quizzero/blob/master/wireframes/quizzero-dark-theme-palette.png)
![Light theme palette](https://github.com/bartosz-makowski/Quizzero/blob/master/wireframes/colorpalette.png)
![Dark theme palette](https://github.com/bartosz-makowski/Quizzero/blob/master/wireframes/quizzero-dark-theme-palette.png)

**Colours used**

* #FAFAFA - Cultured - used for the background
* #000000 - Black - used for text to achieve a good contrast
* #FF7F11 - Amber SAE ECE - used to highlight buttons
* #EF2D56 - Red Crayola - used to highlight wrong answer
* #2FBF71 - Emerald - used to highlight correct answer
* #03120E - Dark jungle Green - used as a background in dark mode
* #FCF7FF - Magnolia - used for texts in dark mode

**Sounds**

## Wireframes :straight_ruler:
I built the wireframes for this project using <a href="https://balsamiq.com/">Balsamiq</a>. Started by doing a very basic wireframe for Mobile/Tablet/Desktop - these were to get a basic understanding of how structurally elements would appear on the page. You can view this wireframe in a wireframe [folder](https://github.com/bartosz-makowski/Quizzero/tree/master/wireframes).

## Features :abacus:
**Features that have been developed:**
* Visible feedback when hover over buttons
* Total score counter
* Best score counter


**Features to be implemented in the future**
* Sound feedback when buttons are pressed
* option to choose question category

## Technologies Used :computer:

### Languages
* [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
* [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)
* [JavaScript](https://www.w3schools.com/js/)

### Tools & Libraries
* [PopperJS](https://popper.js.org/)
* [jQuery](https://jquery.com/)
* [Git](https://git-scm.com/)
* [Bootstrap](https://getbootstrap.com/)
* [Google Fonts](https://fonts.google.com/)
* [Balsamiq](https://balsamiq.com/)
* [AmIresponsive](http://ami.responsivedesign.is/) - used to generate multi screen view of the webiste on different devices


### Testing :magnet:

#### Plan
During planning of this project it was certain I had to have a thorough testing plan in place. Thanks to organising the concept in the wireframes I was able to selcet which feature to work on. This allowed me to thoroughly test the implementation of each feature before moving on to the next task. The utilisation of developer tools in Google Chrome allowed me to test each feature and its behaviour on a different screen sizes. During the development proces this project was tested on various browsers and devices such as Chrome - desktop and mobile, Microsoft Edge - desktop, Mozilla Firefox - desktop, Safari - IPad Pro 9.7 and IPhone XS.
I also tested HTML and CSS by using W3C markup validator and manualy test the game to see if it there is a possibility to brake it.

#### Tests
##### Using W3C Markup Validator
###### Test 1 :writing_hand:
* **Error:** The value of the for attribute of the label element must be the ID of a non-hidden form control.
* **Solution:** Removing ``<label for="Questions-amount">`` fixed this issue
###### Test 2 :mag_right:
* **Warning:**  Empty heading. From line 90, column 17; to line 90, column 39
* **Solution:** Adding  ``<h2 id="question-text">Loading question...</h2>`` fixed this issue
###### Test 3 :chart_with_upwards_trend:
* **Error:** background-color none is not a background-color value : none 
* **Solution** Changing ``background-color: none`` to ``background-color: #FF7F11`` fixed this issue
##### Manual testing of the game
###### Test1 :magnet:
* **Error:** After testing the game and running out of questions screen would freeze at last question.
* **Solution** Adding an if statement in ``newQuestion()`` at line 160 fixed this problem
###### Test 2 :chart_with_downwards_trend:
* **Error:** During testing we found that after selecting one answer user could still select another answer before next question was displayed
* **Solution**  creating a disableAnswerButtons() and enableAnswerButtons() fixed this issue

### Bugs :mosquito:
#### Answer feedback issue :spider:
* **Issue:** During the development process after testing the app noticed that answer feedback wasn't displayed correctly after doing changes to pass the markup validaor
* **Fix:** Removing ``background-color: #FF7F11`` attribute for ``button:hover`` fixed this issue
#### Previous question issue :ant:
* **Issue:** During the development process after testing the app noticed thatafter restarting the game user could see last question and asnwers from previous game
* **Fix:** creating loader() and placing it before getAPI() in ``goBackButton`` and ``beginButton`` fixed this problem

### Deployment :surfer:

Quizzero was developed on GitPod, using git and GitHub to host the repository.

When deploying Quizzero using GitHub Pages the following steps were made:

* Opened up GitHub in the browser.
* Signed in using username and password.
* Selected my repositories.
* Navigated to ``bartosz-makowski/Quizzero``.
* In the top navigation clicked **'settings'**.
* Scrolled down to the GitHub Pages area.
* Selected **'Master Branch'** from the **'Source'** dropdown menu.
* Clicked to confirm my selection.
* Quizzero now live on GitHub Pages. :rocket: 

#### Running Quizzero Locally

Cloning Quizzero from GitHub:

* Navigate to ``/bartosz-makowski/Quizzero``.
* Click the green **'Clone or Download'** button.
* Copy the url in the dropdown box.
* Using your favourite IDE open up your preferred terminal.
* Navigate to your desired file location.
* Copy the following code and input it into your terminal to clone Quizzero.
```
https://github.com/bartosz-makowski/Quizzero.git
```
### Acknowledgements :clap:
* My mentor [Eventyret](www.github.com/Eventyret) for support and priceless feedback regarding this project and allowing me to use his boilerplate [!bcdn](https://marketplace.visualstudio.com/items?itemName=eventyret.bootstrap-4-cdn-snippet)
* [James Q Quick](https://github.com/jamesqquick) [You Tube tutorial](https://www.youtube.com/watch?v=u98ROZjBWy8&list=PLDlWc9AfQBfZIkdVaOQXi1tizJeNJipEx) that I used as an ispiration and base for this project