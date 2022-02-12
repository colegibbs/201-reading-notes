# Class 05 Reading Notes

## ALL INFORMATION COMES FROM DUCKETT'S JAVASCRIPT AND HTML & CSS BOOKS

## HTML & CSS

### Chapter 5: Images

#### Chosing Images for your Site

- need to use stock photos
- get get into trouble for just using any pic
- many images look best on a simple consistent background

#### Storing Images On Your Site

- store images in serparate folder and subfolders(if you need)

#### Adding Images

- `<img src="sourceOfImage" alt="textThatRendersIfImagesDoesnt" title="additional info"/>`
- `src` and `alt` are required, but title isn't

#### Height and Width of Images

- `height` attribute give the image a height in px
- `width` attribute give the image a width in px
- good to specify h and w b/c of the way the browser renders

#### Where to Place Images in your Code

- image places:
  - before a p tag
  - in the p tag before the text
  - in the middle of the p tag content
- Block level element will always appear on a new line
- Inline element sit in a block level element and don't start on a new line

#### Old Code: Aligning Images Horizontally

- the `align` attribute should not be used and coders should change image possition in css
- good to know because might see it in older code
- `align` can be assigned `left` or `right`

#### Olde Code: Aligning Images Vertically

- `align` can also be assigned values of `top`, `middle`, and `bottom` for vertical alignment
- using these values dictates where the p tag first line will apear next to the img

#### Three Rules For Creating Images

- save images in the right format
- websites usually use `jpeg`, `gif`, or `png`
- chosing the wrong image format could effect sharpness
- Save Images At the Right Size
  - save images to the same size it will display on your website
  - doing other than this can cause distortion
- Measure Images in Px
- when saving an image measure it in px

#### Tools To Edit and Save Images

- adobe photoshop is very useful when editing imgs and designing sites

#### Image Dimensions

- You can change the size and shape of images

#### Cropping Images

- Make sure your photot is cropped properly for the style of photo it is

#### Vector Images

- if you want to use a vector image you need to save and use the bitmap image version of the images

### Chapter 11: Color

#### Foreground Color

- `color` lets you specify text color
- can specify colors using RGB values, hex codes, and color names

#### Understanding Color

- saturation is how much gray is in the color
- brightness is how much black is in the color

#### contrast

- when deciding foreground and background color it's important to have enough contrast to see the text

#### CSS3: Opacity

- you can add opacity with `opacity:` 0.5 is 50% opacity and 1 is 100%
- can also specify with `background-color` using rgba which is RGB but with a fourth value specifying opacity : `rgba(0,0,0,0.5)`

#### CSS3: HSL and HSLA

- `background-color: hsl(0,0%,78%);`
  - first number represents the hue as a degree
  - second is saturation in %
  - third is lightness in %: 0% is white and 100% is black
- `background-color: hsla(0,100%,100%,0.5)'`
  - same as hsl except fourth number represents alpha which is transperency from 0 to 1
