# Mocks

A place where I try and replicate various websites and pages. As much as possible, I avoid looking at the underlying code and hopefully learn a lot in the practice!

## Getting Started

All mocks are separated into their own folders which contain a basic hierarchical structure and require no build system. These are static, i.e. pure `HTML`, `CSS` and `JavaScript`.

## Tools

- [Microsoft VS Code](https://code.visualstudio.com/) - I use this for most coding
- [CodePen](https://codepen.io/#) - A great tool for working quickly and iteratively with more visual aspects of a page.

## The Current Mocks:

- [Koogle](https://github.com/alexmaday/mocks/tree/master/google) had some interesting challenges
  - I had problems styling the search input element and for whatever reason I just couldn't get it right. So I decided I'd actually insert the input inside a `div`, style that and make `input` transparent; don't think it's the _right_ way, so I'll have to research this ...
  - Dynamically changing CSS properties such as the width of an input in relation to the page, the changing border radius of an element as it's height changes. Can these properties be `calc`ed or do I need something more, e.g. `SASS` or `JavaScript`.

## TODO

- Finish Koogle
  - Navbar Apps and Account need converted to images
  - Make it responsive. Consider mobile first next time :wink:!
  - Search input
    - needs to be rounder
    - needs hover effect
  - Buttons
    - box-shadow needs work
