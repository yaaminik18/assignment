# theory

What are the basic data types in TypeScript?
Boolean
String
Number
Array
Tuples
Function
Enum

What is Generic data type.
Generics allow creating 'type variables' which can be used to create classes, functions & type aliases that don't need to explicitly define the types that they use.
Functions
Classes
Type Aliases

What is type inferring in TS.
TypeScript is a typed language. However, it is not mandatory to specify the type of a variable. TypeScript infers types of variables when there is no explicit information available in the form of type annotations.
Types are inferred by TypeScript compiler when:
Variables are initialized
Default values are set for parameters
Function return types are determined

How to define Generic type for Classes.
TypeScript supports generic classes. The generic type parameter is specified in angle brackets after the name of the class. A generic class can have generic fields (member variables) or methods.
class KeyValuePair<T,U>
{
private key: T;
private val: U;

    setKeyValue(key: T, val: U): void {
        this.key = key;
        this.val = val;
    }

    display():void {
        console.log(`Key = ${this.key}, val = ${this.val}`);
    }

}

let kvp1 = new KeyValuePair<number, string>();
kvp1.setKeyValue(1, "Steve");
kvp1.display(); //Output: Key = 1, Val = Steve

let kvp2 = new KayValuePair<string, string>();
kvp2.SetKeyValue("CEO", "Bill");
kvp2.display(); //Output: Key = CEO, Val = Bill
In the above example, we created a generic class named KeyValuePair with a type variable in the angle brackets <T, U>. The KeyValuePair class includes two private generic member variables and a generic function setKeyValue that takes two input arguments of type T and U. This allows us to create an object of KeyValuePair with any type of key and value.
