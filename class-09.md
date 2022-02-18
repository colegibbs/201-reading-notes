# Class 09 Reading Notes

## ALL INFORMATION COMES FROM DUCKETT'S JAVASCRIPT AND HTML & CSS BOOKS UNlESS SPECIFIED AS ARTICLE

## HTML & CSS

### Chapter 7: Forms

- several types of form control
- adding text, making choices, submitting forms
- information goes to server
- can also go to database
- `<form>` has an action and method and id attribute
- `<input>` allows for the form control and input, value of type attribute contorls the input type
- `<input>` also has size, name, and maxlength attr.
- to input a passwork `type="password"`
- `<textarea>` allows for multi line comments, alternative to `<input>`
- `type="radio"` presents the user with a vareity of options with selectable buttons next to them
- `type="checkbox"` presents with a textbox
- `<select>` instead of `<input>` can allow for the use of a dropdown list, use `<option>` tags nested in the `<select>` tag
- if you want users to input a file use the `<input>` tag with `type="file`
- `type="image"`
- can add `required attribute for form validation`
- `type="date"`
- `type="email`
- `type="url"`
- `type="search`, `placeholder=""` attri will get a place holder word in the search bar

### Chapter 14: Lists, Tables & Forms

- `list-style-type` selector allows you to pick the marker type
- `list-style-image:url("")` selector allows for an image as a marker
- `list-style-position` allows you to position the marker in relation to the text
- `list-style: markerStyle image position` is short hand
- table properties
  - `width`
  - `padding`
  - `text-transform` converts the content of the table headers to uppercase
  - `letter-spacing`, `font-size`
  - `border-top`, `border-bottom`
  - `text-align`
  - `:hover` to highlight table rows when hover
  - `empty-cell` allows you to adjust an empty cell
  - `border-spacing`, `border-collapse` between cell spacing adjustment
- styling forms
  - `:focus` changes the background color when its used
  - `:hover` changes style when user hovers
  - can style submit button
  - can style entire fieldsets and legends
  - can change cursor style

## JavaScript

### Chapter 6: Events

- there are many different types of events
- events are fired or raised
- events trigger scripts
- there is a specific way to use parameters with event listeners
- you sometimes have to support older verison
- elements can be targeted from outside in or inside out
- you can prevent default behavior with a few different calls
- use event delegation 
- There are many different event types, all with different functions