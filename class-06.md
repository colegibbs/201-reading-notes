# Class 06 Reading Notes

## ALL INFORMATION COMES FROM DUCKETT'S JAVASCRIPT AND HTML & CSS BOOKS

## HTML & CSS

### Article: Understanding the problem domain is the hardest part of programming

- Understanding the problem domain is the hardest part of programming
- When the problem is familiar across platforms it becomes easier to learn the platform
- programming is like building a jigsaw puzzle
- understanding the problem is the most important part
- simplify the problem or understand the problem better

### Article: What’s the difference between primitive values and object references in JavaScript?

- JS is made up of primative values and object referenes
- Boolean
- Null
- Undefined
- Number
- BigInt
- String
- Symbol
- Objects
- primative variables are assigned a value directly
- when variable is assigned to an object it refers to a reference
- primative values are immutable and reference values are mutable
- obj references do not equal eachother even if they are of the same type and value

## JavaScript

### Chapter 3: Object Literals

- a key value pair is a property
- a function is called a method
- `objectName = {}`
- to access value: `objectName.keyName`
- to access value when using number of variable: `objectName['keyName']`

### Chapter 4: Document Object Model

- dom tree is a model of a web page kind of like html put in a root shape
- can select elements use the dom
- dom queries that return more than one element are called nodelists
- you can select nodelsit items with the `.item()` method or array syntax
- you can loop through a node list
- you can access and update a text node with `nodeValue`
- can access only text w/ `.textContent`
- can add or remove html content with the `.innerHTML`
- you can `.createElement()` and `createTextNode()` and `.appendChild()`
- can remove child with `.removeChild()`
- be careful using `.innerHTMl` because it's vulerable to attacks
- can remove attribules
