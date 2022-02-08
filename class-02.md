# Class 02 Reading Notes

## HTML & CSS

### Chapter 2: Text

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

### Chapter 10: Introducing CSS

Each html element has its own box. Block elements start on a new line while inline elements flow with the text. CSS allows you to control how each element box looks.

`p {`
`font-family: Arial;}`

In this example p is the selector and indicates the element being effected. The rest of the text is the declaration which is what is being changed and in what way. `font-family` is the property and `Arial` is the value.

#### External CSS

`<link>` is used to tell the browser where to find the external css file. Every `<link>` should have these attributes:

- `href` - The path to the css file
- `type` - the type of document being linked. in this case text/css.
- `rel` - the relationshi between the html file and the css file linked. in this case stylesheet.

#### Internal CSS

You can put CSS insie the html file within the `<style>` tag. You should not use internal css if your website has more than one page.

#### Class Selectors

- Univeral selector - `* {}`
- Type Selector - same as element name
- Class Selector - `.nameOfClass {}` or `p.nameOfClass {}` (all p elements with defined class name)
- ID Selector - `#IDName {}`
- Child Selector - `li>a {}` (any a elements iside of li elements)
- Descendant selector - `p a {}` (targets a elements that sit inside a p element even if there are other elements between them.)
- Adjacent Sibling slector - `h1+p {}` (get to the first p after any h1)
- General Sibling Selector - `h1~p` (if you had two p elements that are siblings of an h1 this rule would apply to both)

#### CSS Rules Cascade

If two rules are the same the last one wins. The more specific rule will win over less specific rules. you can add `!important` after any property value to indicate that it should take precident.

#### Inheritance

Rules applied to a parent element will be applied to most child elements. This means that child elemet inherited the rule.

#### Use External Style Sheets

All of your pages can share the same file sheet. It is good practice. The rest of the site will load faster. I is easier to edit. There are times when you might want to add internal css for a tweak or two.

#### Different Versions and Browser Quirks

There and different versions of css. Some browsers don't support all of the newest versions properties. Test your site on more than one browser before launch. Use different computers to test your site. Check your site on different OS. When a css property doesn't display properly it is considered a browser quirk or CSS bug.
