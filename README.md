# CSS Units

### Pixels, Font-Size, Width, Height
Pixels are definite values. So the font will be the same pixel size on large and small screen. It will not be responsive. <br/>

Normally the width on block elements is default to the entire width of the screen. When we set this property in pixels, it will shorten the block on large screen, and depending on the size of smaller screens, it can take up the entire width. It will not decrease in size and remain the same pixel size given.
<br/>
* example: font-size: 60px; width:375px;
<br/>

### Percents
To show an example of how % works we will create a parent div with the class outer, and a nested child div with the class inner.  Please note that when using nested elements that their percentage is based on the size of the parent element. <br/>
<br/>


### EM Units
These units are also relative and based off the parent element.
The number preceeding the em unit tells the browser how many times greater the font should be than the base font-size.The default browser font size is 16px<br/>

* Example: <br/>
* Parent font-size:16px <br/>
* child font-size: 2em is 2*16px or 32px

### REM Units
REM units are also relative but not based on the parent element, but rather the root html element. Default is also 16px.
<br/>
<br/>

### Vh an Vw

### Calc Function

### Min-Height, Max-Height
