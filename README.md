# Java 8 New Features

This repository includes a presentation on Java 8 new features.

## license

The presentation is released under the [Creative Commons Attribution 4.0 Int. License](http://creativecommons.org/licenses/by/4.0/)

Tools listed below are released under their own license.

## How to build

The slides are built using markdown and a minimalist toolset:

Slides content is in `java8-new-features.md`.

The perl script `remark.pl` will convert the markdown file to an html file using [remarkjs](https://remarkjs.com) as the presentation engine. The result is a single `java8-new-feature.html` file. That is all you need to present (as long as you have an internet connection).

There are currently problems converting to PDF. This is linked to my choice of a 16:9 ratio. It works well on screen but doesn't seem to be compatible with the printers. My best results so far is using the ISOB5 format, landscape with 85% scaling. (I am suspecting that the CSS layout has specific device size but haven't had a chance to check this out).

## Need something more sophisticated

If you are unhappy with the minimalist approach, you can try something like [backslide](https://github.com/sinedied/backslide). `Backslide` can generate html and PDF out of the markdown file but you will first need to install nodejs and have access to a C++ compiler.

The only difference is that you will get `backslide` custom style instead of `remarkjs` default one.

Before you do, I'll encourage you to read about Doug McIlroy's programming philosophy ("The real hero of programming is the one who writes negative code"). A summary of its challenge to Knuth can be found [here](http://www.leancrew.com/all-this/2011/12/more-shell-less-egg/)
.
