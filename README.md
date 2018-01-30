# default-beauty.css

[![MIT Licensed](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/OleksiyRudenko/default-beauty.css/blob/master/LICENSE.md)
[![CSS Variables](https://img.shields.io/badge/CSS-variables-orange.svg)](https://www.w3.org/TR/css-variables-1/)
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome#front-end-development)

> Work in Progress

 - [ ] Building quick web page/app prototype?
 - [ ] Want to see anything more pleasant than default
       browser styling from the very first page load?
 - [ ] A beginner focused more on HTML?

If anything above is what you would tick then this project
will be of use for you.

The idea behind is to beautify a bit default styles whenever
you just cannot pay much efforts to styling yet.

[Check an example](https://oleksiyrudenko.github.io/default-beauty.css/).

Note that [index.html](index.html) contains no style or element class definitions
(with exception of pre-formatted block content).

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**

- [Installation](#installation)
- [Special features](#special-features)
  - [CSS3 variables](#css3-variables)
  - [Page `header` and `footer`](#page-header-and-footer)
- [Credits to the project](#credits-to-the-project)
- [TODO](#todo)
- [Credits](#credits)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Installation

Tastes best with [`normalize.css`](https://github.com/necolas/normalize.css)
or an extended flavoured variant of `normalize.css` like
[this one](https://github.com/OleksiyRudenko/normalize.css), and
with [a font of your choice](https://www.w3schools.com/howto/howto_google_fonts.asp)
to improve default typography readability.

It will be a good start to add the following snippet to your web page's `<head>`.

```
    <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Overpass%20Mono">
    <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Open+Sans">
    <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.0.4/css/all.css">
    <link rel="stylesheet" href="https://cdn.rawgit.com/OleksiyRudenko/normalize.css/28e3dc36/normalize.css">
    <link rel="stylesheet" href="https://cdn.rawgit.com/OleksiyRudenko/default-beauty.css/482728bd/default-beauty.css">
```

You may also want to download your own up-to-date copies of the two latter stylesheets
from [official `normalize.css` repo](https://github.com/necolas/normalize.css) or
[`normalize.css` fork](https://github.com/OleksiyRudenko/normalize.css),
and [official `default-beauty.css` repo](https://github.com/OleksiyRudenko/default-beauty.css).

[TOC :arrow_double_up: ](#table-of-contents)

## Special features

Feel free changing whatever you like.

### CSS3 variables

`default-beauty.css` employs
[CSS variables](https://www.w3.org/TR/css-variables-1/)
(more on [MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/Using_CSS_variables))
with a somewhat not a 100% browser support and therefore may not pass
[strict validation](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Frawgit.com%2FOleksiyRudenko%2Fdefault-beauty.css%2Fmaster%2Fdefault-beauty.css&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en).

Should you face any issues with it, please
[let me know](https://github.com/OleksiyRudenko/default-beauty.css/issues).

Quick fix:
1. Download `default-beauty.css` or fork this project
2. Replace every `var(--...)` with a relevant value from `:root` section
3. Remove variable definitions from `:root` section

### Page `header` and `footer`

Just add &lt;header&gt; and &lt;footer&gt; elements to have distinctive
styling of your page header and footer.

Last element in `footer` (and first as well if it is the only element
in `footer`) floats to the right. If this not what you want
remove `margin-left: auto;` rule from `footer > *:last-child` ruleset.

[TOC :arrow_double_up: ](#table-of-contents)

## Credits to the project

If you like this project, please, add the following somewhere in the bottom
of your beautified page.

```
    <p><small>
        Styled with
        <a href="https://github.com/OleksiyRudenko/default-beauty.css" target="_blank">
            <i class="fas fa-heart"></i> Default-Beauty.css <i class="fab fa-github-square"></i>
        </a>
        and
        <a href="https://github.com/OleksiyRudenko/normalize.css" target="_blank">
            normalize.css fork <i class="fab fa-github-square"></i>
        </a>
    </small></p>
```

It will look like this:
**Styled with
<a href="https://github.com/OleksiyRudenko/default-beauty.css" target="_blank">
    <i class="fas fa-heart"></i> Default-Beauty.css <i class="fab fa-github-square"></i>
</a>
and
<a href="https://github.com/OleksiyRudenko/normalize.css" target="_blank">
    normalize.css fork <i class="fab fa-github-square"></i>
</a>**, but more pleasantly.

[TOC :arrow_double_up: ](#table-of-contents)

## TODO

Check [project issues](https://github.com/OleksiyRudenko/default-beauty.css/issues).

Any suggestions? Please, do not hesitate submitting
[an issue](https://github.com/OleksiyRudenko/default-beauty.css/issues).

[TOC :arrow_double_up: ](#table-of-contents)

## Credits

This project wouldn't have ever happened without [Kottans](https://github.com/kottans)

![Kottans logo](https://avatars0.githubusercontent.com/u/6013442?s=200&v=4)

[TOC :arrow_double_up: ](#table-of-contents)