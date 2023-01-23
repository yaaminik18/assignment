# Javascript quiz (Basic Level 4)

What are anonymous functions in JavaScript?
It is a function that does not have any name associated with it. Normally we use the function keyword before the function name to define a function in JavaScript, however, in anonymous functions in JavaScript, we use only the function keyword without the function name.

Explain strict comparison and Abstract comparison in javascript?
The abstract and strict comparison operators can be used to check the equality of two operands in JavaScript. Both operators will check the equality of two values and return the boolean value (true or false) based on whether the values are equal or not, The strict equality operator ===, also known as triple equals, compares both the value and the type of its operands.
1 === 1 // true, but
"2" === 2 // false
The abstract equality operator == is also known as the double equals or the loose equality operator When comparing two values with this operator, if both operands are not the same type, JavaScript attempts to resolve the data types by implicitly converting them to the same type before comparing them.

Difference b/w arrow functions and regular functions?
We can write the regular function in two ways, i.e Function declaration, and Function expression but arrow function allows you to create functions more cleanly compared to regular functions. There is no declaration approach here, we can write by using Function expressions only also Curly brackets aren’t required if only one expression is present, and it will implicitly return this result from the function

What is Hoisting in JavaScript?
avaScript Hoisting refers to the process whereby the interpreter appears to move the declaration of functions, variables or classes to the top of their scope, prior to execution of the code.

JavaScript is a garbage collected programming language, explain how?
JavaScript, utilize a form of automatic memory management known as garbage collection (GC). The purpose of a garbage collector is to monitor memory allocation and determine when a block of allocated memory is no longer needed and reclaim it.

Explain Shallow copy vs Deep copy in Javascript?
A deep copy means that all of the values of the new variable are copied and disconnected from the original variable. A shallow copy means that certain (sub-)values are still connected to the original variable

What is Object.freeze
A frozen object can no longer be changed: new properties cannot be added, existing properties cannot be removed, their enumerability, configurability, writability, or value cannot be changed, and the object's prototype cannot be re-assigned. freeze() returns the same object that was passed in.

function radomInTwoRange(min1, max1, min2, max2){
const random1 = (min1, max1) => Math.floor(Math.random() _ (max1 - min1)) + min1;
console.log(random1);
const random2 = (min2, max2) => Math.floor(Math.random() _ (max2 - min2)) + min2;
}
