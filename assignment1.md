#Javascript quiz (Basic Level - 1)

What is JavaScript?
JavaScript is a dynamic computer programming language where the interpreter assigns variables a type at runtime based on the variable's value at that time. It is lightweight and most commonly used as a part of web pages,

What is the difference between b/w let and var?
let keyword can be updated but cannot be re-declared into the scope but the var keyword can be updated and re-declared into the scope.also the scope of var keyword is functional scope and that of let keyword is block scope.

Why do we prefer const over var?
Once you assign a value to the variable declared as const, you cannot assign some other value to the const variable. So there may not be problems associated with redeclaration.

What is the use of javascript in web browsers?
JavaScript helps us to execute complex actions and also enables the interaction of websites with visitors. Using JavaScript, it is also possible to load the content in a document without reloading the webpage

What are Objects?
A javaScript object is an entity having state and behavior (properties and method). For example: car, pen, bike, chair, glass, keyboard, monitor etc. javascript does not follow the concept of classes.

What is an array and how is it different from an Object in Javascript?
An array is used to store a collection of data,lets you store multiple values in a single variable. It stores a fixed-size sequential collection of elements of the same type but The data inside objects are known as Properties that consist of a key and a value.

What is a function?
JavaScript functions are used to perform operations. We can call JavaScript function many times to reuse the code.

How can we implement call by value and call by reference in Javascript?
in call by value It copies the value of a variable passed in a function to a local variable.
Both these variables occupy separate locations in memory. Thus, if changes are made in a particular variable it does not affect the other one but in call by reference the original variable gets modified on changes in other variables.

What are the primitive data types in Javascript?
In JavaScript, a primitive is data that is not an object and has no methods or properties. There are 7 primitive data types:
string
number
bigint
boolean
undefined
symbol
null

What is DOM?
DOM stands for Document Object Model. It is a programming interface that allows us to create, change, or remove elements from the document.

#Average of array nums in Javascript

const arr = [1, 2, 3, 4, 5];
var sum = 0;
for (var i=0;i< arr.length; i++) {
sum += number;
}
var average = sum / arr.length;
console.log(average);

#Swap two numbers by reference

let myNum={
num1:5;
num2:10;
}
function swap(num1, num2){
var x=num1;
num1=num2;
num2=var;
}
swap(myNum.num1,myNum.num2);

#Print the fibonacci sequence

const number = parseInt(prompt('Enter the number of terms: '));
let n1 = 0, n2 = 1, nextTerm;

console.log('Fibonacci Series:');

for (let i = 1; i <= number; i++) {
console.log(n1);
nextTerm = n1 + n2;
n1 = n2;
n2 = nextTerm;
}

#Sort an array by both ascending and descending order

const arr = [56 ,77,4,6];
arr.sort();
console.log(arr);
arr.reverse();
console.log(arr);
