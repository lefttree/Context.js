# Context.js forked

## My modification

The original library providers `attach` method to attach on elements. But 
I wanna use this library with jit.js which already has event listeners. 

To integrate these two, I don't wanna attach the context menu to a element's event,
I hope it can just showup a context menu when the onRightClick of jit.js triggers.
So I reused part of the `attach` function codes and added a new method `show`.

`show(data, e)`

- `data` the same data as `attach`
- `e` event object you can pass in from other event listeners

## About

Context.js is a lightweight solution for contextual menus. Currently, there are two versions.

You can go to original author's website to see the details <a href="http://lab.jakiestfu.com/contextjs/" target="_blank">Visit the Website, lab.jakiestfu.com/contextjs/</a>

## Original Features

<ul>
	<li>Linted: Valid JS</li>
	<li>Can be used with or without Twitters Bootstrap.css</li>
    <li>Icon support for menu items with Twitter Bootstrap icons</li>
	<li>Event Based Links</li>
	<li>Anchor Links</li>
	<li>Headers</li>
	<li>Dividers</li>
	<li>Recursive Menus (infinite depth)</li>
	<li>Vertical Space Detection (turns into a "dropup")</li>
	<li>Horizontal Space Detection (Drops to the left instead of right)</li>
	<li>Add/Delete menus Dynamically</li>
	<li>Even works on <a href="http://google.com" class="inline-menu">Inline Links</a></li>
    <li>Dynamic menu items through callbacks during menu creation</li>
</ul>
