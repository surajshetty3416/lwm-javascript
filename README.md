###Learn With Me - JavaScript
>( Reference -- Tutorials by Tony Alicea on Javascript)

##Contents
 - [The Setup](#the-setup)
 - [Name value pairs](#name-value-pairs)
 - [Objects](#objects)
 - [Global Execution Context](#global-execution-context)
 - [Hoisting](hoisting/hoisting.md)

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

