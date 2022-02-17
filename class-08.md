# Class 08 Reading Notes

## ALL INFORMATION COMES FROM DUCKETT'S JAVASCRIPT AND HTML & CSS BOOKS

## Learn CSS - Layour

- `display` property determins if the element acts like an `inline` or a `block`
- it also determins how child elem should behave with `flex`
- flexbox determines layout horizontally or vertically

## HTML & CSS

### Chapter 15: Layout

- html block will either be a block or inline box
- Block Elements
  - start on a new line
  - `<h1>`
  - `<p>`
- Inline Elements
  - Flow in between text around it
  - `<img>`
- if a block element sits inside a block element the outside one is called the parent
- `<div>` is ofter a parent element

#### Controlling the Position of Elements

- `position:` propetry
- values:
  - `normal flow`
    - how it normally is
  - `relative`
    - allows you to shift the box top, right, left, or bottom of where it would normally be
  - `absoulte`
    - positions element in realtion to its containing element
    - absolutle elements stay in the same place while users scroll
  - `fixed`
    - form of absolut element
    - do not move when user scrolls
  - `floating`
    - can position it to the far left or right of the containing box
- when chencing position the boxes can sometimes overlap
  - the `z-index` property allows you to control which box is on top
