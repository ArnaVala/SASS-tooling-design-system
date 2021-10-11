# Module 3: JAVASCRIPT - SASS

## Description of the project

With this project I wanted to start setting up a base design system using SASS for myself and am will continue to add to it. There is little to see in the DOM, so please view the codes (sass files) to see further how I have implemented the SASS tooling to my code. 

<br>
I started by setting up spacing, typography and color systems with functions,mixins and mapping. These are in my opinion the fundamental and most important parts of any digital product or design, as almost all elements of a design are constructed with those three concepts.
Then I have added to the basic utilities such as breakpoints, borders. 
I will continue to add utils for elevation, motion, icons etc here.
<br>

## Some SASS tools I have used in this project:
- Functions: 
- Mixins
- Mapping
- Folder structure
- Variables
- Themes
- GULP for building styles to CSS and watching for changes.

### For the MODULE 3 - SASS PROJECT


### FOLDER STRUCTURE
I set up a folder structure based on the 1-7 system. Each folder
has it's own directory, which is then imported to the main (style.scss) file.

#### 0-Settings:
Put vendor and reset files here. (bootstrap, bourbon, normalize etc.)
I placed also the fluid-font-utils here.
<br>

#### 1-Themes:
Theme settings - colors, fonts, spaces etc. Set up so the theme can be easily changed dependent on project.
<br>
- Color variables
- Spacing variables
- Breakpoints variables
- Typography variables

#### 2-Utilites:
The base folder includes classes, variables, mixins and functions for the foundation for developing (building) a site with a coherent system. Each utility has it's folder, in which there are functions, mixins and mapping.
<br>
- Border functions, mixins, mappings
- Breakpoint mixins, mapping
- Color functions, mixins, mapping
- Space - functions, mapping.
- Typography: Mapping, mixins, functions for font-sizes and typography structure. 
- Fluid font function & mixins. Function
To do:
- Layout grid, containers: mixins.
- Elevation/ Shadows / Depth
- Motion
<br>

#### Base:
Base styling classes specific to site (atoms)
  -In progress.
<br>

#### Modules:
- In progress: here come smaller elements/components:
e.g buttons, heading blocks etc.

#### Layout:
Basic page layout components styling: navigation, header, footer, main etc.
- In progress

#### Sections:
Page sections styling.
- In progress

#### Pages:
Individual page template styling.
- In progress
