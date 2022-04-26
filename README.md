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


`The blur-radius and spread-radius values are optional.`

The following table shows how the different text-transformvalues change the example text "Transform me":
```
    Value	Result
    lowercase	"transform me"
    uppercase	"TRANSFORM ME"
    capitalize	"Transform Me"
    initial	Use the default value
    inherit	Use the text-transform value from the parent element
    none	Default: Use the original text
```
## Relative
When the position of an element is set to `relative`, it allows you to specify how CSS should move it relative to its current position in the normal flow of the page. It pairs with the CSS offset properties of `left` or `right`, and `top` or `bottom`. These say how many pixels, percentages, or ems to move the item away from where it is normally positioned.
## Absolute
The next option for the CSS position property is `absolute`, which locks the element in place relative to its parent container. Unlike the relative position, this removes the element from the normal flow of the document, so surrounding items ignore it. The CSS offset properties `(top or bottom and left or right)` are used to adjust the position.
## Float
The next positioning tool does not actually use position, but sets the float property of an element. Floating elements are removed from the normal flow of a document and pushed to either the left or right of their containing parent element. It's commonly used with the width property to specify how much horizontal space the floated element requires.

## Gradients
    to greate gradients use:
`background: linear-gradient(gradient_direction, color 1, color 2, color 3, ...);`
example:
`background: linear-gradient(90deg, red, yellow, rgb(204, 204, 255));`

## @keyframes

```
  #rect {
    animation-name: rainbow; <!-- Name of the @keyframes down the lines -->
    animation-duration: 4s; <!-- Duration of the keyframe -->

  }

  @keyframes rainbow { <!-- Start of the keyframes, start middle and end. -->
    0% {
      background-color: blue;
    }
    50% {
      background-color: green;
    }
    100% {
      background-color: yellow;
    }
  }
```

Use `animation-fill-mode: forwards;` to keep the animation after animation has ran
Use `animation-iteration-count: 3;´ to run the animation as many times as you want

animation-timing-function: linear;
animation-timing-function: ease-out;

Audio Player on website
```
<audio id="meowClip" controls>
  <source src="audio/meow.mp3" type="audio/mpeg">
  <source src="audio/meow.ogg" type="audio/ogg">
</audio>
```

## Accesibility

Date picker: input type="date"

# Media queries

@media (max-width: 100px) {
p {
text-size: 10px;
}
}

