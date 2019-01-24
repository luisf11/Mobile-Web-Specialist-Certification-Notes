# Mobile Web Specialist Certification

## Responsive web design fundamentals

* Viewport 

  Define area of the screen that the browser can render content to.

  To calcultate the viewport scale is: 
   ```
   actual size / device pixel ratio
   ```
    Viewport Example
   ```
    <meta name=viewport" content="width=device"-width,initial-scale=1">
   ```

* DPR
   
   (Device pixel Ratio)

* DIP 

  (Device independent Pixels) unit that relates pixels to real distance.

* Hardware pixels
  
  Actual pixels of the divice.


# Inherit css keyword

The inherit keyword specifies that a property should inherit its value from its parent element.

# Media queries

Media queries are useful when you want to modify your site or app depending on a device's general type (such as print vs. screen) or specific characteristics and parameters (such as screen resolution or browser viewport width).

Media queries are used for the following:

* To conditionally apply styles with the CSS @media and @import at-rules.
* To target specific media for the <link>, <source>, and other HTML elements.
* To test and monitor media states using the Window.matchMedia() and MediaQueryList.addListener() JavaScript methods.

# Grid layout (Flex box)

The Flexible Box Module, usually referred to as flexbox, was designed as a one-dimensional layout model, and as a method that could offer space distribution between items in an interface and powerful alignment capabilities. This article gives an outline of the main features of flexbox, which we will be exploring in more detail in the rest of these guides.

When we describe flexbox as being one dimensional we are describing the fact that flexbox deals with layout in one dimension at a time — either as a row or as a column. This can be contrasted with the two-dimensional model of CSS Grid Layout, which controls columns and rows together.

# Responsive layouts patterns

Some of them:

* mostly fluid
* layout Shitter
* column drop
* off canvas