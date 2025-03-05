# HTML Layout Lab - Bootstrap Learning

## Introduction:
Welcome to the Web Layout Lab! In this lab, you will practice building a responsive webpage using the Bootstrap framework. Bootstrap is a powerful front-end framework that helps you quickly design and customize websites with its pre-built components, grid system, and utilities.

The goal of this lab is to give you hands-on experience with the grid system, responsive design, and Bootstrap components like navigation bars, cards, and footers.

## Git Setup
- Fork this repository
- Clone to your local machine : `https://github.com/onja-org/w2_html_layout.git`
- Navigate into the project directory: `cd w2_html_layout`
- Create a new branch for your task: `git checkout -b your-branch-name`
- Stage and commit your changes, and push to github 

## Lab Guide: Tasks and Steps
Follow the instructions below to build your webpage using Bootstrap. This lab is meant to help you learn and experiment with different aspects of Bootstrap's features.

### 🪶 Step 1: Modify the Header Section
Use Bootstrap utility classes to apply styles to the `<header>` element:<br>

🟣 To do:
- ***Center the text*** by adding the `text-center` class.
- ***Add padding*** to the top and bottom of the `<header>` using the `py-5` class (which adds vertical padding).
- ***Set a background color*** using Bootstrap's bg-* classes (e.g., `bg-primary` for a blue background or `bg-light` for a light background).
- ***Adjust text color*** by using classes like `text-white` for white text on a dark background.

<br>

### 🪶 Step2: Navigation Bar and Menu
Create a responsive navigation menu using Bootstrap's navbar component.<br>

🟣 To do:
- ***Create the Navbar***: Add a navbar with at least 4 links: **Home, About, Services, and Contact** and use the `navbar-nav` class to group the links.

- ***Make it Responsive***:  Use the class `navbar-expand-lg` to make the navbar collapse on smaller screens, and ad the `navbar-toggler` button to create a hamburger menu on mobile screens.

- ***Style the Navbar***: Use class like `bg-dark or bg-light` for the navbar background and Change the text color with classes like `text-white` on light background `text-dark` on dark background.

- ***Add a Collapsible Menu***: Use `navbar-collapse` class to group the links and make them appear/disappear when the hamburger menu is clicked on mobile.

<br>

### 🪶 Step 3: Create the Content Layout Using the Grid System
In this step, you'll use the Bootstrap grid system to create a responsive layout with three sections: Sidebar, Main Content, and Articles.

🟣 To do:
- ***Wrap Content in a Container***: Use the `<div class="container">` element to wrap the entire layout.
- ***Create a Three-Column Layout***: Inside the container, use the `<div class="row">` element to create a row for the columns.
- ***Add three columns***:
    - **Sidebar** (3 columns wide)
    - **Main Content** (6 columns wide)
    - **Articles** (3 columns wide)

- ***Use Bootstrap classes*** like `col-md-3` for Sidebar, `col-md-6` for Main Content, and `col-md-3` for Articles.
- ***Style Each Column***:
Use classes like bg-light, bg-white, or bg-secondary to set different background colors for each section.
Use `p-3` for padding and border to add borders to the sections.
- ***Make it Responsive***: 
On smaller screens (mobile), the columns should stack into a single column automatically.


### 🪶 Step 4: Create the Footer 
Ccreate a footer for your webpage using Bootstrap's utility classes for styling. 

🟣 To do:
- ***Add a footer element*** at the bottom of the body section in your HTML file.

- ***Apply the following Bootstrap classes to style the footer***:
    - Use `bg-dark` class to add a dark background color to the footer.
    - Use `text-white` class for the text color, and making it stand out against the dark background.
    - Use `text-center` class to center the text horizontally within the footer.
    - Add vertical padding (top and bottom) to give the footer more space, using `py-5` class.
    - Add a top margin to separate the footer from the content above with `mt-4`.

- ***Inside the footer***, you can include the copyright message or any other text you'd like to display. Make sure the text is aligned and styled according to the applied classes.


## Resources to Help You with Bootstrap:
👉 [Bootstrap Documentation](https://getbootstrap.com/docs/4.1/getting-started/introduction/): Find detailed info about all Bootstrap classes and components.<br>
👉[ Bootstrap Grid System](https://getbootstrap.com/docs/4.0/layout/grid/): Learn how to layout content in columns or rows.<br>
👉 [Bootstrap Utilities](https://getbootstrap.com/docs/4.0/utilities/borders/): Discover utility classes for spacing, text alignment, and colors.<br>
👉 [Bootstrap Examples](https://getbootstrap.com/docs/4.0/examples/): Check out real-world examples and templates built with Bootstrap.
