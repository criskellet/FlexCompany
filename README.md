# FlexCompany

## Project brief
Build a company website using FlexBox and CSSGrid.  Layout must include responsive design aadpting layout depending on screen size

## Introduction
Build a website for a company selling homemade, fabric face coverings.
Web page consists of :
  * title section - with logo and navigational bar
  * mission statement
  * product list
  * company employee section
  * contact section
  * footer section with copyright information
  
  ## Styles used
  * `@media` to adapt display for mobile phone screens.  Layout changes from a grid-like list to a column format as the page shrinks
  * `display:flex` uses a FlexBox to display employee images and information
  * `display:grid` uses CSSGrid to display the product information
  * `display-template-areas` is used to name the grid areas
  * `grid-area` is used to position product items in the grid named areas.  The product image and product description are positioned in the same grid area - overlapping
  * `justify-self` and `align-self` are used to position overlapping grid items so that the product description is on the bottom of the product image
  
  ## Other
 * Imported "Bree Serif" font from Google fonts and applied this style to the mission statement
 * Used both colour names and rgb to set colour attributes
 * Set a background image for the contact section to match the company logo
 
 ## Written by Cris Kellet on 14/12/2020
