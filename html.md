### HTML

- HTML has elements for 'tags' <h1></h1>
- There's usually a 'pair' of tags, except for elements that can't have children,
- like <img /> and <input />


### tags 

<div>: general wrapper element (by default display:block)
<span>: wrapper for some text (display:inline-block)
- you can put stuff into div with flex, instead of using span

<img> has a 'src'

<header>

<main>: similar as div

<select>: drop down, but we use UI kit now


### form elements

<input />: can have a 'type' of 'text', 'number', 'checkbox', or 'radio'

<button>: a button of type='submit' within a form will submit that form

<form>: wraps around a bunch of inputs and collect their data

<a>: wrap 'href'

<p>: paragraph


### props

There are built-in props, that are standard to HTML elements (like onClick, or value or src)
but you can also add custom props to your own elements

### React

- React element (or 'components') always start with an uppercase letter
- React props are always camelCase, while in HTML they're all lowercase

<ReactComponent>
    <div></div>
</ReactComponent>
