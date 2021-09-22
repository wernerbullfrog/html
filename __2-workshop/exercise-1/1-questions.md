# HTML Comprehension Questions

## Q1 - For each of the following HTML documents, is the HTML valid?

Type true/false in the provided [ ].

a) [false] `<div><span>hello</div></span>`

b) [false]

```html
<ul>
<li>one</li>
</ol>
```

c) [True] `<ul></ul><img/><ol><li>one</li></ol>`

## Q2 - What is a screenreader and why should we care about them?
A screenreader is a software that are used to aid the visually impaired to interact with websites. They convert html tags to audio/brail files. 

source -> https://developer.mozilla.org/en-US/docs/Glossary/Screen_reader
_Feel free to use the powers of Google here, but please provide link(s) to your source(s)_

## Q3 - For each of the following cases, which tags will be needed?

a) You want to create a webpage with the photos from your latest vacation
<h1><div><img> 


b) You want to create a website that lists all the art gallery websites in your city and links to their website.

<h1> <div> <ul> <li> <a>

c) You want to sell designer hats. You need to receive orders from the user.

<h1> <div> <img> <a> <form> <input> <select> <option> <button>

## Q4 - Can a `button` be a child of a `button`? Explain your reasoning

no because a button is a clickable tag and you can't click something within a click

## Q5 - What is the most generic tag you can use?
<div></div>
## Q6 - What do the following achronyms stand for?

a) `a` anchor

b) `ol` ordered list

c) `ul` unordered list

d) `li` list item

e) `tr` table row

f) `th` table head

g) `td` table data

## Q7 - Usually, `td` elements are children of what kind of elements?
<table>

## Q8 - What is the difference between td and th?
th refers to the first row of the table as for td refers to simply adding a table cell

## Q9 - Which tag makes the text appear bigger: h1 or h3?
<h1>

## Q10 - In which situation can you use self closing tags?
when the tag does not have any children 

## Q11 - What is autofilling and why is it important?
autofilling is completed by the browser in a <form> tag. This is how information is sent to a server

## Q12 - Which attributes are always present in an img element?
src & alt
## Q13 - Which attribute is always present for an anchor tag?
href