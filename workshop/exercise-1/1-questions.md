# HTML Comprehension Questions


## Q1 - For each of the following HTML documents, is the HTML valid?

Type true/false in the provided [ ].

a) [false ] `<div><span>hello</div></span>`

Fixed: `<div><span>hello</span></div>`

b) [false ]

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

c) [false ] `<ul></ul><img/><ol><li>one</li></ol>`

Fixed: 

`<ul>
    <li>
        <img/>
        <ol>
            <li>one</li>
        </ol>
    <li>
</ul>`


## Q2 - What is a screenreader and why should we care about them?

_Feel free to use the powers of Google here, but please provide link(s) to your source(s)_

A screenreader is an assistive technology essential to people who are blind, and helpful to people who are visually, illiterate, or have learning disability (source:https://en.wikipedia.org/wiki/Screen_reader )


We should care about them because there are laws that exist about accessibility, and fines to pay in case a website does not comply to the law. And it is important to help everybody have access to the information of a website, who have disabilities or not.


## Q3 - For each of the following cases, which tags will be needed?

a) You want to create a webpage with the photos from your latest vacation
<h1>, <img>

b) You want to create a website that lists all the art gallery websites in your city and links to their website.

<h1>, <ul>, <li>
c) You want to sell designer hats. You need to receive orders from the user.

<h1>, <form>, <input>


## Q4 - Can a button be a child of a button? Explain your reasoning

No, a button can not be a child of a button, because it is not a text. 




## Q5 - What is the most generic tag you can use?

<html>


## Q6 - What do the following achronyms stand for?

a) `a` Anchor

b) `ol` Ordered list

c) `ul` Unordered list

d) `li` List

e) `tr` Table row

f) `th` Table head

g) `td` Table data


## Q7 - Usually, `td` elements are children of what kind of elements?

They are children of table row (tr) element.

## Q8 - What is the difference between td and th?

Table data (td) is the content of a table cell, and the table header (th) is the name of the table cell.

## Q9 - Which tag makes the text appear bigger: h1 or h3?

H1 makes the text appear bigger than h3 because it is the first one, and the text height decreases afterward.

## Q10 - In which situation can you use self closing tags?

when the element has no child.

## Q11 - What is autofilling and why is it important?

Autofilling is when your browser is able to fill up automatically the information for you, so it is a time and error saver.

## Q12 - Which attributes are always present in an img element?

They always have an src attribute that corresponds to the location of the image on the Internet.

## Q13 - Which attribute is always present for an anchor tag?

They always have an href attribute that corresponds to the destination address.

