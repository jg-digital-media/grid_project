# JGDM Grid Project
**Last Update:** 21-04-2022: 11:08  **v4**

## **Sections**

  + [About this Project](#about-this-project)
  + [Using the Site](#using-the-site)
  + [Setup](#setup)
  + [Example Partials](#example-partials)
  + [Still to Come](#still-to-come)


## About this Project

My CSS Grid website started out as a simple re-design of a project I first made in 2017. I got to work on the redesign and the ideas kind of snowballed from there. I've turned it into a cloneable repository so anyone can use it, inspect it and it if they so wish.

The homepage for this website is divided into 3 sections of elements, each defined as a CSS Grid. The first 2 use ```grid-template-columns``` to lay out the "*grid item*" elements.

The third uses Grid Areas to assign a more custom layout to child elements of a grid area.

Grid is turned off on mobile screens where a 1 column layout is preferred where possible.   

You can visit the URL for this website at <a href="https://projects.jonniegrieve.co.uk/grid_project" target="blank">https://projects.jonniegrieve.co.uk/grid_project</a>

## Using the Site

+ This project is run on Git, GitHub and Ruby Sass

  + Make sure you're in a CLI (Such as Git Bash, Powershell or Terminal) and have the above technologies installed. I like to use Visual Studio Code text editor for easy access to all of these. 

  + In the project root directory type ```sass --watch style.scss:style.css```.

  + To switch between sass partials go into the `style.scss` partial and switch out the relevant sass partial `@imports` and note the differences in your browser. 

  + The explanations for the differences in the grid styling used are available on the ```code.html``` page.

## Setup

+ Create a Project root directory in your system ```mkdir create_a_project_root```.

+ Clone Repository to your system with Git Version Control installed. - ```git clone https://github.com/jg-digital-media/jgdm_grid_project.git```.

+ To use this project you will need a CSS compiler and a text editor.

+ Use `sass --watch style.scss:style.css` to operate Sass and make changes to Sass Code.

+ Open a sass partial text file. e.g. `grid_areas.scss`.

+ Swap out the import file and review the changes made to `index.html`.

+ Go to `code.html` for more information about what is happening with each sass partial.


## Example Partials


+ `template_columns.scss`
+ `grid_order.scss`
+ `grid_row.scss`
+ `grid_implicit.scss`
+ `repeat_notation.scss`
+ `minmax.scss`
+ `justify_self.scss`



## Still to Come */

+ `grid_areas.scss`
+ `media_queries.scss`
+ `nested.scss`


## Change Log

v4 
* additions  to notes and setup instructions

v3
* updated notes

v2
+ Added example partial images
+ Added
  + template_columns.scss";
    + grid_order.scss";
    + grid_row.scss";
    + grid_implicit.scss";
    + repeat_notation.scss";
    + minmax.scss";
    + justify_self.scss";
+ Added index.html to main navigation


v1
  + Added information for template columns, grid order and grid row.

