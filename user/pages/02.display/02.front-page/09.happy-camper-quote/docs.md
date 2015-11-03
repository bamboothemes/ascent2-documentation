---
title: Happy Camper quote
taxonomy:
    category: docs
---

## What is this?
The quote that sits below the recent work module on the front page below the main content.

![Camper](/images/camper/camper.png)


## Steps to recreate this layout

This item is a custom html module published to the grid17 module. 

The background colour used for this row is one of the row styles that can be assigned by row via the template settings. See below for more details.

** Module Manager **
1. Navigate to the module manager in your Joomla administrator via extensions > Module Manager
2. Click new
3. Select the custom html type module
4. Copy the markup displayed below into the text area of the custom module.
5. Assign the module to a module position (sidebar2).
6. Ensure the module is published
7. Give the module a title
8. Set the module title to be hidden
9. Save your new module.

## Markup used in the module

<pre>&lt;blockquote>
	&lt;p>Cras nec lorem eget ligula varius aliquet at et mi.&lt;/p>
	&lt;/blockquote>
	&lt;p style="text-align: right;">&lt;em>A Happy Camper&lt;/em>&lt;/p>
</pre>

## Row Styles set in the template
The background colour used for this row is determined by the template and can be found in the theme panel in the template administrator.

The row style is applied to a row of modules grouped by their respective rows.

- Top row - top1,top2,top3,top4
- Banner row - banner
- Grid1 row - grid1,grid2,grid3,grid4
- Grid2 row - grid5,grid6,grid7,grid8
- Grid3 row - grid9,grid10,grid11,grid12
- Grid4 row - grid13,grid14,grid15,grid16
- Grid5 row - grid17,grid18,grid19,grid20
- Grid6 row - grid21,grid22,grid23,grid24
- Bottom row - bottom1,bottom2,bottom3,bottom4,bottom5,bottom6
- Top row - top1,top2,top3,top4

** Row Styles in the template settings **
![Row styles](/images/row-styles/row-style.png)

** Example Options **
![Row Style Options](/images/row-styles/row-style-options.png)