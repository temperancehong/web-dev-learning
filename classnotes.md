# HTML notes

Server respond with instructions (source code) HTML, CSS and JS.

Define HTML with tags.


## HTML Boilerplate


One head, one body.

Head: meta data (including style sheet etc)

Title element: the title for the browser windows

Body: all the content of the page 

Unordered list: ul, with descendents li

Ordered list: ol, with descendents li

Nested list: put the list inside a list


Anchor text: the `a` tag

Image tag: no closing tag, just image; alt: text description for the image


## Div and Span

Div: content division element

Span: inline generic element, we can add style to span


- HR and BR

HR: horizontal rule element, a horizontal line

BR: line break element

sup, sub: superscript and subscrip (power)

- HTML entities

Series for specific characters

## Semantic markup

https://www.w3schools.com/html/html5_semantic_elements.asp 

`<main>, <section>, <footer>` instead of `<div>`

```html
<article>
<aside>
<details>
<figcaption>
<figure>
<footer>
<header>
<main>
<mark>
<nav>
<section>
<summary>
<time>
```

## Emmet

Use emmet to type abbreviation and get elements

## Table in HTML

`<td>` defines a single table cell.

`<tr>` is table row, grouping elements into a row

`<th>` defines a table header

`<thead>, <tfoot>, <tbody>` marking head, body and foot


- Rowspan and column span: those that extend multiple rows/columns

## Forms in HTML

`<form>` is itself a container

Form action: where the data should be sent, for example `/search/`

Form attribute: which HTTP method should be used

### Input

No closing tag

https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input 

### Label

Direct connection with inputs, make things clickable

The `for` attribute is associated with `id` which should be unique on a page, one lable, one connection


### Buttons

Name with submission

The server is looking for

- Radio buttons: only select one
- Check boxes: can select multiple

```html
<div>
      <input type="radio" id="huey" name="drone" value="huey" checked />
      <label for="huey">Huey</label> <!-- for corresponding to the id attribute -->
    </div>
```

The `for` in the label corresponds to the `id` in the input

Value: sending to the form the value

- Select

- Range input

## HTML5 Validation

Using javascript

Server side validation