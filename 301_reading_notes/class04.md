# CSS Grid

CSS Grid Layout is the most powerful layout system available in CSS. It is a 2-dimensional system, meaning it can handle both columns and rows, unlike flexbox which is largely a 1-dimensional system. CSS Grid Layout (aka “Grid”), is a two-dimensional grid-based layout system that aims to do nothing less than completely change the way we design grid-based user interfaces. CSS has always been used to lay out our web pages, but it’s never done a very good job of it. First, we used tables, then floats, positioning and inline-block, but all of these methods were essentially hacks and left out a lot of important functionality (vertical centering, for instance)
 Flexbox helped out, but it’s intended for simpler one-dimensional layouts, not complex two-dimensional ones (Flexbox and Grid actually work very well together). Grid is the very first CSS module created specifically to solve the layout problems we’ve all been hacking our way around for as long as we’ve been making websites.


## Getting started

To get started **you have to define a container element as a grid with display: grid**, set the column and row sizes with grid-template-columns and grid-template-rows, and then place its child elements into the grid with grid-column and grid-row.

## Terminology

**Grid Container**
The element on which display: grid is applied. It’s the direct parent of all the grid items. 

**Grid Item**
The children (i.e. direct descendants) of the grid container.

**Grid Line**
The dividing lines that make up the structure of the grid. They can be either vertical (“column grid lines”) or horizontal (“row grid lines”) and reside on either side of a row or column.

**Grid Track**
The space between two adjacent grid lines. You can think of them like the columns or rows of the grid.

**Grid Cell**
The space between two adjacent row and two adjacent column grid lines.

**Grid Area**
The total space surrounded by four grid lines.

**Grid Properties**

### Properties for the Grid Container

1. display
2. grid-template-columns
3. grid-template-rows
4. grid-template-areas
5. grid-template
6. grid-column-gap
7. grid-row-gap
8. grid-gap
9. justify-items                                                   
10. align-items                                     
11. place-items                                                 
12. justify-content
13. align-content
14. place-content
15. grid-auto-columns
16. grid-auto-rows
17. grid-auto-flow
18. grid


### Properties for the Grid Items

1. grid-column-start
2. grid-column-end
3. grid-row-start
4. grid-row-end
5. grid-column
6. grid-row
7. grid-area
8. justify-self
9. align-self
10. place-self