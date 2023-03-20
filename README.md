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
To update the root element, we use the html root size by adding that to the stylesheet.<br/>
example: html { font-size: 25px}

### Vh an Vw
The are viewport are relative units of measurements based on the size of the viewport, we can set a percentage of that screen to display the content. <br/>
Great to use for for banners and responsive design.
<br/>

### Default Browser Styles
Open the dev tools to see the browers defaults. They can be found in the elements tab. Then on the right we can see the styles applied to each element that is highlighted or selected. 
<br/>
<br/>
You know we are using the default if it says "user agent stylesheet". When we add custom css, it will show our stylesheet, and below it, it will show what was changed from the default. 
<br/>
<br/>
You can use the Devtools to test changes without actually affecting the CSS file. Just note that once you refresh, it will not save those changes, as they were temporary and only used for testing. 
<br/>

### Calc Function
This CSS function allows you to perform calculations when Specifying property values. It can be used with the length, time, percentage, number or interger values.
<br />
<br />
Calc function is best used to make sure to avoid scrolling by setting value that is calculated based on either the viewport height or width.
<br/>
example: height: calc(100vh - 140px);
<br/>

### Min-Height, Max-Height
This is used to limit the sizing parameters even if the viewport size changes. This is helpful so that the content viewed is never to large or too small based on the viewport. 
<br/>
By default if we do not set height and width, they are set to auto and these values for each element  is are set to "auto". <br/>
<br/>
We can also set an overflow property to either hidden or scroll when the context exceeds our height or width set in CSS.

