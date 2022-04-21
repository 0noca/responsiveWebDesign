## Start of Responsive web design
```
Padding: 
Border:
margin:
```

An element's `padding` controls the amount of space between the element's content and its border.

An element's `margin` controls the amount of space between an element's border and surrounding elements.

CSS allows you to control the padding of all four individual sides of an element with the ` padding-top, padding-right, padding-bottom`, and `padding-left`  properties.

To change the CSS of a certain group of items use [attr=value] like [type="radio"]

Relative units, such as em or rem, are relative to another length value. 
For example, em is based on the size of an element's font. 
If you use it to set the font-size property itself, it's relative to the parent's font-size.

To define a variable in HTML use
--[variable-name]: e.g color;


To use it in CSS add this;
var(--[variable name])
```
Text is often a large part of web content. CSS has several options for how to align it with the text-align property.

text-align: justify; spaces the text so that each line has equal width.

text-align: center; centers the text

text-align: right; right-aligns the text

And text-align: left; (the default) left-aligns the text.
```

Instead of adjusting your overall background or the color of the text to make the foreground easily readable, you can add a background-color to the element holding the text you want to emphasize. This challenge uses rgba() instead of hex codes or normal rgb().

The box-shadow property applies one or more shadows to an element.

The box-shadow property takes the following values, in order:

    offset-x (how far to push the shadow horizontally from the element)
    offset-y (how far to push the shadow vertically from the element)
    blur-radius
    spread-radius
    color
e.g box-shadow: 0 10px 20px rgba(0,0,0,0.19), 0 6px 6px rgba(0,0,0,0.23);


The blur-radius and spread-radius values are optional.
