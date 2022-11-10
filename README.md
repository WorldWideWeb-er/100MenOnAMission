# 100MenOnAMission

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
- [My process](#my-process)
  - [Built with](#built-with)
  - [Site Maintenance ](#site-maintenance)
- [Update Log](#update-log)
- [Author](#author)

## Overview

100+ Men on a Mission is a charity that brings 100 or more men together every quarter to help fund a charity in the Des Moines, Iowa area.

Their previous website was outdated with systems that became difficult to edit and work with, so I stepped up and asked the groups founder Mike Schneider if I could undertake a new site redesign.

## My process

### Figma Designs

Working with Figma, a very basic wireframe layout and landing page were created.

Once the landing page layout was finalized, the color palette was created that would still honor the groups colors.

Layout of the remaining pages would follow. (To the best of my ability as I am a developer first, a UI/ UX designer second)

### Built with

- CSS custom properties
- Flexbox
- Mobile-first workflow
- SCSS
- BEM Model

### Site Maintenance

CSS/SCSS Changes

- All css was made through SCSS found in the 'scss' file
- Each page has its own folder titled respectively

layout-general Folder

- Inside holds the SCSS for the footer, header, and nav classes refrenced on every '\_index' page within every folder
- Use these files to change every class on every page

Files named 'globals' & 'util'

- 'globals' folder is refrenced globaly so items such as 'colors' have SCSS variables that can be refrenced anywhere
- 'util' folder contains functions and breakpoints. These are refrenced with an '@use "../util/" as u;' at the top of every SCSS page.

## Update Log

Initial completion as of February 09, 2022, sent into review for further editing.

## Author

- Website - [Nate Weber](http://nateweber.name/)
- Note from Author: This is my first attempt at a full website outside of an educational project.
