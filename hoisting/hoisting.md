### Hoisting

Hoisting is a term you will not find in the JavaScript docs. Hoisting was thought up as a general
way of thinking about how execution context (specifically the creation and execution phases) work
in JavaScript. But, hoisting can lead to misunderstandings. For example, hoisting teaches that
variable and function declarations are physically moved to the top your coding, but this is not
what happens at all. What does happen is the variable and function declarations are put into memory
during the compile phase, but stays exactly where you typed it in your coding.

[Explanation Link](https://jsbin.com/qitaneh/edit?js,console)
[extra read](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Memory_Management)