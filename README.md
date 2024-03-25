### CSS Units: Absolute

1. cm : Centimeters
2. mm : Millimeters
3. in : Inches
4. px : Pixels (1px = 1/96th of 1in)
5. pt : Points (1pt = 1/72 of 1in)
6. pc : Picas picas (1pc = 12pt)

### CSS Unit: Relative

1. %   : To parent element
2. em  : To font-size of parent element
3. rem : To font size of the root element
4. vw  : To 1% of viewport width
4. vh  : To 1% of viewport height

### CSS Positioning

* Static    | Not effected by tblr (top, bottom, left, right) properties/values
* Relative  | tblr values cause element to be moved from its normal position
* Absolute  | Positioned relative to its parent element that is positioned "relative"
* Fixed     | Positioned relative to the viewport
* Sticky    | Positioned based on the scroll position

### How to achieve responsive design

* Set the viewport / scale
* Use fluid widths as opposed to fixed
* Media queries - Different CSS styling for different screen sizes
* Rem units over px
* Mobile first method