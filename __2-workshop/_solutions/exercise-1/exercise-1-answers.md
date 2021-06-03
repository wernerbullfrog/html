# HTML Comprehension Questions


## Q1 - For each of the following HTML documents, is the HTML valid?

- Type true/false in the provided [ ].
- If it's false fix it.

a) [ false ] `<div><span>hello</div></span>`

Fixed:  `<div><span>hello</span></div>`

b) [ false ]

```html
<ul>
<li>one</li>
</ol>
```

Fixed:

```html
<ol>
    <li>one</li>
</ol>
```

c) [ false ] `<ul></ul><img/><ol><li>one</li></ol>`

Fixed: _many answers possible_

```html
<ul>
    <li>
        <img/>
        <ol>
            <li>one</li>
        </ol>
    </li>
</ul>
```

## Q2 - What is a screenreader and why should we care about them?

_Feel free to use the powers of Google here, but please provide link(s) to your source(s)_

_answers will vary_




## Q3 - For each of the following cases, which tags will be needed?

a) You want to create a webpage with the photos from your latest vacation

_answers will vary_


b) You want to create a website that lists all the art gallery websites in your city and links to their website.

_answers will vary_


c) You want to sell designer hats. You need to receive orders from the user.

_answers will vary_



## Q4 - Can a button be a child of a button? Explain your reasoning

No. First and foremost because a `button` is an inline element and inline elements should never contain other elements, only text (leaf nodes.) There is also the consideration that a `button` is a clickable element and it could cause some weird behaviour if a clickable element is included inside another.


## Q5 - What is the most generic tag you can use?

`<div>` has **NO** semantic value.


## Q6 - What do the following achronyms stand for?

a) `a` anchor tag

b) `ol` ordered list

c) `ul` unordered list

d) `li` list item

e) `tr` table row

f) `th` table head

g) `td` table cell


## Q7 - Usually, `td` elements are children of what kind of elements?

`td` is a child of the `tr` element.


## Q8 - What is the difference between td and th?

`th` is the header row. It contains the headers for the columns of the table. `td` is for the table data.


## Q9 - Which tag makes the text appear bigger: h1 or h3?

`h1` elements are usually "bigger" than `h3` elements.

Trick question! It is true that the `h1` element is very often bigger than the other heading elements, that is only because of the basic CSS that each browser applies to all HTML. Presentational qualities should never factor in your setting of HTML tags.


## Q10 - In which situation can you use self closing tags?

When the element has no text to render between its tags; e.g. the `<img>` or the `<input>` tags.


## Q11 - What is autofilling and why is it important?

It is when the browser auto-populates input fields. This is a convenience.


## Q12 - Which attributes are always present in an img element?

- `src=""`
- `alt=""`

## Q13 - Which attribute is always present for an anchor tag?

- `href=""`

