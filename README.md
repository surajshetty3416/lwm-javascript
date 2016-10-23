###Learn With Me - JavaScript
>( Reference -- Tutorials by Tony Alicea on Javascript)

##Contents
 - [The Setup](#the-setup)
 - [Name value pairs](#name-value-pairs)
 - [Objects](#objects)
 - [Global Execution Context](#global-execution-context)
 - [Hoisting](#hoisting)

###The Setup
 - Browser ([Chrome](https://www.google.com/chrome/browser/desktop/ "Yeah! It's free .. It always was") Recommended) - to run javascript code
 - Text Editor (eg. [Sublime Text](https://www.sublimetext.com/3 "Download one of the best editor")) - To edit code :P

      OR

 - Use [JSbin.com](https://jsbin.com/?js,console,output) to run and edit Javascript online.

### Name Value Pairs
~~~js
// here profession is name and 'Web developer' is value assigned to the name.
var profession = 'Web developer'
~~~

### Objects
In Javascript it is basically a collection of name value pair
eg.
~~~js
var obj = {
  name1 : 'value1',
  name2 : {               //
    name3 : 'value3'      // object itself as value
  }                       //
}
~~~

### Global Execution Context

Whenever the js code runs, it runs inside the execution context.

All the JS code is wrapped (by js engine) within an execution context which by default creates two things:
    1: Global Object like 'window'
    2: 'this' which usually points to window (when in global execution context)

[Explanation link](http://jsbin.com/mezamu/edit?js,console)

### Hoisting

Hoisting is a term you will not find in the JavaScript docs. Hoisting was thought up as a general
way of thinking about how execution context (specifically the creation and execution phases) work
in JavaScript. But, hoisting can lead to misunderstandings. For example, hoisting teaches that
variable and function declarations are physically moved to the top your coding, but this is not
what happens at all. What does happen is the variable and function declarations are put into memory
during the compile phase, but stays exactly where you typed it in your coding.

[Explanation Link](https://jsbin.com/qitaneh/edit?js,console)
[extra read](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Memory_Management)