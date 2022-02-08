# Class 01 Reading Notes

## Introduction

Book structure :

1. HTML - How to use html
2. CSS - How to use css with presentation and layout
3. Practical- Information for better websites

Accessing Websites:

1. Browser - Software, Chrome or Safari, get updated
2. Web Servers - Computer that hosts the website, always have internet, web hosting compaies who rent out servers or company servers
3. Devices - Different devices have different sized screens which changes the look of the website
4. Screen Readers - program that read the words on a screen, laws that require websites to be screen reader compatable,

You are seeing html and css on a website. Also includes other content like pics and vids. Also use JS or Flash.

small sites can use just html and css. Bigger sites use managment systems among other things and require servers. Very large sites youse databases to store data. New versions of html and css come out.

### The Web

1. connect to ISP and type domain name
2. conputer reaches DNS and tell your computer the domain addresses IP
3. The IP allows your computer to connnect to that specific server

## Chapter 1

Elements define the outline and structure of the page. Each element has an opening and closing tag. the h and p tags are inside the body and the body is inside the html tag.

1. Opening tag: `<p>`
2. Closing tag: `</p>`

Attributes tell more about the tag and live in the opening tag.

`<p lang="en-us">Paragraph in English</p>`

`lang="en-us"` is the attribute of this p tag. `lang` is the name and `"en-us"` is the value. Should have double quotes. Most attribures can only be used on a few specific tags. `lang` can go on any element. attribute values are already defined or follow a format. `lang` is short for language.

## Chapter 2

- `<b>` - bold
- `<i>` - italic
- `<sup>` - superscript (like an exponent)
- `<sub>`- subscript
- `<br />` - line break
- `<hr />` - horizontal line
- `<em>` - used to emphasis text and apears as italics
- `<blockquote>` - has an attribute cite which is a link to where the quote is from. a p tag should be inside this tag and is the quote itself.
- `<q>` - used to identify quotes inside of a line. the browser should render as ", but explorere doesnt do this so people don't use it.
- `<abbr>` - used around an abbreviation. has attribute title that is the full name from the abbreviation.
- `<cite>` - Is used to site a reference and it rendered as italics.
- `<dfn>` - Used to show that this is the first time this content is being talked about like a concept. some browsers italic this but others don't.
- `<address>` - contains information about the author.
- `<ins>` - shows what has been added to the document with an underline.
- `<del>` - Shows what has been removed from the document with a strikeout.
- `<s>` - used to show that something is no longer accurate, but is still displayed. renders as a strikeout.

## Chapter 8

Some characters are used by html an in order for you to use them you need to use an excape.

- `<`
- `>`
- `&`
- `"`
- The cent sign
- pound sign
- yen sign
- euro sign
- copywrite symbol
- registered trademark
- trademark
- left single quote
- right single quote
- left double quotes
- right double quotes
- multiplication sign
- division sign

all have there own code if you want them to apear in your webpage.

DOCTYPES tells the browser which html you're using.
To make a comment use `<!--` and `-->`.
id anc class attribues let you identify elements.

`<div>` lets you group elements together in a single element.

`<span>` is used to group text together like a div groups elements. Useful with CSS.

`<iframe>` allows a window to display on your site that is from another site. Has attributes: width, height, and src.

`<meta>` is inside the head element. No closing tag. Can use any at once. has attributes name and content. The attributes are related. description, keywords, robots, author, pragma, expires are all attributes.

## Chapter 17

`<article>` any section of the page that could make sense alone.

`<aside>` when used inside an `<article>` should contain relevant, but not necisarry information to the article. When outside of an `<article>` it is meant to hold information about the webpage.

`<section>` groups related content together and each section has its own heading in it. Might contain several `<article>` together. Can be used to split a long `<article>` into sections.

`<hgroup>` groups together h tag headings.

`<figure>` wraps and image and a `<figcaption>`. The `<figure>` defines the image as a figure and then `<figcaption>` conent is the figures caption as text.

When using HTML5 put:

`header, section, footer, aside, nav, article, figure, figcaption {`
`display: block};`

for formating reasons.

## Chapter 18: Process and Design

Know who your audience is, why they visit your site, and what info they want and when they will come back.
Site maps is a tree like structure for the organization of all of the pages on your website. Wireframe allow you to organise the information on your prospective web page. Use contrast to creat a visual hierarchy for the user. You can do this using size, color, style, and images. Using groups and similarities to design your navigation pages.

## JavaScript

When creating a script, first create a flowchart for the tasks and then have a list of steps for each task.
A script is a list of instructions. Each time the script is used only a part of it may be used. The task must be solved programatically.

An Object is made of properties or methods. A property is a triat that exists already and a method is an action done. html, css, and js all get linked together. Use `<script>` to link the js document to the html document. the script tag has an src attribute that should be the pathway to the js file. JavaScript runs where it is on the html document.
