# JGDM Grid Project
**Last update:** 06-07-2021: 12:11


## About this project.

It started out as a simple re-design of a website project I first made in 2017 about CSS Grid when it was a bit newer than it is today. and the ideas kind of snowballed from there. I've turned it into a cloneble repository so anyone can use it and inspect it if they so wish.

The homepage for this website is divided into 3 sections of elements, each defined as a CSS Grid. The first 2 use ```grid-template-columns``` to lay out the "grid item" elements.

The third uses grid areas to assign a more custom layout to child elements of a grid area.

Grid is turned off on mobile screens where a 1 column layout is preferred where possible.

## Setup

+ Create a Project root directory in your system ```mkdir create_a_project_root```.

+ Clone Repository to your system with Git Version Control installed. - ```git clone https://github.com/jg-digital-media/jgdm_grid_project.git```.


## Using the site

+ This project is run on Git, GitHub and Ruby Sass

  + Make sure you're in a CLI and have the above technologies installed.

  + In the project root directory type ```sass --watch style.scss:style.css```

  + To switch between sass partials go into the style.scss partial and switch out the relevant sass partial file and note the differences. 

## Example Partials

+ grid_areas.scss
+ grid_order.scss
+ grid_row.scss
+ template_columns.scss

## changelog

