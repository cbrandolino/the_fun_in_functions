# <a id="meta"></a>The fun in functions (also, zombies)
## A practical beginner's guide to functional programming with Javascript.

## <a id="meta_index"></a>Index

- [Meta](#meta)
    - [Index](#meta_index)
    - [Audience and scope](#meta_audience)
    - [Conventions](#meta_conventions)
    - [Reading the guide](#meta_reading)
- [Intro: Zombies](#intro)
- [Chapter 1: Where we are introduced to first-class function, gather vital supplies and implement map()](#c1)
    - [Functions as arguments](c1_functions_as_arguments)
    - [The imperative approach](c1_the_imperative_approach)
    - [The functional approach](c1_the_functional_approach)
    - [Other uses of applyToEach](c1_other_uses)
    - [Glossary](c1_glossary)

## <a id="meta_audience"></a>Audience and scope
This guide is aimed at programmers with some basic experience of Javascript who:

- Want to make a more extensive and more conscious use of its functional capabilities;
- Are curious about all the fuss around FP;
- Like magic.

Each chapter will introduce one of the many concepts of FP, combining it with the 
previous ideas to tackle real-life, zombie-related problems in a functional fashion.

Being a beginner's guide, some non-functional javascript features are also explained
*en passant*, in order to clarify the examples.

## <a id="meta_conventions"></a>Conventions

This guide respects [Douglas Crockford's conventions on javascript syntax](http://javascript.crockford.com/code.html), since most other manuals follow
them and we'd rather keep our personal and quite controversial opinions on
javascript style at bay in a text aimed to beginners.

Every function is documented with [JSDoc](http://usejsdoc.org/)-style 
declaration.

The result of function evaluations is represented as follows:

    Math.floor(1.3);
    result: 1

## <a id="meta_reading"></a>Reading the guide

Many concepts will be introduced in each chapter; at the end of the chapter they will be summarized in a small **glossary** section.

It is very important to read the chapters in order. If there is still 
something you don't understand at the end of a chapter, feel free to open an
issue on the github repository and I will try to include further explanations
in the following versions of the guide.

You are encouraged to type in all the code in the javascript console as we go, 
to see the results immediately. To open the javascript console in Chrome, 
use `Ctrl` + `Shift` + `i` to open the developer tools panel, and press `esc`
to toggle the console.


