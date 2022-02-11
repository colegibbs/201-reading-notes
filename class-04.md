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
    - positions element in realtion to its containing element
    - absolutle elements stay in the same place while users scroll
  - `fixed`
    - form of absolut element
    - do not move when user scrolls
  - `floating`
    - can position it to the far left or right of the containing box
- when chencing position the boxes can sometimes overlap
  - the `z-index` property allows you to control which box is on top

## JavaScript

### Chapter 3

#### What is a function?

- lets you group statements to perfor a task
- accept parameters
- return values
- call funtions to use them

#### Immediately Invoked Function Expressions

- iffes are function that are not given a name
- they are executed once the interpreter hit them
- they are written like a function expression, but have `()` around the function and after the last `}` there is another set of `()` that is also inside the first parenthasis

### Article: 6 Reasons for Pair Programming

#### How Does Pair Programming Work?

- Driver: writes all of the code
- Navigator: Tell the driver what to write, documents, no code written, research solutions
- 4 aspects to learning a language
  - listening
  - reading
  - writing
  - speaking
- pp works on all of these

#### Greater Efficency

- pp takes a little bit longer but also saves time on the debugging end so it actually saves time overal
- higher quality code is generated

#### Engaged Collaboration

- results in more engagement
- less likely to procrasonate
- programmers can find solutions together so confidence is boosted

#### Learning From Fellow Students

- exposes developers to peers solutions
- fills the gaps in experince and technique 

#### Social Skills

- improves social skills
- improves communication skills
- employers want people who work well with others

#### Job Interview Readiness

- employers will have an applicant pp with an empolyee to see how they fit in with the team
- communication skills are as important as technical skills

#### Work Environment Readiness

- knowing how to pp give you a one up on the CS grads who still need to learn it