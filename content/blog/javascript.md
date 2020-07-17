
---
title: "Javascript"
date: 2020-07-10T19:41:59+05:30
tags: ["frontend-course","script","programming","Steve"]
categories: ["webdevelopment"]
Author: "Steve"
images:
  - /images/js1.jpg
draft: false
---

{{< figure src="/images/js1.jpg" >}}

Javascript

JavaScript, often abbreviated as JS, is a programming language that conforms to the ECMAScript specification. JavaScript is high-level, often just-in-time compiled, and multi-paradigm. It has curly-bracket syntax, dynamic typing, prototype-based object-orientation, and first-class functions
javascript It has curly-bracket syntax,

Strings
Strings are values made up of text and can contain letters, numbers, symbols, punctuation, and even emoji.

Strings are contained within a pair of either single quotation marks '' or double quotation marks
example
'This is a string
"This is the 2nd string
Enclosing quotation marks let us say you’re trying to use quotation marks inside a string. You’ll need to use opposite quotation marks inside and outside. That means strings containing single quotes need to use double quotes and strings containing double quotes need to use single quotes.
example
"It's six o'clock.";
'Remember to say "please" and "thank you."';
Alternatively, you can use a backslash \ to escape the quotation marks. This lets JavaScript know in advance that you want to use a special character.
Here’s what that looks like reusing the examples above:

EXAMPLE
'It\'s six o\'clock.';
"Remember to say \"please\" and \"thank you.\"";
Properties and methods
Strings have their own built-in variables and functions, also known as properties and methods. Here are some of the most common ones.

length
A string’s length property keeps track of how many characters it has.

EXAMPLE
"caterpillar".length;
OUTPUT
11
toLowerCase
A string’s toLowerCase method returns a copy of the string with its letters converted to lowercase. Numbers, symbols, and other characters are not affected.

EXAMPLE
"THE KIDS".toLowerCase();
OUTPUT
"the kids"
toUpperCase
A string’s toUpperCase method returns a copy of the string with its letters converted to capitals. Numbers, symbols, and other characters are not affected.

EXAMPLE
"I wish I were big.".toUpperCase();
OUTPUT
"I WISH I WERE BIG."
trim
A string’s trim method returns a copy of the string with beginning and ending whitespace characters removed.

EXAMPLE
"   but keep the middle spaces   ".trim();
OUTPUT
"but keep the middle spaces"
Learn / Resources / AboutJavaScript.com logo© 2016 - 2020 JavaScript.com
