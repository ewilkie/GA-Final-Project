# Homewares Galore

This is my final project for the General Assembly Front-end Web development course. 

The duration of the course was 10 weeks with 2x 3 hour sessions per week.

## Table of Content

- [Preview](#preview)
- [Responsive Design](#responsive-design)
- [Interactive Features](#interactive-features)
- [Page built with pure JS](#pure-js)

## Preview

You can access my site [here](https://ewilkie.github.io/GA-Final-Project/)

![image](https://user-images.githubusercontent.com/10229392/216500736-25e020c7-34d3-4ed8-aaab-cd2e26ba29e6.png)


## Responsive Design
<a name="responsive-design"></a>

* **Navbar:** For tablet size and below the navbar items are replaced with a hamburger menu
* **Shop by category:** Tiles displayed in are reduced from 4 per row for bigscreens to 3 per row for smaller screens and tablets. For smaller tables and mobile sites the tiles are replaced with horizontal bars without images
* **Footer:** Text and images are rearranged depending on screen size
* **Store Locations page:** Number of stores per row are reduced depending on size, buttons with box of store location are rearranged depending on size
* **Contact Us modal:** Text rearanged depening on size


## Interactive Features
<a name="interactive-features"></a>

* **Navbar:** When the hamburger menu is display, the navigation options are available via hover
* **Feedback Tab:** Pressing the feedback tab on the right will trigger a box to ease in from the right. Error messages will be display if incorrect/missing information is entered and submit button pressed
* **Contact us:** when pressing this in navbar a modal box appears containing contact info
* **Sale:** hovering over any box with "Sale" text
* **Read more:** Pressing the read more button in the about section will trigger more text to be displayed
* **Contact us button:** redirects to store location page 

## Page built with pure JS
<a name="pure-js"></a>

 The Store Locations page has been populated using javascript.
 
 In the **store.html** file the main section only contains the following code
 
 ![image](https://user-images.githubusercontent.com/10229392/216508332-c1dd034b-f713-4813-a1cb-2552607443a7.png)

In the **stores.js** file, the date is stored in an array of objects. Subsequently I used a for loop to create divs with classes which are then added to the page. 

![image](https://user-images.githubusercontent.com/10229392/216509293-49378f87-ce11-4bb0-a8ad-ac2b0a5d74ba.png)

 If else statements are used to determine weekday text to display
 
 ![image](https://user-images.githubusercontent.com/10229392/216509432-c689af0a-cad1-4a31-bc65-9130d9f110dc.png)

