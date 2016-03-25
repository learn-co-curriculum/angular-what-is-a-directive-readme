# What is a Directive?

## Overview

You might not have noticed, but we've used directives already in our previous labs. Directives are essential to learning Angular, so hold on tight!

## Objectives

- Describe what Directives are

## Directives, deep down

Directives are essentially "markers" on a HTML element that tell Angular to attach a specific behavior to the HTML element - either something small like a click event, or actually completely transforming the DOM node to display a list of data.

Directives can be either an actual HTML element or an attribute on a HTML element.

```html
<my-directive></my-directive>

<!-- these are the same -->

<div my-directive></div>
```

However, not all directives can be used in both ways - some are restricted to being just an attribute or just an element. All of the built-in directives from Angular are restricted to being used as attributes. For any other ones (such as custom directives you download online) you will have to check the documentation on how to use it.

## Types of directives

There are two types of directives - event and behavioral. Event directives handle all of the events on a HTML element we might need - for example, `click`, `mouseover`, `keydown`, etc. These are the same as normal JavaScript events that we would add event listeners for.

Behavioral directives are directives that manipulate the DOM. For example, we might have a list that repeats our DOM node for every item in a list. We could even have a directive for hiding and showing content depending on one of our variables' value.

We'll have more on these in the next couple of lessons.

## Built-in directives

Luckily for us, Angular comes with a tonne of built-in directives that do what we mentioned above and more. We'll be looking into the built-in ones in the other sections of this unit. Angular's built-in directives are prefixed with `ng-` (you might have noticed we're already using `ng-app` and `ng-controller` - these are just directives!) `ng-app` tells Angular what DOM node to put our application inside of. `ng-controller` tells Angular to attach our controller to that DOM node so we can access the controller inside of the element. In case you hadn't guessed, the `ng-` stands for Angular and it's best practice NOT to use this prefix on our own directives. 

<p data-visibility='hidden'>View <a href='https://learn.co/lessons/angular-what-is-a-directive-readme'>Angular What Is A Directive</a> on Learn.co and start learning to code for free.</p>
