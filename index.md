## Overview 

Nutrition Positions is a web application that provides pages to locate, rate, and view the menus of the restaurants and food places on UH Manoa campus. It will illustrate various technologies including:

* [Meteor](https://www.meteor.com/) for Javascript-based implementation of client and server code. 
* [React](https://reactjs.org/) for component-based UI implementation and routing.
* [Semantic UI React](https://react.semantic-ui.com/) CSS Framework for UI design.
* [Uniforms](https://uniforms.tools/) for React and Semantic UI-based form design and display.

### Group Members

Ryan Ell
- Student working on a B.S. in Math with Data Science 
- Hoping to contribute to the design/layout of the project as well as help manage the team members and learn more about software development
- Has skills in Photoshop, layout and design and software development from taking ICS 314 in college
- [More info](https://ryanell.github.io)

Tommy Herman
- info for stuff should go here, maybe link to personal website

Colin Jackson
- Student working on a B.S. in Computer Science w/ focus in Security Science
- Hoping to gain a deeper understanding of how websites handle data base queries and potentially tackle a screen scraping script
- Have skills in Linux, Cryptography, Networks, and password cracking
- More info on my latest project can be found [here](https://colinj23.github.io


James Lau
- info for stuff should go here, maybe link to personal website


### Current Progress

The project is currently in the stage of cementing the look of the web application as well as creating the layout of each of the pages and components for the various pages. The app will keep track of the restaurants by using collections including but not limited to Restaurants and Reviews.

[Milestone 1](https://github.com/nutrition-positions/eatereez/projects/1) shows the current status of the project as it heads towards the first milestone, which is a mockup of each of the project pages.

## Project Pages

This section provides a walkthrough of the Nutrition Positions user interface and its capabilities. 

### Landing Page

The landing page is presented to users when they visit the top-level URL to the site. It will have a description of the purpose and features of Nutrition Positions.

![](images/landing-page.png)

### Index pages (FindFood, Map)

Nutrition Positions provides two public pages that present the contents of the database organized in various ways. 

The FindFood page shows all of the food places and lets you search through them all with filters. Filters will include things such as food type (mexican, thai, hawaiian, etc...), if they're currently open, or by user reviews. Each restaurant will have user reviews and ratings that can be read on this page and the reviews will also provide a way to sort by place with highest ratings:

![](images/findfood-page.png)

The Map page shows a map with various pins at the places you can get food:

![](images/Map-page.jpg)


### Sign in and sign up

Click on the "Login" button in the upper right corner of the navbar, then select "Sign in" to go to the following page and login. You must have been previously registered with the system to use this option:
 
![](images/signin-page.png)
  
Alternatively, you can select "Sign up" to go to the following page and register as a new user:

![](images/signup-page.png)

### Review page

Once you are logged in, you can add reviews on the Review page which lets you pick from each of the restaurants and review them:

![](images/review-page.png)

### Submit Eatery

Logged in users will also be able to submit new restaurants to the website which will then be subject to approval by site admins before being published.

![](images/submit-eatery-page.png)

