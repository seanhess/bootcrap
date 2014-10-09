bootcrap
========

Prototype web applications without worrying about how they look.

Motivation
----------

CSS Frameworks like Bootstrap help you make an application look good more easily. It looks just good enough, however, that we find ourselves spending significant time messing with css classes and styling to keep our views looking nice. 

When prototyping, you are exploring ideas. They might be technical, or even involve some user experience, but the user interface will almost definitely change dramatically. The code will also need to be rewritten. It doesn't make sense to waste any time on visuals in this situation. 

What is Bootcrap?
-----------------

Bootcrap is a set of guidelines to follow, and a simple css skin that will help you avoid the temptation to make things look good while prototyping. 

Installation
------------

    bower install bootcrap

Then link to the css file

Guidelines
----------

- make it look like wireframes
- use vertical layout (not horizontal, no columns)
- never use classes or customize the look

- [ ] buttons with icons, font awesome
- [ ] tables
- [ ] navigation / header with title, menu

Later, add extra react components? Like sliders, etc? No...

Elements
--------

```
<label>   bold, full width
<input>   full width
<button>  full width
<a>       inline
<p>       vertical padding for text elements
<mark>    highlight a run of text
```

Ideas under review

```
<section> shouldn't have any padding
<article> padding?
<aside>   should we allow simple columns that float left or right?
<ul>      should look a little nicer?
<ol>
<li>      
<menu>
<menuitem> 
<nav>
<output>  ???
<blockquote>
<progress>
<q>       short quote
<s>       strikethrough?
<header>  
<footer>  
```


Thanks To
---------

Bootstrap, Foundation, Nate Jones




