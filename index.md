![](images/landing-page.png)
## Overview 

Eatereez is a web application that provides pages to locate, rate, and view the menus of the restaurants and other food places on the UH Manoa campus. In addition, it will allow users to search for restaurants based on both meal preferences (e.g. burrito) and dietary restrictions (e.g. vegetarian, gluten-free, etc.).  It illustrates various technologies including:

* [Meteor](https://www.meteor.com/) for Javascript-based implementation of client and server code. 
* [React](https://reactjs.org/) for component-based UI implementation and routing.
* [Semantic UI React](https://react.semantic-ui.com/) CSS Framework for UI design.
* [Uniforms](https://uniforms.tools/) for React and Semantic UI-based form design and display.

The web application is displayed here:
[Eatereez](http://eatereez.meteorapp.com/#/)

### Project Milestones

Eatereez has completed each of its milestones by the launch deadline, which are listed below
 
[Milestone 1](https://github.com/nutrition-positions/eatereez/projects/1) shows the current status of the project at the completion of the first milestone, which includes mockups of each of the project pages.

[Milestone 2](https://github.com/nutrition-positions/eatereez/projects/2) shows the current status of the project as it heads towards the second milestone, which involves creating functional webpages for the website.

[Milestone 3](https://github.com/nutrition-positions/eatereez/projects/3) shows the tasks completed in the last milestone. This milestone's goal was to give the application an aesthetic touch which includes an overhaul of the landing page, restaurant page, and other small things. Included in our goals is to complete the implementation of the restaurant reviews and map. After some user reviews, a lot of functionality was added for the admin to be able to better control the website.

### Table of Contents
* [User Guide](#user-guide)
* [Landing Page](#landing-page)
* [Index Pages](#index-pages)
* [Sign in and sign up](#sign-in-and-sign-up)
* [User Reviews](#user-reviews)
* [Map](#map)
* [Community Feedback](#community-feedback)
* [Developer Guide](#developer-guide)
* [Group Members](#group-members)


## User Guide

Logging In:

To sign, click on login at the top right of any page. You are logged if it displays your email.

![](images/SignIn.png)

Searching For Restaurants:

There are two ways of searching for restaurant. 

![](images/LandingPage-Greet.png)
The first is from the Landing Page with the use of the search bar here. Type the name of the restaurant and press either the search button or enter key will bring your search request to the restaurant list.

![](images/ListRestaurant-Filters.png)
The main way of searching through the list is to use the List Restaurant Page. This page has four options to adjust the scope of your search. First option one is to search by name. Second option is to search by keywords such as "sandwhiches" or "Chinese". The third option is for vegetarians and vegans. Last option has locations.

Submitting Reviews:

There are reviews in the restaurant detail page. You can get to the restaurant detail page by navigating through the restaurant list.

![](images/RestaurantDetails-M3.png)

Underneath the logo, there are a list of reviews. Here you can see who, how many stars they give, and what they thought. You can also delete your own reviews or report other reviews if they contain inappropriate content.

![](images/Reviews.png)

At the bottom, you can write your review here. Give your review title, the number of stars, and your thoughts.

![](images/SubmittingReview.png)

Using the Map:

You can navigate to the map via the top navbar. There are pins where the restaurants are located. By clicking the pins, you can see what restaurants there and a link to more information.

![](images/MapMarkers.png)

## Landing Page

The [landing page](http://eatereez.meteorapp.com/#/) is presented to users when they visit the top-level URL to the site. It has a description of the purpose and features of Eatereez. The landing page contains four sections. 
![](images/LandingPage-M3.png)

The first section provides the user with a button and a search bar so they can get straight into searching. This section will also greet the user if they are logged in.
![](images/LandingPage-GreetUser.png)

Second section contains information about the site. All icons and text here are clickable and will redirect the user to the relevant page. 
![](images/LandingPage-Info1.png)

Third section has a picture carousel with three random restaurants of the list. This section is to help alleviate deciding where to eat should the user been unable to decide. 
![](images/LandingPage-Random.png)

The fourth section is a reminder to login so that the user can take advantage of all functionalities such as making comments or reporting comments.
![](images/LandingPage-Info2.png)

## Index pages 

Eatereez provides four public pages (Find Food, Map, and Restaurant Details pages) that present the contents of the database organized in various ways. 

The [Find Food](http://eatereez.meteorapp.com/#/food) page displays a list of restaurants, with the ability to be filtered by food type (Hawaiian, Chinese, Sandwiches, etc...), location, and dietary preference (Vegan, vegetarian). Each restaurant will also have an average rating displayed:

![](images/ListRestaurant-M3.png)

The [Map](http://eatereez.meteorapp.com/#/map) page shows a map with various pins at the places you can get food:

![](images/Map-MS2.png)

The [Restaurant Details](http://eatereez.meteorapp.com/#/details/cd8Yp98TZpR4fnpqT) pages shows even more details about each restaurant, such as their menu, full description and the full list of reviews:

![](images/RestaurantDetails-M3.png)

## Sign in and sign up

Click on the ["Login"](http://eatereez.meteorapp.com/#/signin) button in the upper right corner of the navbar, then select "Sign in" to go to the following page and login. You must have been previously registered with the system to use this option:
 
![](images/signin-page.png)
  
Alternatively, you can select ["Sign up"](http://eatereez.meteorapp.com/#/signup) to go to the following page and register as a new user:

![](images/signup-page.png)

## User Reviews

Once you are logged in, you can add reviews on the [Restaurant Details](http://eatereez.meteorapp.com/#/) page of each restaurant, as well as report the reviews of other users.

![](images/submit-review-page.png)

![](images/report-page.png)

## Submit Eatery

Logged in users will also be able to [submit new restaurants](http://eatereez.meteorapp.com/#/submit-restaurant) to the website, which will then be subject to approval by site admins before being published.

![](images/submit-eatery-page.png)


## Map

Users can use the map to help them navigate to their restaurants. The map will display pins of all restaurant locations. An info will show when you click on the markers. It will display the name  Below the map page are instructions on how to use the map.

![](images/Map.png)

## Community Feedback

Jaylin Kuoha (Food loving Mathematics Major)
- Could use something extra to fill in the white space
- I like that there's a menu for each of the restaurants listed
- The colors are nice on the eyes

Matthew Mackenzie (At the time starving Geology Major)
- It's pretty impressive, but I don't like the green bar at the bottom having a bunch of white below it
- The logo is pretty gnar

Somebody
The homepage looks neat and clean, love the logo on the background.  However, the logo, search bar, and button seem off center. I really like the way the map looks but the links are broken and the “How To” section feels a little out of place.  I like having both the location and address listed.  I’d like that if i clicked on the menu or website link it would open in a new tab.   Loving the reviews! Wish I could sort by them.  Also I like the submit a restaurant page because there are so many sites that miss info and to be able to submit new info makes me feel good and not annoyed it’s missing something.

Jake Camarao (CS major)
- Likes the convenient search bar on the landing page
- Wants to sort the restaurants by stars

## Developer Guide

1. Clone the repo from [here](https://github.com/nutrition-positions/eatereez)
2. Using terminal navigate to the correct directory ".../eatereez/app/"
3. Type "meteor npm install"
4. Type "npm install react-slide-image"
5. Lastly type "meteor npm run start" 

Note: You will need to provide your Google map API key. You can get a Google API key [here](https://developers.google.com/maps/documentation/javascript/get-api-key).

This should have a running localhost of our application.

## Group Members
[Ryan Ell](https://ryanell.github.io)

[Tommy Herman](https://hermantw.github.io)

[Colin Jackson](https://colinj23.github.io)

[James Lau](https://jklaulau.github.io)

