# Class 03 Reading Notes

## ALL INFORMATION COMES FROM DUCKETT'S JAVASCRIPT AND HTML & CSS BOOKS

## HTML & CSS

### Chapter 3: Lists

#### Ordered Lists

- ordered lists are created using `<ol>`
- the items in the list should be put in the `<ls>` tag
- lists should be styled in CSS though the numbering can be changed in html

`<ol>`
  `<ls>`list item`</ls>`
  `<ls>`list item`</ls>`
`<ol>`

#### Unordered List

- unordered list are created with `<ul>`
- each item in the list is made using `<ls>`, just like an ordered list
- lists should be styled in css

`<ul>`
  `<ls>`list item`</ls>`
  `<ls>`list item`</ls>`
`</ul>`

#### Definition Lists

- created with `<dl>`
- usually is made up of a list of terms
- `<dt>` is used for the definition term or the word that is to be defined
- `<dd>` is used to contain the defintion

`<dl>`
  `<dt>`definiton term`<dt>`
  `<dd>`term definition`<dd>`
  `<dt>`definiton term`<dt>`
  `<dd>`term definition`<dd>`
`</dl>`

#### Nested List

- you can put a list inside of an `<ls>` to create a nested list

#### Take Aways

- ordered, unordered, and definition lists
- ordered lists use numbers
- unordered lsits use bullets
- definition lists are for definitions
- lists can be nested

### Chapter 13: Boxes

#### Box Dimensions

- width, height
- box is just big enough to hold the content by default
- use width and height properties in css to change the box size
- you can assign thes properties with pixels, percentages or ems
- If you use a percentage value, the size is relative to the size of the parent box
- ems is realitive to the size of the text and changes with screen size

#### Limiting Width

- min-width, max-width
- in dynamic page design the min or max width is the min width a window can display and the max width a window can display
- These are used to ensure that the pages are readable

#### Limiting Height

- min-height, max-height
- used in the same was as limiting width

#### Overflowing Content

- overflow
- tells the browser if the content in the box is to big for the box it can have one of the following values
- hidden
- hides the extra content that doesn't fit in the box
- scroll
- renders a scroll bar so the user can scroll through the content
- Is useful because some browsers allow users to make text as big as they want, causing overflow

#### Border, Margin, and Padding

- if you specify a width, the border, margin ,and padding are added to its width and height
- border
  - border sperarates the edge of one bos from another
- margin
  - sits outside the border
  - can set the the margin to create space between adjasent boxes
- padding
  - space between boarder and content
  - bigger border can increase content readability

#### White Space and Vertical Margin

- padding and margin are used to add space bwtween item on the page
- white space is the space between items
- you don't want the text to touch the boarder of a box
- betwen box white space
- if tow margins touch in the browser, the larger one only will show or if they are the same value, only one will show up

#### Border Width

- border-width
- controls border width
- values: pixles or thin, medium, thick
- no percentages
- you can control each side of the border with `border-top-width: ;` format
- clockwise asignmens also work

#### Border Style

- `border-style`
- values :
  - `solid` is a solid line
  - `dotted`
  - `dashed`
  - `double`
  - `groove`
  - `ridge`
  - `inset` appears embedded in the page
  - `outset` appears like its comming out of the screen
  - `hidden`/`none` none is shown
- can change border sides with `border-top-style` syntax

#### Border Color

- `border-color`
- can control the colors on differne side s with `border-top-color` syntax
- can shorthand with clockwise assingment

#### Shorthand

- `border`
- can specify width, style and color in one property
- syntax: `border: 3px(width) dotted(style) #0088dd(color);`

#### Padding

- `padding`
- specifies spacebetween content and border
- defined with pxels usally
- `padding: 10px`
- can do top, left, right, and bottom as well
- can use clockwise shorthand

#### Margin

- `margin`
- gap between boxes
- commonly uses pixels
- if two margins touch the larger one take persidence
- `margin: 20px`
- `margin: 1px 2px 3px 4px;`
- `margin: 20px(vertical) 10px(horizontal)`
- need to specify margin for every element b/c there is less inheritance

#### Centering Content

- set left and right margin to auto
- need to set a width for the box to center or it will take up the full page
- you should also `text-align` the text to be centered or not

#### IE6 Box Model

- when width is specified the margin and padding should be added to the width of the box

#### Change Inline/Block

- `display`
- allows you to turn inline into block or vice
- `inline` causes block level element to act like inline element
- `block` inline element to act like block
- `inline-block` causes block eleement to flow like an inline elemnt
- `none` hides the element

#### Hiding Boxies

- `visibility`
- allows you to hide boxes but leaves a spce where the elemtn would be
- values:
  - `hidden` hides the element
  - `visible` shows the element
- if you want the elemtn to be hidden with no space use the dispay property with a `none` value

#### Border Images

- `border-image`
- applies an image to the boarder of any box
- propety need three things:
  1. the url image
  2. where to slice the image
  3. what to do with the stright edges
      - `stretch` stretches the image
      - `repeat` repeats the image
      - `round` like repeat but scales the image
- must also have a border width
- `border-image: url("url") 11 11 11 11 stretch`

#### Box Shadows

- adds a shadow
- horizontal offset: negative values position the shadow to the left
- vertial offset: negative values postition shadow to the top
- blur distance: if not included the shadow has a solid line
- spead of shadow: positive value will cause shadow to expand and negative will make it contaract
- inset keyword will let you create an inner shaddow
- `box-shadow: 5px 5px 5px 5px #777777`

#### Rounded Corners

- `border-radius`
- side of radius in px
- can specify top bottwon right and left
- can use clockwise shorthand
- `border-radius: 10px`

#### Elliptical Shapes

- `border-radius`
- can change horizon by putting another px value
- `border-radius: 80px 50px` horisontal and vertical respectively
- can target corner with `border-top-left-radius`

#### Take Aways 2

- css treats html as if it has its own box
- css controls box dimentsions

## JS

### Chapter 4: Decisions and Loops

#### Switch Statements

- starts with switch value
- each case is code that should be run if this variable is a certain value
- provides bettwer performance than multiple if statements

#### Using Switch Statements

- each case ends with a `break;` keyword

#### Type coercion and weak typing

- if you use a data type that js didn't expect js will try to make it work
- js will change data types behind the sense this is called type coersion
- js is weak typing b/c the type can change
- this causes errors and thats why we use `===` insead of `==`

#### Truthy and Falsy values

- values that will evalues to false or true are called falsey and truthy values respectively
- truthy: true, 1, 'carrot', 10/5, 'true', '0', 'false'
- falsey: false, 0, '', 10/'score' (NaN), no assignment variable

#### Checking Equality and Existence

- a urary operator returns a reslutl with just one operands

#### Short Circut Values

- You can assign a value to something like this:
- `var artist = 'alskdjf'`
- `var artistA = (artist || 'Unknown')`
- if artist exists then asisng artistA with the same value if not assign 'Unknown'

#### Loops

- Loops have conditions and will run as long as the condition is true
- for loops
  - code needs to run a number of times
- while
  - don't know how many times the code will need to run
- do while
  - similar to while
  - it will run the code block at lease once
  - then will check condition

#### Key Loop Concepts

- kewords will be used in a loop
- `break;` causes the loop to stop
- `continue;` causes the current iteration to stop and then update and then chekc the contidion.
- loops are useful when dealing with arrays
- if a loop contains a lot of items it can take a long time to load
- variable that can be outside the loop should be outside the loop
