
<div align="center">
<img src="chrome-devtools.svg" alt="Markdownify" width="150">

# An Intro to Chrome DevTools
### By Gerard Lucas - IT1600-01

<br />

</div>

<div align="center">

[Overview](#overview) • 
[Getting Started](#getting-started) • 
[Elements Tab](#elements-tab) • 
[Console](#console) • 
[Sources Tab](#sources-tab) • 
[Network Tab](#network-tab)

</div>

## Overview

This tutorial serves as a walkthrough of the basic features found in Chrome DevTools--a set of tools built into the Chrome browser designed to help web developers.
We will explore the main features and functions of Chrome DevTools, as well as how they can help you be more productive. First, we will go over some helpful configuration options, and then we will explore common uses of the elements, console, sources, and network tabs.

<br/>
  
This tutorial is aimed at someone just beginning web development. You should have some familiarity with how HTML, CSS, and JavaScript function together to build a website, but detailed knowledge is not necessary. We will cover only the basic uses of DevTools; for full documentation please refer to the [Official Guide](https://developer.chrome.com/docs/devtools/).

<br/>

## Getting Started

opening the console

Just as you have a prefered way of setting up your IDE, you will probably have a way you like to set up your console.

a note that firefox and edge both have consoles also.

pin to right

keep console open (esc hotkey)

lots more to see in "more tools"

<br />

## Elements Tab

is tutorial serves as an introduction and walkthrough of the basic features
found in the Google Chrome Developer Console. We will discuss how it can be helpful for 
We will explo

right click an element on the page -> click inspect element -> elements tab opens focused to this element

<br />

## Console

If you don't have the console drawer open, you can get to it by typing ctrl+shift+j or it is the second tab after hitting F12.  

The two main functions of the console are to view logged messages from developers and to run JavaScript code.  

### *Viewing Messages*

When writing JavaScript, it can often be very useful to write messages from your code that you can view while you test out your website. 
Some of the most common are sending out a message when you reach a certain block of code, or print out the value of a variable. These messages are written by telling the console to log, like the example below.

``` js
console.log("Hello World!");
```

If you monitor the console while browsing popular websites, especially if you have ad-blockers on, you will see many error messages appear in the console. The image below shows a console exception, denoted by the red background and "X". The error message and location of the error is also displayed, in this case, a request to get data is being blocked by an ad-blocker. Clicking
the link to the right (www-embed-player) would navigate the user to a view of the offending code.

<img src="error.png" alt="console error">

### *Writing JavaScript*

``` js
let name = "Friend";
let date = new Date();

console.log(`Hello ${name}! The date is ${date.toLocaleDateString()}.`);
```
<br />

## Sources Tab

is tutorial serves as an introduction and walkthrough of the basic features
found in the Google Chrome Developer Console. We will discuss how it can be helpful for 
We will explo


code snippets - save reusable javascript blocks that are stored in the sources tab.

https://developer.chrome.com/docs/devtools/javascript/snippets/

<br />

## Network Tab

is tutorial serves as an introduction and walkthrough of the basic features
found in the Google Chrome Developer Console. We will discuss how it can be helpful for 
We will explo
