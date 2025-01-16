# **_Food Forest Foraging Recipes - Portfolio Project 1_**

This document contains all the issues necessary to create and develop a website in HTML5 and CSS3 for the website: <a href="https://css-angie.github.io/Food-Forest-Foraging/" rel="noopener" target="_blank">Food Forest Foraging Recipes</a>. The website is a part of the course “Full Stack Software Development” at Code Institute and is a showcase of the knowledge I have gained so far.

<Screenshot of all 3 devices>
</Screenshot>

# Table of Contents
The objective of the website	1
The UX part of creation	1
Creating user stories	1
Designing the layout and structure	1
Colour Palette	1
Typography	1
Images	2
Basic Set-up	2
Set up of the repository	2
Set up of the basics of the website	2
External sources	2
Features	3
Generic features	3
Homepage	3
Plant page	3
Contact page	4
Technology used	4
Deployment	4
Testing	4
Lessons learned and failures	4
Credits	4





# The objective of the website

The food forest hype keeps continuing to conquer the world. Many people are looking at their garden, wondering what they can do to make the world a better place. The ones doing this are willing to start a food forest with native plants and herbs, shrubs and trees (we will only mention plants from now on, but with regard to all). Somehow unfortunately, the knowledge how to use native plants got lost along the way. Knowing quite a few people doubting how to use plants from their garden or found in the woods, I started with the idea to generate information about identification of and recipes for plants. When people harvesting plants during foraging in their backyard or in the woods, they only need to visit this website to gather the knowledge what to do with it.

The primary target group in this case are:
-	Owners of a food forest (small or large is not of interest)
-	Foragers going out in the woods
  
Secondary target groups are:
-	the ones who are interested in becoming a food forest owner 
-	newbies to food foraging, either because they want to become less dependent on supermarkets or have a need to get back to nature

In all cases the education on topics (plants) is the common factor.


[Back to top](<#contents>)

# The UX part of creation

## Creating user stories

For the creation of the user stories, we only focus on the primary target group. The user story is complemented with acceptance criteria and tasks to be able to design wireframes that contain all features needed.

<details><summary><b>User Story 1: As a food forest owner / forager I want to see compelling colours, so I can scroll without being blinded</b></summary>

<br>Acceptance criteria: 
    
*	Website has a pleasant colour scheme that soothes the eye and fits a nature site

Task: 

*	Find a great combination of colours
</details><hr>

<details><summary><b>User-Story 2: As a forager / food forest owner I need pictures to identify my plant, so I can scroll to the right plant directly.</b></summary>

<br>Acceptance Criteria: 

*	Images are compressed  
*	Images are high quality and have webp-extension) 
*	Images are showing the right accents to recognize plant

Tasks: 

*	the page layout features the pictures prominent
*	compress all images with tinypng.com
*	search pixel dense images
*	search self-explaining plant images
</details><hr>

<details><summary><b>User Story 3: As a food forest owner, I want to know how to use my harvest in everyday recipes preventing waste, so I need an overview of recipes that fits the produce.</b></summary>

<br>Acceptance criteria:

*	Homepage displays a photo list of plants sorted alphabetically.
*	After each plant is a page containing extended information and several recipes.

Tasks

*	Design homepage in HTML containing 2 blocks in main.
	- an explanation intro, how to use the website
	- a photo list of plants and name using bootstrap cards in alphabetical order
	- a sign up form in the footer containing name and email address where user can show interest in forum or leave a message what plants should be included in the list
*	Use (minimized) photos so plant can easily be identified
*	Incorporate a navbar at the top
*	Style homepage with Bootstrap and CSS
*	Use colour scheme and fitting graphics
*	Design a plant page in Html containing
	- more than one photo,
	- an information section how to identify a plant and
	- at least two recipes
*	Style plant page with Bootstrap and CSS
</details><hr>

<details><summary><b>User-story 4: As a food forest owner I'm not tech savvy, so I need to see immediately what I can find in the navigation section.</b></summary>

<br>Acceptance criteria:

*	The navigation bar is not overcrowded
*	Every navigation point makes sense
*	Responsive and looks clean and clear at every device
*	Navigation is intuitive

Tasks:

*	Design a navigation bar with 3 or 5 subjects
*	Decide on the 5 subjects
*	Apply responsive design with Bootstrap
*	Incorporate an intuitive layout
</details><hr>

<details><summary><b>User-Story 5: As a forager or food forest owner I want to see at a glance what I can expect of the website. If the website offers me the information I need.</b></summary>

<br>Acceptance Criteria:

*	A catchy headline on homepage
*	Inviting background image
*	One-liner with concise information what visitor can find on site
*	Simple and clear layout

Tasks:

*	Create catchy headline
*	Find a compelling hero image
*	Think of a great one-liner
*	Provide a clean layout
</details><hr>

<details><summary><b>User Story 6: as a forager I want to see more than one photo and read extended information about a plant, so I can identify a plant in the wild.</b></summary>

<br>Acceptance criteria
    
*	more than one image of the plant
*	extensive information about the plant
*	
Tasks

*	search numerous images of the plant
*	find information how to identify the plant
</details><hr>

<details><summary><b>User story 7: as a food forest owner I want to find a recipe that contains the plant with all other ingredients listed and clear preparation instructions, so I can cook everyday meals without a lot of fuzz.</b></summary>
    
<br>Acceptance criteria: 

*	the recipe(s) have a clear name
*	the recipe contains a complete list of ingredients
*	The preparation is shown as a step by step instruction
*	preferably with image
*	the recipes look nicely at all devices
*	
Tasks

*	create layout that is visual appealing for recipes
*	find recipes that contain the plant
*	make unordered list of ingredients with correct amounts
*	make ordered list with preparation instructions
*	make the layout responsive
</details><hr>

<details><summary><b>User story 8: as a forager, I would like to know if like-minded people live near me, so I can get in touch with them. That's why I like to fill in the register form and join.</b></summary>

<br>Acceptance criteria:

*	Registration Form to register for the forum
*	Form contains a message box for additional questions
*	Form looks nice on every device
*   The fields with name and email are required
*	The checkbox for newsletter is optional
*	
Tasks

*	Create form with required name field and required email field and message box
*	Create a checkbox for joining forum or not
*	Make hover function on send-button
*	Use Bootstrap to create round edges for the boxes
</details><hr>

<details><summary><b>User story 9: as a visitor I would like to subscribe to the newsletter, so I will be informed, when a new plant is added to the database.</b></summary>
    
<br>Acceptance criteria: 

*	the website contains a sign up option for a newsletter
*	the sign up option sits in the footer so it will show up on every page, making it easy to subscribe
*	
Tasks

*	create a form with required fields: name and email
*	created a checkbox with a required checkbox to sign in
*	add form to footer
</details>


[Back to top](<#contents>)

## Designing the layout and structure
After having created several user stories, all are used to create a structure that fit all the mentioned requirements i.e. acceptance criteria. Wireframes were made with Balsamic to set the basic guideline for the process.

### Homepage

![preview homepage mobile](assets/readme-images/hp-mobile.png) ![preview homepage tablet](assets/readme-images/hp-tablet.png) ![preview homepage desktop](assets/readme-images/hp-desktop.png)


### Plant page

![preview homepage mobile](assets/readme-images/pp-mobile.png) ![preview homepage tablet](assets/readme-images/pp-tablet.png) ![preview homepage desktop](assets/readme-images/pp-desktop.png)


### Contact page

![preview homepage mobile](assets/readme-images/sf-mobile.png) ![preview homepage tablet](assets/readme-images/sf-tablet.png) ![preview homepage desktop](assets/readme-images/sf-desktop.png)

 
## Colour Palette

Being a website about nature, first colours that come in mind are green and brown, as they connect emotionally to anything natural. But it took some time to find the right colour scheme as green and brown aren't a match, when in comes to contrasting colours. With green as the main colour, most of the generated palettes (at numerous sites) offered a palette with too little contrast, thus creating contrast errors. The palette that is being used now has the colours of most seasons. Orange is a colour associated with sunset and autumn. Whereas autumd is generally known as the harvest season. 

![preview homepage mobile](assets/readme-images/colour-scheme.png)

Finally this green and orange scheme at [coolors.co](https://coolors.co) almost passed the test. The light contrast colour is a 70% shade and was changed to the 62% shade to erase any contrast errors, resulting in HEX-colour #E4B681.
The final colours are now:
#606C38 olive green - jungle civilization
#283618 dark green - darkest forest
#FEFAE0 light yellow - magnolia
#E4B681 light orange – cane sugar
#BC6C25 middle orange brown - brown alpaca


[Back to top](<#contents>)
 
## Typography

The criteria for the fonts were:
-	Heading should have a friendly and personal touch, which leads to handwritten looks.
-	The primary font should be readable at all times and should be a straightforward font without much ado.
Looking in the Google Fonts library I found the appealing font Quintessential for the headings and the sturdy font Roboto for the body text.
Quintessential has a fallback of cursive and Roboto the fallback sans-serif.


[Back to top](<#contents>)

## Images

The general colour palette of the site is greenish, as the project deals with the subject nature and plants. Therefore it makes sense to continue this look-and-feel in  the images  used showing lots of green, brown and al bright and fresh colours you can find in nature.
The logo represents a tree, as is found in forests and the favicon is made from the logo to ensure repetition.<br>
![logo website](assets/images/logo.png)


[Back to top](<#contents>)

# Basic Set-up

## Set-up of the repository 

The basic set-up started with setting up the repository for the project in Github. Within it creating a project board and fill out the board with the user stories with their requirements and the subsequent tasks, labeling every task in the to-do section with must-have, should-have and could-have.
Along wi it the basics of the website were created with the folder structure:
	- index.html with boilerplate and connection to the style.css stylesheet
    - assets - css - style.css
    - assets - favicon and fill this with the generated favicon
    - assets - images and put all images so far in it

External sources used in this project are:
    - bootstrap version 5
    - google fonts
These were added as well at the correct places

The set-up was checked and deployed and ready to be filled with all features


[Back to top](<#contents>)

# Features

## Generic features
	
	### Responsive design
	One of the most important generic features of any website is the responsive design to ensure a great user experience at any device. This was achieved by using bootstrap columns, flex-boxes and media queries. The common DOM breakpoints were used with only one exception. An extra query with min-width 1080px was used to fix the height of the title at the plant catalog, which changed the appearance in a very negative way. To avvoid a very large broad form at the contactpage, the same min-width of 1080px was used to avoid an excess of code.

	### Navigation
	As website users are used to a certain layout nowadays, best user experience is to offer the same way as they are used to. Therefore the logo leading to the homepage is on the left and the menu is on the right. On mobile screens the menu is represented with the well-known hamburger icon offering a dropdown menu when clicked on it.
	The navigation consists of three options. Studies have unveiled that uneven numbers of a menu are most pleasing to the mind of visitors. 


	
	### Favicon
	The favicon is a beacon in all tabs opened and offers the visitor a quick reminder of the site. It is important to have a favicon that represents the website.
	By using the logo making it into a favicon at [favicon](https://favicon.io) the site shows a consistancy and offers a regognizable favicon.<br>
	![favicon website](assets/favicon/favicon.ico)

	
	### Footer
	
	
	### 404 page

## Homepage
	Hero Section
	Main section
	
## Plant page
	Plant identification
	To generate the text I ordered ChatGPT 4o mini the following: write me a text of 300 words how to identify a dandelion and add some recipe names to it. I changed it a bit to match the recipes I wanted to display underneath.
	Recipes
	I found the recipe Cantaloupe, Arugula & Goat Cheese Salad at https://www.eatingwell.com/ and changed the aragula to dandelion leaves.
	I found the recipe Dandelion Jelly at https://www.homestead-acres.com/  and did not change anything except for the layout.


## Contact page
	Form

## Thank you page

## 404 page

## Sitemap XML page

## Privacy Policy

# Technology used

## Languages: 
HTML and CSS

 ## Other:
	Bootstrap
	Github

# Deployment

# Testing
	All pages
	Validation
	Accessibility

# Lessons learned and failures
Bootstrap is quite restrictive as I found out the hard way. My responsiveness was lost at the homepage in the main section. Seemed to be an extra item I wrote in the CSS style: margin. When using cards, margin is best not to be used. Only padding can be used to style the section as you wish for, when using bootstrap.
I found it quite difficult to find the right contrast colour as well. It took a while to find what colour to use soothing the eye (contrast) and the website (attractive).
Most complicated part though, was the form. As I had some wishes, that I was not able to code yet, I did not get the code validated.


# Credits

## Sources used to write this website:
Code Institute Course Content and Dee Mc videos
## Images 
-	Hero image is originally from tuinsmakelijk.nl (I will not continue to use this in the future)
-	Logo, 404, recipe images, plant images are AI generated with https://deepai.org
-	Fern heads image originates from https://thespruce.com (I will not continue to use this in the future)
-	Some images (chickweed, dandelion, stingy nettle, wild garlic and purslane) are partly photos of my own and partly of my friends who were so generous to let me use their photos.
All images are compressed with https://tinypng.com 
All images are converted to .webp extension with https://convertio.co 
## Texts
The texts at the website are partly generated by ChatGPT 4o mini and rewritten.
The recipes are found at other sites 
Recipes found at:
https://www.homestead-acres.com/ (dandelion jelly) 
https://www.eatingwell.com/ (aragula, cantaloupe and goat cheese salad – adapted)
https://www.learningherbs.com/ (chickweed pesto)
https://rivercottage.net/ (herby chickweed and crow garlic pakoras – adapted)


## Fonts
All fonts at the site were generated at https://fonts.google.com 
https://www.favicon.io  for a great favicon

## Colours
Colour scheme was found at https://coolors.co 
https://www.colorkit.co  gave the colours a name
https://www.w3schools.com  where I highlighted the navbar background colour from 62% to 70% to eliminate contrast errors. 

## Privacy Policy sample text
At https://developer.moneris.com/More/Compliance/Sample%20Privacy%20Policy I found a sample of a privacy policy, that I copied.

## XML-Sitemap
XML-Sitemap created with Free Online Sitemap Generator https://www.xml-sitemaps.com 



# Acknowledgements
My mentor for all his help and advice throughout the project
Kristyna for taking care I did not want too much



