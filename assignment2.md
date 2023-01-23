# Javascript quiz (Basic Level - 2

Why do we use functions in JavaScript?
A JavaScript function is a block of code designed to perform a particular task.A JavaScript function is executed when "something" invokes it (calls it).

What is Function Invocation?
The JavaScript Function Invocation is used to execute the function code and it is common to use the term call a function instead of invoke a function. The code inside a function is executed when the function is invoked

Does a function behave like an object in Javascript? Prove it by an example.
In JavaScript, functions are called Function Objects because they are objects. Just like objects, functions have properties and methods, they can be stored in a variable or an array, and be passed as arguments to other functions.

What are Events in Javascript?
JavaScript's interaction with HTML is handled through events that occur when the user or the browser manipulates a page. When the page loads, it is called an event. When the user clicks a button, that click too is an event.

What is a string?
JavaScript strings are for storing and manipulating text. A JavaScript string is zero or more characters written inside quotes

What is an array? Is it static or dynamic in Javascript?
In JavaScript, array is a single variable that is used to store different elements. It is often used when we want to store a list of elements and access them by a single variable. JavaScript Arrays are Dynamic in nature which means, the length of the array can be modified at run time

Difference between Map and Set?
The Set is a one-dimensional array with unique keys, while the Map is a two-dimensional array with key-value pairs, where each key shall be unique.

Difference between Array and Map?
An array is a collection of items stored at contiguous memory locations. The idea is to store multiple items of the same type together. A map is an associative container that stores elements in a mapped fashion. Each element has a key value and a mapped value. No two mapped values can have equal key values.

What are array methods? List a few names?
Array methods are pre defined functions that only works on arrays, they don't access any internal data of the array object. some of them are:

1. map( )
2. filter( ) ·
3. sort( ) ·
4. forEach( )
5. concat( )
6. every( )

In how many ways can we traverse through an array in Javascript?
There are multiple ways one can iterate over an array in Javascript some of them are :
for loop
for-in loo
while loop
do-while loop
forEach loop.

### Reverse an array

const arr=[1,2,3,4,5];
let reversearr=[];
reverseArr=arr.reverse();
console.log(reverseArr);

### Explain the properties of the join array method function via program?

The JavaScript Array join() Method is used to join the elements of an array into a string. The elements of the string will be separated by a specified separator and its default value is a comma(, ).
function joins() {
var a = [ 1, 2, 3, 4, 5 ];
console.log(a.join('.'));
}
func();

### Show all the values of an array in a html webpage using DOM and forEach method

const arr=[1,2,3,4,5];
arr.forEach((e=>(console.log(e))));

### merge two sets in javascript

const a = new Set([1, 2, 3]);
const b = new Set([4, 5, 6]);
const result = new Set([...a, ...b]);console.log(result);
