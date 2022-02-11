# Class 04 Reading Notes

## ALL INFORMATION COMES FROM DUCKETT'S JAVASCRIPT AND HTML & CSS BOOKS

## HTML & CSS

### Chapter 4: Links

#### Writing Links

- created w/ `<a>`
- user clicks on text between opening and closing tags to go to link
- syntax : `< a href="url">Text<a/>`

#### Linking to Other Sites

- use full or absolute url

#### Linking to Other Pages on the Same Site

- you can use relative urls

#### Directory Structure

- top level folder is the root folder
- relationship described using family tree language

#### Email Links

- `mailto:`
- syntax: `<a href="mailto:email@email.com">Email Me</a>`
- looks like any other link when rendered

#### Opening Links in a New Window

- `target`
- `<a href="url" target="_blank">Link Text</a>`
- adding the `target="_blank"` attribute will cause the link to open in a new window
- used when linking to another website

#### Linking to a Specific Part of the Same Page

- can link to content on the same page
- assign and id to the place you want to link in html
- use the id as the href in the `<a>` tag with a proceding `#`

#### Linking to a specific Part of Another Page

- similar to linking on same page
- use the relative path and then add a /#idName to the end to link to that part of the other page

### Chapter 15: Layout

#### Key Concepts in Positioning Elements

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
    - 